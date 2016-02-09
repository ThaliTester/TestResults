#### Test 58380500c26a9ef_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/dalvikvm-heap( 3450): Grow heap (frag case) to 9.509MB for 73240-byte allocation
D/Process (  906): killProcessQuiet, pid=3140
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
--------- beginning of /dev/log/system
I/ActivityManager(  906): Killing 3140:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3140
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AutoSetting( 1315): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3474 uid=10079 gids={50079, 3003, 5012}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055)
D/AutoSetting( 1315): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1315): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1315): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1315): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1315): service - handleMessage() setting current location null
D/AutoSetting( 1315): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1315): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055)
,W/fb4a(:<default>):UserScope( 3450): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 3450): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):UserScope( 3450): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/MobileConnectivityChangeReceiver( 3474): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3474): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3474): onOtaspChanged old =0, new =3
V/PhoneMonitor( 3474): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3490 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3193
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3193:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3474/10079)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3474/10079)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3474/10079)
I/ActivityManager(  906): Recipient 3193
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(4278b3a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3450): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/CheckinService( 2177): Checkin interval check for package: unspecified last checkin: 1454981449522 min interval config: 0 actual interval: 2114303
D/PMS     (  906): acquireWL(42761b80): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4278b3a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2177): Checking schedule, now: 1454983563862 next: 1454981479433
I/CheckinService( 2177): active receiver: enabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2177, uid=10029, userID:0
I/CheckinService( 2177): Preparing to send checkin request
I/EventLogService( 2177): Accumulating logs since 1454983252801
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3508 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3152
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3152:com.google.android.youtube/u0a168 (adj 15): empty #17
E/dalvikvm( 3450): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 3450): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3450): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 3450): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3450): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 3450): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3450): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 3450): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3450): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3450): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 3450): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:64, mTXpacketCount:48, avgLinkspeed:24,mAvgTxRate54
D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
I/dalvikvm-heap( 3450): Grow heap (frag case) to 9.964MB for 84664-byte allocation
W/dalvikvm( 3450): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3450): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3450): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3450): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 3450): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3450): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3450): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3508): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3508): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/dalvikvm-heap( 3450): Grow heap (frag case) to 9.980MB for 28144-byte allocation
I/ActivityManager(  906): Recipient 3152
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.youtube (pid 3152): Died!
E/cutils-trace( 3486): Error opening trace file: No such file or directory (2)
W/GAV2    ( 3508): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3508): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/CheckinRequestBuilder( 2177): Checkin reason type: 8 attempt count: 1
I/dalvikvm-heap( 3450): Grow heap (frag case) to 10.019MB for 39954-byte allocation
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3508): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/WifiService(  906): New client listening to asynchronous messages
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2177): Failed to find provider info for com.google.android.wearable.settings
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 3450): Grow heap (frag case) to 10.095MB for 79892-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3508/10151)
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2177/10029)
V/WebViewChromiumFactoryProvider( 3508): Binding Chromium to main looper Looper (main, tid 1) {41b3aef0}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/LibraryLoader( 3508): Expected native library version number "",actual native library version number ""
I/chromium( 3508): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [2][0][0]
I/BrowserStartupController( 3508): Initializing chromium process, renderers=0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/CustomizationManager( 3486): ====startRecUseTime====
D/htc.customization.log.level( 3486):  is 
W/CustomizationLogLevel( 3486): Level value is invalid, use default level 2
E/AudioManagerAndroid( 3508): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(425dde50): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(424e47a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(425dde50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/dalvikvm-heap( 3450): Grow heap (frag case) to 10.282MB for 75760-byte allocation
I/Adreno-EGL( 3508): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3508): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3508): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3508): Local Branch: 
I/Adreno-EGL( 3508): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3508): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3508):                  aa63bbd948f41d15fc72f585e
W/dalvikvm( 1374): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3450/10027)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424e4018 u0 ReceiverList{425003c0 3450 com.facebook.katana/10027/u0 remote:4259e0a8}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424e4018 u0 ReceiverList{425003c0 3450 com.facebook.katana/10027/u0 remote:4259e0a8}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4245a180 u0 ReceiverList{4245a140 3450 com.facebook.katana/10027/u0 remote:424d0830}}
I/NSApplication( 3508): Starting up...
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3450/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3450/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3508/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3508/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3450/10027)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/Process (  906): killProcessQuiet, pid=3215
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3556 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  906): Killing 3215:com.android.vending/u0a74 (adj 15): empty #17
D/CustomizationManager( 3486):  Read ACC file spent 0.081 (s)
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3486): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3486): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3486): Parsing tag category name = system
I/CustomizationCIDLoader( 3486): Parsing tag category name = application
I/CustomizationCIDLoader( 3486): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3486): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3486): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3486): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3486): Parsing tag category name = Settings
D/CustomizationManager( 3486):  Read CID file spent 0.133 (s)
D/CustomizationManager( 3486):  All configurations done spent 0.133 (s)
W/HtcNativeFlag( 3486): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3486): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3486): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3486): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3568 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PMS     (  906): acquireWL(4251cc58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4251cc58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Recipient 3215
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3486
W/dalvikvm( 3568): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 3568): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 3568): VM with version 1.6.0 does not have multidex support
I/MultiDex( 3568): install
I/MultiDex( 3568): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 3568): loading existing secondary dex files
I/MultiDex( 3568): load found 3 secondary dex files
I/MultiDex( 3568): install done
W/dalvikvm( 3568): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 3568): VFY: unable to resolve instance field 36
W/dalvikvm( 3568): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
V/JNIHelp ( 3568): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/PMS     (  906): acquireWL(425fb5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
W/ContextImpl( 3450): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/PMS     (  906): releaseWL(425fb5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3450): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/ProviderInstaller( 3568): Installed default security provider GmsCore_OpenSSL
D/PMS     (  906): acquireWL(4255d268): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3556 10160 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3556/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3556/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3556/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3556/10160)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
W/dalvikvm( 3568): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 3568): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/PMS     (  906): acquireWL(4270def8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3556 10160 null
D/PMS     (  906): releaseWL(4255d268): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 3568): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 3568): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 3568): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
W/dalvikvm( 3568): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
W/dalvikvm( 3568): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2177, uid=10029, userID:0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
I/iu.SyncManager( 2177): SYNC; picasa accounts
D/PMS     (  906): releaseWL(4270def8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  906): killProcessQuiet, pid=2880
I/ActivityManager(  906): Killing 2880:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/NetworkLogImpl( 2177): Loaded NetworkSpeedPredictor
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/iu.Environment( 2177): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
I/ActivityManager(  906): Recipient 2880
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/iu.UploadsManager( 2177): num queued entries: 0
I/iu.UploadsManager( 2177): num updated entries: 0
I/iu.SyncManager( 2177): NEXT; no task
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
D/NativeLibraryUtils( 3568): Install completed successfully. count=14 extracted=0
W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
I/WVCdm   (  371): CdmEngine::OpenSession
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1374/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/WearableService( 1223): callingUid 10029, callindPid: 1223
E/MDM     ( 1223): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 2177): Restart initialization of location
D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1374): Proximity feature is not enabled.
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3610 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
W/dalvikvm( 3568): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
W/GCoreFlp( 1223): No location to return for getLastLocation()
W/FusedLocationProvider( 1223): location=null
W/dalvikvm( 3568): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 3568): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/WVCdm   (  371): PrepareKeyRequest: nonce=1337339325
W/dalvikvm( 3568): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 3568): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/PMS     (  906): acquireWL(423c3910): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(423c3910): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
I/GoogleURLConnFactory( 3568): Using platform SSLCertificateSocketFactory
D/AlertReceiver( 3381): beginStartingService
D/PMS     (  906): acquireWL(426de8d0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3381 10013 null
D/WIFI_ICON( 1117): WifiActivity: 3
W/WeatherUtility( 3610): can't get weather sync account
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/libc    ( 3568): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3568): [NET] getaddrinfo-,err=8
D/libc    ( 3568): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3568): [NET] getaddrinfo-, 1
D/libc    ( 3568): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3629 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8793 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
I/WVCdm   (  371): CdmEngine::CloseSession
D/AlertService( 3381): start to updateAlertNotification!
D/AlertService( 3381): No fired or scheduled alerts
D/HtcAlertUtils( 3381): -- cancelReminderNotification --
W/WeatherRequest( 3610): request cur loc, but there is no sys cur
W/Settings( 3610): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HtcAlertUtils( 3381): broadcastExistReminder!
D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/AlertReceiver( 3381): stopSelfResult true
D/PMS     (  906): releaseWL(426de8d0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
W/WeatherUtility( 3610): can't get weather sync account
I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=86
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3568): [NET] getaddrinfo_proxy-, success
I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 1 9 17
W/WeatherRequest( 1117): request cur loc, but there is no sys cur
D/PMS     (  906): acquireWL(42788898): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3629 10071 null
D/PMS     (  906): acquireWL(42789108): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3629 10071 null
D/PMS     (  906): releaseWL(42788898): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3646 uid=10090 gids={50090, 3003, 5012, 1028}
D/TodoTaskshortcut( 3629): update TASK shortcut>
I/TodoTaskNotifyService( 3629): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/WorldClock.Global( 3646): isHtcDevice = true
W/WeatherRequest( 3610): request cur loc, but there is no sys cur
W/Settings( 3610): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/TodoTaskNotifyService( 3629): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/WorldClock.Global( 3646): isHtcDevice = true
I/WorldClock.AlarmUtils( 3646): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
W/ContextImpl( 3097): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  906): releaseWL(42789108): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/libc    ( 3568): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3568): [NET] getaddrinfo-,err=8
D/libc    ( 3568): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3568): [NET] getaddrinfo-,err=8
I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3661 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/NotifyReceiver( 3629): stopSelfResult true
I/WorldClock.AlarmUtils( 3646): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 3646): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1117): receive(android.intent.action.ALARM_CHANGED,1,false)
D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 1 89 17
D/Process (  906): killProcessQuiet, pid=3110
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/Process (  906): killProcessQuiet, pid=3302
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3110:com.android.settings/1000 (adj 15): empty #17
I/ActivityManager(  906): Killing 3302:com.htc.sense.browser/u0a12 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3110
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TimeService( 3661): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454983565131
D/Process (  906): killProcessQuiet, pid=3341
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3341:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/PMS     (  906): acquireWL(426ed2b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Recipient 3341
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(426ed2b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2177): Checkin interval check for package: unspecified last checkin: 1454981449522 min interval config: 0 actual interval: 2115648
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
D/PMS     (  906): acquireWL(426d3250): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2177 10029 null
D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/PMS     (  906): acquireWL(426ceef0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=10 [28][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
D/PMS     (  906): releaseWL(426d3250): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  906): releaseWL(426ceef0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Recipient 3302
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3678 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/DemoRecovery.RestoreReceiver( 3678): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3678): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3678): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42693588): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3629 10071 null
D/PMS     (  906): acquireWL(42689ac0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3629 10071 null
,D/TodoTaskshortcut( 3629): update TASK shortcut>
,I/TodoTaskNotifyService( 3629): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/PMS     (  906): releaseWL(42693588): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): releaseWL(42689ac0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3695 uid=10082 gids={50082, 3003, 5012}
W/NotifyReceiver( 3629): stopSelfResult true
,D/Process (  906): killProcessQuiet, pid=3353
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3353:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3353
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3707 uid=10082 gids={50082, 3003, 5012}
,I/FeedHostManager( 1270): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
,D/Process (  906): killProcessQuiet, pid=3403
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  906): killProcessQuiet, pid=3364
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3403:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/PMS     (  906): acquireWL(424657e0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1270 10076 null
D/PMS     (  906): releaseWL(424657e0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
I/ActivityManager(  906): Killing 3364:com.htc.sense.news/u0a76 (adj 15): empty #18
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3403
,I/ActivityManager(  906): Recipient 3364
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BroadcastQueue(  906): Schedule to resend BroadcastRecord{426c14c0 u0 com.htc.mms.DB_CHANGE callingPid=1244 callingUid=1001} for ResolveInfo{424896c8 com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent m=0x108000} of com.htc.widget.hmsproc1
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3719 uid=10041 gids={50041}
,D/SMSBackup( 3416): Got a database change event
,I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3732 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  906): killProcessQuiet, pid=3428
,I/ActivityManager(  906): Killing 3428:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,I/ImageRamCache( 3732): create image Cache, size: 31457280.
I/ImageRamCache( 3732): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3732): create image Cache, size: 12582912.
,I/FeedSettings( 3732): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3732): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3732): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3732): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3732): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3732): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3732): [custom highlight] onReceive
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3732): [custom highlight] onHandleIntent
D/NewsDB  ( 3732): set custom highlight []
,D/WVCdm   (  371): PrepareKeyRequest: nonce=672084343
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3428
D/MediaRouterService(  906): Client com.google.android.music (pid 3428): Died!
,D/CustomHighlightService( 3732): [custom highlight] set tags 
D/MessagingShortcutReceiver( 2152): keep hiding shortcut bubble
D/MessagingShortcut( 2152): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2152): After query: 0
D/MessagingShortcut( 2152): mPresentUnreadCount: -1
D/MessagingShortcut( 2152): setMsgShortcutDrawable> 0
I/ActivityManager(  906): Resuming delayed broadcast
D/MessagingShortcut( 2152): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1576): [EventService] reorderNotification, total:0
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/TodoTaskshortcut( 3629): update TASK shortcut>
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
D/HtcBroadcastReceiver( 1244): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/Process (  906): killProcessQuiet, pid=3450
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3450:com.facebook.katana/u0a27 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3750 uid=10091 gids={50091, 3003, 5012}
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3764 uid=10091 gids={50091, 3003, 5012}
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Recipient 3450
,D/MdScBoot( 3750): [6e8.1.] 40@-030556
,I/ActivityManager(  906): Resuming delayed broadcast
D/SMSBackup( 3416): Got a database change event
,D/Process (  906): killProcessQuiet, pid=3474
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  906): killProcessQuiet, pid=3490
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3474:com.google.android.setupwizard/u0a79 (adj 15): empty #17
I/ActivityManager(  906): Killing 3490:com.android.chrome/u0a96 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3474
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3490
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/MDM     ( 1223): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2177): Restart initialization of location
,D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1374): Proximity feature is not enabled.
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MtpReceiver( 2711): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2711): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2711): [MTP][handleMessage][startService]
,D/MtpReceiver( 2711): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2711): [MTP][handleMessage]-
W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3782 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/PMS     (  906): acquireWL(4255d0b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4255d0b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/MtpService( 2711): [MTP] startForeground
D/DotMatrix( 1576): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews( 1117): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1117): com.android.providers.media 1 0 10
I/RemoteViews( 1117): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1117): com.android.providers.media 1 1 15
,D/MtpService( 2711): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2711): TotalSize=1918604,MediaCacheLimit=6000
,D/MtpService( 2711): [isMtpConnected] connected: true
D/PMS     (  906): acquireWL(4264c420): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2177 10029 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
D/PMS     (  906): acquireWL(4267c670): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3556 10160 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/MessagingNotification( 2152): New incoming message, can't cancel notification now
,D/MessagingNotification( 2152): newMsgCnt: 0, false
,I/dalvikvm-heap( 3556): Grow heap (frag case) to 15.217MB for 1821008-byte allocation
,D/SyncApplication( 3782): Loading default preferences
,W/Resources( 3782): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/iu.UploadsManager( 2177): End new media; added: 0, uploading: 0, time: 91 ms
D/WifiService(  906): New client listening to asynchronous messages
D/PMS     (  906): releaseWL(4264c420): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/PMS     (  906): releaseWL(4267c670): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,D/SyncApplication( 3782): Overriding preferences with custom values
,D/SyncApplication( 3782): Updating preferences succeeded
,E/SyncApplication( 3782): Application created.
D/VolumeInfo( 3782): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3782): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3782): Found 0 mount point(s)
,V/VolumeInfo( 3782): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3782): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3782): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3782): Can not create volume ID for unmounted volume null
,I/Adreno-EGL( 3568): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3568): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3568): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3568): Local Branch: 
I/Adreno-EGL( 3568): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3568): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3568):                  aa63bbd948f41d15fc72f585e
,I/CalendarDefines( 3782): getNewCalendarAuthority()...
,D/SyncApplication( 3782): enableAppOperation()+
,D/SyncApplication( 3782): enableAppOperation()-
,D/HTCUtilities( 3782): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3782, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3782, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3782): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3782): isNeorSinged() return false
D/CDMountReceiver( 3782): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3782): USB connected to PC
,D/FOTAReceiver( 3782): onReceive() enter 
,D/FOTAReceiver( 3782): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/Process (  906): killProcessQuiet, pid=3508
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3810 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 3508:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/Adreno-EGL( 3568): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3568): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3568): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3568): Local Branch: 
I/Adreno-EGL( 3568): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3568): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3568):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  906): Recipient 3508
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3381
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3381:com.htc.calendar/u0a13 (adj 15): empty #17
,I/Adreno-EGL( 3568): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3568): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3568): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3568): Local Branch: 
I/Adreno-EGL( 3568): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3568): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3568):                  aa63bbd948f41d15fc72f585e
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3381
,D/HtcFingerPrintQuickLaunchProvider( 3810): -onCreate()
,V/Settings:HtcSettingsApplication( 3810): [3810/3810] onCreate()
,D/TetherSettings( 3810): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3810): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3810): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3810): Cust_ConnectToPC   : spcsc>false
D/        ( 3810): Cust_ConnectToPC   : IPT>true
,D/        ( 3810): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3810): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3810): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3810): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3810): Cust_ConnectToPC   : spcsc>false
D/        ( 3810): Cust_ConnectToPC   : IPT>true
D/        ( 3810): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3810): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3810): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3810): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3810): usb_cable_connect = 1
,D/SmartNS_Utility( 3810): usb_denied = 0
I/SmartNS_NSReceiver( 3810): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3810): USB = true hasTethered = false isNSOpening: false
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3568/10029)
,I/PSReceiver( 3810): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3810): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/SmartNS_PSService( 3810): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3810):  defaultType:0
I/SmartNS_PSService( 3810): fail notificaiton:false
D/SmartNS_Utility( 3810): usb_cable_connect = 1
D/SmartNS_Utility( 3810): usb_denied = 0
I/SmartNS_PSService( 3810): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  906): bSetPropertyMultiRAB:false
I/ActivityManager(  906): Resuming delayed broadcast
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3810/1000)
,D/SmartNS_Utility( 3810): usb_cable_connect = 1
D/SmartNS_Utility( 3810): usb_denied = 0
I/SmartNS_PSService( 3810): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/DotMatrix( 1576): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,V/Tethering(  906): bSetPropertyMultiRAB:false
W/WeatherUtility( 3610): can't get weather sync account
,I/RemoteViews( 1117): com.android.settings (true,33751552),
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3810/1000)
I/RemoteViews.Performance( 1117): com.android.settings 2 1 10
D/SmartNS_Utility( 3810): usb_cable_connect = 1
D/SmartNS_Utility( 3810): usb_denied = 0
D/DotMatrix( 1576): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3810): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3810): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  906): Resuming delayed broadcast
,I/RemoteViews( 1117): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1117): com.android.settings 1 0 10
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1270): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1270): com.google.android.googlequicksearchbox 2 0 5
,D/PMS     (  906): acquireWL(42542710): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1500 10014 null
W/WeatherRequest( 3610): request cur loc, but there is no sys cur
,W/Settings( 3610): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 1 7 17
D/PMS     (  906): releaseWL(42542710): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(426173b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=3828 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(426173b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425decc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3828 1000 null
,W/ContextImpl( 3828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3828): call getInstance()
I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3828): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/Settings( 3568): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2177): Classify the device as Phone.
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2177): [NET] getaddrinfo-,err=8
,D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2177): [NET] getaddrinfo-, 1
,D/libc    ( 2177): [NET] getaddrinfo_proxy+
,W/BatSI   (  906): Couldn't get kernel wake lock stats
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =142e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2177): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2177): [NET] getaddrinfo-,err=8
,D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2177): [NET] getaddrinfo-,err=8
D/libc    ( 2177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2177): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2177): Sending checkin request (12253 bytes)
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3646
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/WeatherUtility( 1117): can't get weather sync account
,I/ActivityManager(  906): Killing 3646:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/WeatherUtility( 1315): Weather sync is On
,D/WSP     ( 1315): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3646
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3849 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/WeatherUtility( 3610): can't get weather sync account
,W/WeatherRequest( 3610): request cur loc, but there is no sys cur
,W/Settings( 3610): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 0 5 17
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=6 [15][1][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 7 times.
,I/SensorManager(  906): mEventCount = 450
,D/PMS     (  906): releaseWL(424e47a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3867 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3097
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3097:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3097
,I/MusicStore( 3867): Database version: 95
,W/ContextImpl( 3867): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3867): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3867): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3867): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 2177): Checkin reason type: 8 attempt count: 1
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2177): Failed to find provider info for com.google.android.wearable.settings
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3867): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3867, uid=10154, userID:0
,D/PMS     (  906): releaseWL(425decc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 3867): Registered
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
I/MediaRouter( 3867): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/NetworkMonitor( 3867): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (3867/10154)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0],
V/AlarmManager(  906): sending alarm PendingIntent{422d1c90: PendingIntentRecord{426fed28 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1454983567727, Int=0
,D/MediaRouter( 3867): getSelectedRoute
,I/NetworkMonitor( 3867): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3867/10154)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/TelephonyReceiver( 1244): bind: true
,D/Process (  906): killProcessQuiet, pid=3661
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3867, uid=10154, userID:0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(426a9cb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3661:com.qualcomm.timeservice/1000 (adj 15): empty #17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/DFPI.PIReciver( 3678): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/GenericMessagesProvider( 2152): query uri: content://htc-messages/wappush/count
D/PMS     (  906): releaseWL(426a9cb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
E/SQLiteLog( 2152): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 2152): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2152): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 2152): DB info: errno = 2, errno message = No such file or directory
I/DFPI.ApkInstallService( 3678): onHandleIntent
,I/DFPI.ApkInstallService( 3678): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3678): check CID = HTC__032
,I/DFPI.ApkInstallService( 3678): There is no Demo.apk in sd card or phone storage
,E/SQLiteDatabase( 2152): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2152): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2152): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2152): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2152): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2152): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2152): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2152): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2152): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2152): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2152): 	at android.content.ContentProvider.query(ContentProvider.java:869)
,W/System.err( 2152): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2152): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2152): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2152): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  906): Recipient 3661
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Resuming delayed broadcast
D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2177/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,I/CheckinRequestBuilder( 2177): Classify the device as Phone.
,I/CheckinTask( 2177): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2177): Checking schedule, now: 1454983567858 next: 1455506504856
,I/CheckinService( 2177): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/ActivityManager(  906): Resuming delayed broadcast
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,D/CheckinService( 2177): Recording last checkin time for package unspecified as 1454983567876
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3893 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
D/PMS     (  906): releaseWL(42761b80): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3893/10053)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3893/10053)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{426fb358 u0 ReceiverList{426fb2f8 3893 com.htc.musicenhancer/10053/u0 remote:426fb000}}
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3893): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3695
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3911 uid=10081 gids={50081, 5001, 1028, 1015}
I/ActivityManager(  906): Killing 3695:com.htc.stock/u0a82 (adj 15): empty #17
,I/SoundPicker( 3911): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3911): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3911): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3911): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3911): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3911): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3911): MODE_GSM access default DB
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3,
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3911): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_gsm),
D/RingtoneManager( 3911): MODE_GSM access default DB
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/ActivityManager(  906): Recipient 3695
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/ActivityManager(  906): Resuming delayed broadcast
,D/DFPI.PIReciver( 3678): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3678): onHandleIntent
,I/DFPI.ApkInstallService( 3678): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3678): check CID = HTC__032
,I/DFPI.ApkInstallService( 3678): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/Prism.ItemManager( 3732): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3732): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/dalvikvm-heap( 1270): Grow heap (frag case) to 13.197MB for 53840-byte allocation
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/PackageManager(  906): Unable to load service info ResolveInfo{4281c4c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  906): applying state to connected service
,D/AutoSetting( 1315): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/LocationProviderProxy(  906): applying state to connected service
D/AutoSetting( 1315): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1315): service - requestNLP() NetworkLocationProvider not enabled
D/PMS     (  906): acquireWL(42877068): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42877068): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(428787e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(428787e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4287a038): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4287a038): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4287b4f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4287b4f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3707
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3707:com.htc.stock:remote/u0a82 (adj 15): empty #17
I/SoundPicker( 3911): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3911): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/ActivityManager(  906): Recipient 3707
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3911): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3911): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3911): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3911): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3911): MODE_GSM access default DB
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3911): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3911): MODE_GSM access default DB
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=c,ontent://media/internal/audio/media/244 type=8
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/Prism.ItemManager( 3732): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3732): loadItems() com.htc.launcher.pageview.WidgetManager@41badcc0 +
,I/Prism.WidgetManager( 3732): onLoadItems() +
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41bcbe50 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4288e208): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1500 10014 null
,I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(4288e208): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3935 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3678): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3678): onHandleIntent
,I/DFPI.ApkInstallService( 3678): Media Scan Finished Case 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3678): check CID = HTC__032
,I/DFPI.ApkInstallService( 3678): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
,I/EASAppSvc( 3935): [ NA ]- onCreate()
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3935): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3629): put()
,I/EASAppSvc( 3935): [ NA ]- onDestroy()
,I/EASAppSvc( 3935): [ NA ]> uninitEASService
,E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41bcbe50 -
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3935/10064)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3935/10064)
,D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3935/10064)
,I/Prism.WidgetManager( 3732): onLoadItems() -
,I/Prism.ItemManager( 3732): loadItems() com.htc.launcher.pageview.WidgetManager@41badcc0 -
,I/EASRequestController( 3935): [ NA ]release
,I/EASAppSvc( 3935): [ NA ]< uninitEASService
,I/EASAppSvc( 3935): [ NA ]- onCreate()
,I/EASAppSvc( 3935): [ NA ]> onUpgrade: version = 63
,D/Process (  906): killProcessQuiet, pid=3732
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3935/10064)
I/ActivityManager(  906): Killing 3732:com.htc.sense.news/u0a76 (adj 15): empty #17
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3935/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3935/10064)
,D/ORMLib  ( 3629): put()
,I/EASAppSvc( 3935): [ NA ]- onDestroy()
,I/EASAppSvc( 3935): [ NA ]> uninitEASService
,I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3967 uid=10068 gids={50068, 3003, 5012}
D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
I/EASRequestController( 3935): [ NA ]release
D/PhoneApp( 1244): -- N1 =0
D/PhoneApp( 1244): -- N2 =0
D/PhoneApp( 1244): -- N3 =0
I/EASAppSvc( 3935): [ NA ]< uninitEASService
,I/ActivityManager(  906): Recipient 3732
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3750
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3750:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3750
,D/ORMLib  ( 3629): put()
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 8 times.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3764
,I/ActivityManager(  906): Killing 3764:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3911): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3911): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3911): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3911): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3911): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3911): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3911): MODE_GSM access default DB
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3911): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3911): MODE_GSM access default DB
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  906): Recipient 3764
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3867): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/TelephonyReceiver( 1244): bind: false
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(4249fcb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4249fcb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=74 rxSum=80} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20942 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20943 delay=15s
,D/DFPI.PIReciver( 3678): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3678): onHandleIntent
I/DFPI.ApkInstallService( 3678): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3678): check CID = HTC__032
,I/DFPI.ApkInstallService( 3678): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/PMS     (  906): acquireWL(424ddbe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424ddbe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,V/AlarmManager(  906): sending alarm PendingIntent{4254f918: PendingIntentRecord{4266ffe8 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454983573952, Int=0
,I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 3911): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3911): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3911): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3911): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3911): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3911): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3911): MODE_GSM access default DB
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3911): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3911): MODE_GSM access default DB
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3911): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3911): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3911): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3911): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac,
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3867): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3998 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{426d6478 u0 com.google.android.gms/.gcm.GcmService}
,D/Process (  906): killProcessQuiet, pid=3719
,I/ActivityManager(  906): Killing 3719:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Recipient 3719
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/[PluginManager]RegisterService( 1315): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
I/[PluginManager]RegisterService( 1315): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2810): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(425c2918): PARTIAL_WAKE_LOCK  AsyncService 0x1 3556 10160 null
,I/ActivityManager(  906): Delaying start of: ServiceRecord{424a1d50 u0 com.htc.updater/.service.UpdaterCheckIntranetService}
,D/PMS     (  906): releaseWL(425c2918): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/IcingCorporaProvider( 2810): UpdateCorporaTask done [took 48 ms] updated apps [took 48 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4019 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Settings:HtcWirelessFeatureFlags( 3810): id/is att sku: 99/false
,W/dalvikvm( 4019): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/SystemReader( 3810): Cannot find devicepolicy_lower_fp_quality, use default value instead
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4019, uid=10074, userID:0
,W/SystemReader( 3810): Cannot find support_harman, use default value instead
,W/SystemReader( 3810): Cannot find effect_manager_id, use default value instead
,D/Finsky  ( 4019): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/Settings:HtcWrapHeaderInfo( 3810): no such activity!
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4019/10074)
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3810): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3810): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3810): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]support         :false
,W/FingerprintManager( 3810): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3810): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3810): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4019): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4019): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/DotMatrix( 1576): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1117): com.htc.updater (true,33751552)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4019/10074)
,D/NotificationService(  906): notification sound not played, stream=5 volume=0 always=false
D/Finsky  ( 4019): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 4019): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ef3600 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1117): com.htc.updater 2 8 0 10
W/Settings( 4019): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4019): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/RemoteViews( 1117): com.htc.updater (true,33751552)
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c86010 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1117): com.htc.updater 1 6 1 10
W/dalvikvm( 4019): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4019): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4019): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4019): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4019, uid=10074, userID:0
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3810): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3810): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3810): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3810): [supportHomeButton]support         :false
,W/FingerprintManager( 3810): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3810): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3810): Failed to find provider info for com.htc.vowifi
,D/Ads     ( 4019): Skipping gmscore version check
,D/Finsky  ( 4019): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4019): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4019): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4019): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4019): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  906): killProcessQuiet, pid=3416
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3416:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4062 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/PMS     (  906): acquireWL(4248b750): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4248b750): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424e07a8): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Recipient 3416
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GAV2    ( 4062): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 2177): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2177): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,W/dalvikvm( 2177): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
W/dalvikvm( 2177): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2177): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2177): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2177): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2177): cleanUpNonGplusAccounts done.
,D/Process (  906): killProcessQuiet, pid=3782
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3782:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Recipient 3782
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4089 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Gmail   ( 4062): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4062): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4062): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4062): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/dalvikvm( 4089): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4089): VFY: unable to resolve instance field 36
,W/dalvikvm( 4089): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Babel   ( 4089): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4089): MmsConfig.loadMmsSettings
,V/JNIHelp ( 4089): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2152): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2152): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4089): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4089): MmsConfig.loadFromDatabase
,E/Babel   ( 4089): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4089): MmsConfig.loadFromResources
,E/Babel   ( 4089): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4089): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4089, uid=10111, userID:0
,W/Settings( 4089): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4089, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4089, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4089, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4089, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4089, uid=10111, userID:0
D/PMS     (  906): acquireWL(4271d250): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4089 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4089): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  906): releaseWL(4271d250): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(426cdb20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4089 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): releaseWL(426cdb20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(42669f48): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4089 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): releaseWL(42669f48): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3828
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3828:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/PMS     (  906): acquireWL(4241ed48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Recipient 3828
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
D/PMS     (  906): releaseWL(4241ed48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(41e74060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(41e74060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  906): acquireWL(42048d70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42048d70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
D/PMS     (  906): acquireWL(42600ad8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(42600ad8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  906): acquireWL(42702d40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42702d40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426e7b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(426e7b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(426c7c70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(426c7c70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,V/AlarmManager(  906): sending alarm PendingIntent{4258d030: PendingIntentRecord{4255be00 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454983575773, Int=0
,D/PMS     (  906): acquireWL(42675120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
V/AlarmManager(  906): sending alarm PendingIntent{4260f3d0: PendingIntentRecord{424664e8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454983575800, Int=0
D/PMS     (  906): releaseWL(42675120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4267b9d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4140 uid=10041 gids={50041}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,I/iu.UploadsManager( 2177): End new media; added: 0, uploading: 0, time: 78 ms
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4267b9d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426b9e80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/Process (  906): killProcessQuiet, pid=3610
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3610:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42791c98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(426b9e80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(42791c98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,D/LocationInitializer( 2177): Restart initialization of location
,D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1374): Proximity feature is not enabled.
,E/MDM     ( 1223): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
,I/Icing   ( 2177): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
D/PMS     (  906): acquireWL(42724fd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42724fd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
I/ActivityManager(  906): Resuming delayed broadcast
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,I/Icing   ( 2177): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
I/ActivityManager(  906): Recipient 3610
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(424e07a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42810e58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3629 10071 null
E/TodoTaskNotifyService( 3629): java.lang.NullPointerException
,W/System.err( 3629): java.lang.NullPointerException
W/System.err( 3629): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3629): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3629): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3629): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3629): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): acquireWL(42893a78): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3629 10071 null
D/PMS     (  906): acquireWL(42818e08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3629 10071 null
D/PMS     (  906): releaseWL(42810e58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): acquireWL(42893a78): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3629 10071 null
D/PMS     (  906): acquireWL(42848978): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3629 10071 null
D/PMS     (  906): releaseWL(42818e08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  906): releaseWL(42893a78): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 3629): stopSelfResult false
E/TodoTaskNotifyService( 3629): java.lang.NullPointerException
W/System.err( 3629): java.lang.NullPointerException
W/System.err( 3629): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3629): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3629): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3629): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3629): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 3629): stopSelfResult false
E/TodoTaskNotifyService( 3629): java.lang.NullPointerException
,W/System.err( 3629): java.lang.NullPointerException
W/System.err( 3629): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3629): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3629): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3629): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3629): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 3629): mStartingService is null
,W/NotifyReceiver( 3629): stopSelfResult true
D/PMS     (  906): acquireWL(426fe948): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3629 10071 null
D/PMS     (  906): releaseWL(426fe948): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/PMS     (  906): releaseWL(42848978): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/WSP     ( 1315): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
D/WeatherUtility( 1315): Weather sync is On
,I/WSP     ( 1315): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 09 04:06:15 CET 2016
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055)
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): acquireWL(42682f58): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1315 10055 null
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/MediaManager( 3849): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(4286b738): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4089 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(4286b738): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1315): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1315): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/IcingCorporaProvider( 2810): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  906): acquireWL(428307f0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428307f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4282fc80): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4282fc80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428250f0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428250f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42792b00): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42792b00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42776738): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42776738): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4276f558): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4276f558): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4274a818): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4274a818): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42737f10): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42737f10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2810): UpdateCorporaTask done [took 244 ms] updated apps [took 244 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(4271d250): PARTIAL_WAKE_LOCK  AsyncService 0x1 3556 10160 null
,D/PMS     (  906): releaseWL(4271d250): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2177): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/PMS     (  906): acquireWL(42700b58): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2177): updateResources: need to parse f{com.google.android.gms}
,W/MediaManager( 3849): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3629): update TASK shortcut>
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 9 times.
,I/SensorManager(  906): mEventCount = 600
,I/Icing   ( 2177): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2177): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2177): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(42700b58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:116, mTXpacketCount:64, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/CheckinService( 2177): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/GAV2    ( 4062): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV4    ( 4089): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/CalendarProvider2( 1500): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1500): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3849): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4264c768): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3867 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3867): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3867, uid=10154, userID:0
,W/ContextImpl( 3867): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/MusicLeanback( 3867): Conditions not met for autocaching.
,I/MusicLeanback( 3867): Stop autocaching.
D/PMS     (  906): releaseWL(4264c768): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4193 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4193): Loading default preferences
,W/Resources( 4193): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 4193): Overriding preferences with custom values
,D/SyncApplication( 4193): Updating preferences succeeded
,E/SyncApplication( 4193): Application created.
D/VolumeInfo( 4193): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4193): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4193): Found 0 mount point(s)
,V/VolumeInfo( 4193): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4193): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 4193): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4193): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 4193): getNewCalendarAuthority()...
,D/SyncApplication( 4193): enableAppOperation()+
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4193, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4193, uid=10008, userID:0
,W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4193): enableAppOperation()-
D/HTCUtilities( 4193): isNeorSinged() + 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 10 times.
,D/HTCUtilities( 4193): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4193): isNeorSinged() return false
,D/CDMountReceiver( 4193): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4193): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1576): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
,D/CDMountReceiver( 4193): enable CD Auto-mount: true
,I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/HTCUtilities( 4193): enable auto-mount
D/HTCUtilities( 4193): enable auto-mount
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f24b38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 3 16 6 11
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(426e6908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cc8200 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 9 2 16
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/MediaManager( 3849): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3935
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3935:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3935
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): acquireWL(428307f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(428307f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(4278a8c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4278a8c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424d3cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4216 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(424d3cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/CalendarApplication( 4216): onCreate
D/ProviderChangeReceiver( 4216): ---------------------------------------------------
,D/ProviderChangeReceiver( 4216): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4216): start to updateAlertNotification!
,D/Process (  906): killProcessQuiet, pid=3568
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4230 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 3568:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/AlertService( 4216): No fired or scheduled alerts
,D/HtcAlertUtils( 4216): -- cancelReminderNotification --
,D/HtcAlertUtils( 4216): broadcastExistReminder!
,D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4230): [4230/4230] onCreate()
W/ContextImpl( 4230): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Recipient 3568
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3967
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 3967:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3967
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42738280 u0 com.htc.musicenhancer/.EnhancerService}
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  906): releaseWL(42682f58): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 11 times.
,I/SensorManager(  906): mEventCount = 750
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=76 rxSum=81} preTxRxSum={txSum=74 rxSum=80}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20943 Sent 0 pkts since last received, < watchdogTrigger=5
D/PMS     (  906): acquireWL(423c40a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42077fb0: PendingIntentRecord{42632b10 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=86925, Int=0
,D/PMS     (  906): releaseWL(423c40a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20944 delay=15s
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(41c1aa28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
D/Finsky  ( 4019): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4019): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  906): sending alarm PendingIntent{42351070: PendingIntentRecord{426f1150 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454983588886, Int=0
D/PMS     (  906): releaseWL(41c1aa28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4019/10074)
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4019): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4019): [NET] getaddrinfo-,err=8
D/libc    ( 4019): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4019): [NET] getaddrinfo-, 1
D/libc    ( 4019): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =eba2 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4019): [NET] getaddrinfo_proxy-, success
,I/global  ( 4019): call createSocket() return a new socket.
D/libc    ( 4019): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4019): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4019): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4019): [NET] getaddrinfo-,err=8
D/WIFI_ICON( 1117): WifiActivity: 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4019): untagSocket(69) failed with errno -22
,D/Finsky  ( 4019): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4019): untagSocket(69) failed with errno -22
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4019): untagSocket(69) failed with errno -22
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4019/10074)
,D/Finsky  ( 4019): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  906): acquireWL(428185b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{424dfb98: PendingIntentRecord{424ffdb0 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454983591055, Int=0
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,D/Finsky  ( 4019): [428] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/PMS     (  906): acquireWL(427432b0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4019 10074 null
,D/PMS     (  906): releaseWL(428185b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/DeviceConnectionService( 1223): client connected with version: 8296000
,D/Finsky  ( 4019): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4019): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4019): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4019): [NET] getaddrinfo-,err=8
D/libc    ( 4019): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4019): [NET] getaddrinfo-, 1
,D/libc    ( 4019): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9cdf +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4019): [NET] getaddrinfo_proxy-, success,
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=5 [72][4][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): releaseWL(427432b0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 12 times.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1315): service - has update message, not stop
,D/AutoSetting( 1315): service - mHandler: update timezone
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1500): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1500): service - mHandler: update timezone
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1500): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1500): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1576): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1576): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f62ff8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 1 8 3 11
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:196, mTXpacketCount:116, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1500): Don't start project servcice
,D/HtcModeClient( 1500): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1500): connectState: CONNECTION_READY = false
D/SilentMusic( 1500): call stop
D/HtcModeClient( 1500): close connection
W/HtcModeClient( 1500): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1500): read the terminate packet, so break
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 900
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4258 uid=10078 gids={50078}
,D/PMS     (  906): acquireWL(42821a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10078}
,V/AlarmManager(  906): sending alarm PendingIntent{424671f0: PendingIntentRecord{423d5268 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454983600793, Int=60000
,D/PMS     (  906): releaseWL(42821a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4258): SMSBackupAgentService started
,D/SMSBackup( 4258): Checking restore status
,D/SMSBackup( 4258): Restore complete
,D/SMSBackup( 4258): cancelCheckAlarm
,D/SMSBackup( 4258): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3678
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
I/ActivityManager(  906): Killing 3678:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3678
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=148 rxSum=146} preTxRxSum={txSum=76 rxSum=81}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20944 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20945 delay=15s
D/PMS     (  906): acquireWL(426f7548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4208e630: PendingIntentRecord{42632b10 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=101930, Int=0
D/PMS     (  906): releaseWL(426f7548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): acquireWL(4270e5f0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4270e5f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42845580): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42845580): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42767038): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42767038): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4271d0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{427133e0: PendingIntentRecord{427133a8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454983605343, Int=0
,D/PMS     (  906): releaseWL(4271d0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4019): [419] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4019): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4238de50 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:196, mTXpacketCount:196, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB,
,V/LightsService(  906): setLight #0: color=#26
,V/LightsService(  906): setLight #0: color=#22
,V/LightsService(  906): setLight #0: color=#1c
,V/LightsService(  906): setLight #0: color=#15
,V/LightsService(  906): setLight #0: color=#14
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4219ae90
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4219ae90, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42085630
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42496470
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 343ms
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1256): ScreenObserver: OFF
D/NfcService( 1256): applyRouting - 0
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@423c8910)
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=1270
D/PMN     (  906): wakingUp
,D/NfcService( 1256): applyRouting -2
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMS     (  906): acquireWL(42886d08): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  906): releaseWL(42886d08): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  906): acquireWL(42888368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  906): onScreenOn
I/BatteryService(  906): n_update end
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20946 delay=15s
,D/MtpService( 2711): [MTP][onReceive]+android.intent.action.USER_PRESENT
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): releaseWL(42888368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/MtpService( 2711): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting - 0
,D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/NfcService( 1256): applyRouting -2
D/PMS     (  906): acquireWL(4286c8e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4286c8e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ClockThread( 1117): stop update clock
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): SET_SCREEN_ON:On
I/wpa_supplicant( 1137): htc_wext_set_keepalive +
I/wpa_supplicant( 1137): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1137): getPrivFuncNum +	
I/wpa_supplicant( 1137): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1137): BG scan when screen On
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1137): wpa_supplicant_scan enter
I/wpa_supplicant( 1137): Match BG scan, scan!
,I/wpa_supplicant( 1137): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1137): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1137): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1137): nl80211: Event message available
D/WifiNative-wlan0(  906):    returned true
D/wpa_supplicant( 1137): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0,
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4279 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
,V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  906): updateScreenOn: false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(42807158): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42807158): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42808640): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOn: 1454983617959
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOn: 1454983617959
D/PMS     (  906): releaseWL(42808640): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4280a5c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4279 1000 null
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42085630
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42085630, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42496470
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4279): isEpsOn(), nState = 0
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(4280c2b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
,I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c811c0
I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20946 mDataStallAlarmIntent=PendingIntent{42528d40: PendingIntentRecord{42632b10 android broadcastIntent}}
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/PMS     (  906): acquireWL(427e1f80): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(4280c2b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 4279): getMobilePolicyEnabled, result = true
,D/Process (  906): killProcessQuiet, pid=3911
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3911:com.htc.sdm/u0a81 (adj 15): empty #17
,D/PMS     (  906): releaseWL(4280a5c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3911
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): SET_SCREEN_ON:Off
I/wpa_supplicant( 1137): htc_wext_set_keepalive +
I/wpa_supplicant( 1137): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1137): getPrivFuncNum +	
I/wpa_supplicant( 1137): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1137): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1137): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1137): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1315): receiver - intent: android.intent.action.USER_PRESENT
V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/TetherSettings( 3810): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3810): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3810): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3810): Cust_ConnectToPC   : spcsc>false
D/        ( 3810): Cust_ConnectToPC   : IPT>true
D/        ( 3810): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3810): hasRemovableStorageSlot: true
,D/AutoSetting( 1315): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/SmartNS_Utility( 3810): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3810): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1244): start background delete task...
,I/PSReceiver( 3810): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 3810): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1244): size: 0 , 0
D/ContactMessageStore( 1244): Background delete complete
,I/SmartNS_PSService( 3810): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3810):  defaultType:0
,I/PhoneStatusBar( 1117): removeHeadsNotification.gc: 53
,W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3810): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3810): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3810): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3810): Cust_ConnectToPC   : spcsc>false
D/        ( 3810): Cust_ConnectToPC   : IPT>true
D/        ( 3810): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3810): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3810): Index of the first 1 = -1
,D/AutoSetting( 1315): service - mHandler: cancel location update
,D/AutoSetting( 1315): service -           changes count: 0
W/Settings( 3810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3810): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3810): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3810): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3810): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3810): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 3810): [ACC]android_networking:tethering_guard_support=false
,D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1576): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  906): acquireWL(427f9258): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427f9258): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427f8f68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4279): isEpsOn(), nState = 0
D/SmartSyncUtils( 4279): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4279): getMobilePolicyEnabled, result = true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOff
D/PMS     (  906): releaseWL(427f8f68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/WifiService(  906): New client listening to asynchronous messages
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42496470
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42496470, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42496470, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42496470
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42512b18 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42512b18 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(427e1f80): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/PMS     (  906): acquireWL(42750f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1137): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1137): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1137): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1137): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1137): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1137): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): Selecting BSS from priority group 1
I/wpa_supplicant( 1137): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1137): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1137): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1137): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1137):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1137):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1137): Start print parameters
I/wpa_supplicant( 1137): wpa_s->wpa_state is 9
I/wpa_supplicant( 1137): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1137): isConcurrentMode() is 0
I/wpa_supplicant( 1137): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1137): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1137): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1137): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1137): wpa_s->reassociate is 0
I/wpa_supplicant( 1137): wpa_s->is_screen_on 0
I/wpa_supplicant( 1137): wpa_s->ifname wlan0
I/wpa_supplicant( 1137): End print parameters
I/wpa_supplicant( 1137): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1137): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/wpa_supplicant( 1137): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1137): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1137): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomn,ess: count=9 entropy=3
D/wpa_supplicant( 1137): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1137): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1137): State: DISCONNECTED -> INACTIVE
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=118769, Int=0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@41d17730 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@41d17730 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@41d17730 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1137): reply (376) for get BSS: id=0
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1137): freq=5220
I/wpa_supplicant( 1137): level=-50
I/wpa_supplicant( 1137): tsf=0000000118776845
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG7005g
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=1
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-58
I/wpa_supplicant( 1137): tsf=0000000118776872
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG700
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=2
I/wpa_supplicant( 1137): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-79
I/wpa_supplicant( 1137): tsf=0000000118776883
I/wpa_supplicant( 1137): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1137): ssid=Gonzos
I/wpa_supplicant( 1137): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 118776845, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 118776872, distance: ?(cm), distanceSd: ?(cm)
D/PMS     (  906): releaseWL(42750f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 118776883, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/AutoSetting( 1500): service - handleMessage() stop self
,D/AutoSetting( 1500): service - onDestroy() END
,D/AutoSetting( 1500): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=3998
,I/ActivityManager(  906): Killing 3998:com.htc.updater/u0a85 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3998
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  906): killProcessQuiet, pid=3893
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3893:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3893
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(425b9838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425b9838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1137): wpa_supplicant_scan enter
I/wpa_supplicant( 1137): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1137): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1137): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1137): nl80211: Event message available
,D/wpa_supplicant( 1137): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1137): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1137): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1137): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1137): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1137): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1137): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1137): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): Selecting BSS from priority group 1
I/wpa_supplicant( 1137): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1137): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1137): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1137): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1137): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1137):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1137):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1137): Start print parameters
I/wpa_supplicant( 1137): wpa_s->wpa_state is 9
I/wpa_supplicant( 1137): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1137): isConcurrentMode() is 0
I/wpa_supplicant( 1137): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1137): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1137): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1137): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1137): wpa_s->reassociate is 0
I/wpa_supplicant( 1137): wpa_s->is_screen_on 0
I/wpa_supplicant( 1137): wpa_s->ifname wlan0
I/wpa_supplicant( 1137): End print parameters
I/wpa_supplicant( 1137): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1137): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1137): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1137): BSS: last_scan_res_used=4/32 la,st_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1137): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1137): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1137): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1137): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1137): reply (489) for get BSS: id=0
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1137): freq=5220
I/wpa_supplicant( 1137): level=-50
I/wpa_supplicant( 1137): tsf=0000000136174982
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG7005g
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=1
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-58
I/wpa_supplicant( 1137): tsf=0000000136175020
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG700
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=2
I/wpa_supplicant( 1137): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-78
I/wpa_supplicant( 1137): tsf=0000000136175030
I/wpa_supplicant( 1137): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1137): ssid=Gonzos
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=3,
I/wpa_supplicant( 1137): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-56
I/wpa_supplicant( 1137): tsf=0000000136175008
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1137): ssid=01ABC
I/wpa_supplicant( 1137): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 136174982, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 136175020, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 136175030, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 136175008, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42633e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{423e96c0: PendingIntentRecord{426cf918 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=134508, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42575ac0: PendingIntentRecord{4254a190 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142466, Int=0
,D/PMS     (  906): acquireWL(4245a1e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42166118: PendingIntentRecord{4270b180 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=147536, Int=0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,D/AutoSetting( 1315): service - handleMessage() stop self
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1315): service - handleMessage() quit looper
,D/AutoSetting( 1315): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=2152
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): acquireWL(4209ce48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Killing 2152:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/PMS     (  906): releaseWL(4209ce48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4245a1e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42388110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(42388110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426a76e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Recipient 2152
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42682ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42743158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1454983649010 tag=VacuumService
D/PMS     (  906): releaseWL(426a76e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42682ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(4266b220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42744b58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
D/PMS     (  906): releaseWL(42743158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4266b220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/PMS     (  906): acquireWL(4283ca68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,D/PMS     (  906): releaseWL(42633e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =cb76 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(4283ca68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424c9390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(424c9390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 10
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1137): wpa_supplicant_scan enter
I/wpa_supplicant( 1137): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1137): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1137): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1137): nl80211: Event message available
,D/wpa_supplicant( 1137): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): releaseWL(42744b58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1137): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1137): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1137): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1137): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1137): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1137): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1137): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): Selecting BSS from priority group 1
I/wpa_supplicant( 1137): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1137): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1137): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1137): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1137): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1137):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1137):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1137): Start print parameters
I/wpa_supplicant( 1137): wpa_s->wpa_state is 9
I/wpa_supplicant( 1137): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1137): isConcurrentMode() is 0
I/wpa_supplicant( 1137): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1137): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1137): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1137): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1137): wpa_s->reassociate is 0
I/wpa_supplicant( 1137): wpa_s->is_screen_on 0
I/wpa_supplicant( 1137): wpa_s->ifname wlan0
I/wpa_supplicant( 1137): End print parameters
I/wpa_supplicant( 1137): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1137): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1137): p2p0: Updating scan results from sibling
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=241,2 level=-57
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1137): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1137): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1137): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1137): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1137): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1137): reply (489) for get BSS: id=0
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1137): freq=5220
I/wpa_supplicant( 1137): level=-50
I/wpa_supplicant( 1137): tsf=0000000153292080
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG7005g
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=1
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-57
I/wpa_supplicant( 1137): tsf=0000000153292116
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG700
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=2
I/wpa_supplicant( 1137): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-78
I/wpa_supplicant( 1137): tsf=0000000153292125
I/wpa_supplicant( 1137): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1137): ssid=Gonzos
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=3
I/wpa_supplicant( 1137): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-56
I/wpa_supplicant( 1137): tsf=0000000153292105
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1137): ssid=01ABC
I/wpa_supplicant( 1137): ####
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 153292080, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 153292116, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 153292125, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 153292105, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42770968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42770968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1137): wpa_supplicant_scan enter
I/wpa_supplicant( 1137): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1137): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1137): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1137): nl80211: Event message available
,D/wpa_supplicant( 1137): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1137): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1137): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1137): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1137): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1137): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1137): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1137): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): Selecting BSS from priority group 1
I/wpa_supplicant( 1137): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1137): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1137): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1137): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1137): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1137):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1137):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1137): Start print parameters
I/wpa_supplicant( 1137): wpa_s->wpa_state is 9
I/wpa_supplicant( 1137): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1137): isConcurrentMode() is 0
I/wpa_supplicant( 1137): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1137): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1137): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1137): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1137): wpa_s->reassociate is 0
I/wpa_supplicant( 1137): wpa_s->is_screen_on 0
I/wpa_supplicant( 1137): wpa_s->ifname wlan0
I/wpa_supplicant( 1137): End print parameters
I/wpa_supplicant( 1137): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1137): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1137): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1137): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1137): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1137): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1137): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1137): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1137): reply (489) for get BSS: id=0
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1137): freq=5220
I/wpa_supplicant( 1137): level=-50
I/wpa_supplicant( 1137): tsf=0000000170482807
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG7005g
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=1
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-57
I/wpa_supplicant( 1137): tsf=0000000170482844
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG700
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=2
I/wpa_supplicant( 1137): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-78
I/wpa_supplicant( 1137): tsf=0000000170482854
I/wpa_supplicant( 1137): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1137): ssid=Gonzos
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=3
I/wpa_supplicant( 1137): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-56
I/wpa_supplicant( 1137): tsf=0000000170482833
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1137): ssid=01ABC
I/wpa_supplicant( 1137): ####
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 170482807, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 170482844, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 170482854, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 170482833, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1,
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4280c5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=178769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4280c5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42883630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{4272b800: PendingIntentRecord{424c0e30 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=183043, Int=0
,D/PMS     (  906): releaseWL(42883630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1137): wpa_supplicant_scan enter
I/wpa_supplicant( 1137): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1137): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1137): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1137): nl80211: Event message available
,D/wpa_supplicant( 1137): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1137): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1137): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1137): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1137): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1137): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1137): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): Selecting BSS from priority group 1
I/wpa_supplicant( 1137): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1137): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1137): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1137): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1137):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1137):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1137): Start print parameters
I/wpa_supplicant( 1137): wpa_s->wpa_state is 9
I/wpa_supplicant( 1137): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1137): isConcurrentMode() is 0
I/wpa_supplicant( 1137): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1137): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1137): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1137): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1137): wpa_s->reassociate is 0
I/wpa_supplicant( 1137): wpa_s->is_screen_on 0
I/wpa_supplicant( 1137): wpa_s->ifname wlan0
I/wpa_supplicant( 1137): End print parameters
I/wpa_supplicant( 1137): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1137): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1137): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1137): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1137): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1137): Add randomness: count=41 entropy=35
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1137): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1137): reply (489) for get BSS: id=0
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1137): freq=5220
I/wpa_supplicant( 1137): level=-50
I/wpa_supplicant( 1137): tsf=0000000187906061
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG7005g
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=1
,I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-57
I/wpa_supplicant( 1137): tsf=0000000187906087
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG700
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=2
I/wpa_supplicant( 1137): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-78
I/wpa_supplicant( 1137): tsf=0000000187906098
,I/wpa_supplicant( 1137): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1137): ssid=Gonzos
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=3
I/wpa_supplicant( 1137): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-56
I/wpa_supplicant( 1137): tsf=0000000170482833
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1137): ssid=01ABC
I/wpa_supplicant( 1137): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 187906061, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 187906087, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 187906098, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 170482833, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults,
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiManager( 1223): getScanResults enter 
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4286eb08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4286eb08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo,
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42634a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{427dcad8: PendingIntentRecord{426cf918 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=194531, Int=0
,D/PMS     (  906): acquireWL(426fea10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42634a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=9 [31][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0],
,D/PMS     (  906): acquireWL(4288c548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426fea10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4288c548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427e7170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(427e7170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4289bfb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1137): Change stage from stage3 to stage1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(4285aa60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4289bfb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 2739 seconds from now (1454983696433)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
D/libc    ( 1223): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =76ff +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/PMS     (  906): releaseWL(4285aa60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427c79a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(427c79a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4279c088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(4279c088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1137): wpa_supplicant_scan enter
I/wpa_supplicant( 1137): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1137): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1137): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1137): nl80211: Event message available
,D/wpa_supplicant( 1137): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1137): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1137): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1137): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-90
D/wpa_supplicant( 1137): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1137): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1137): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): Selecting BSS from priority group 1
I/wpa_supplicant( 1137): Recent assoc_freq = 2412 rssi = -90
D/wpa_supplicant( 1137): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1137): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1137): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1137): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1137):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1137):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-90
I/wpa_supplicant( 1137): Start print parameters
I/wpa_supplicant( 1137): wpa_s->wpa_state is 9
I/wpa_supplicant( 1137): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1137): isConcurrentMode() is 0
I/wpa_supplicant( 1137): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1137): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1137): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1137): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1137): wpa_s->reassociate is 0
I/wpa_supplicant( 1137): wpa_s->is_screen_on 0
I/wpa_supplicant( 1137): wpa_s->ifname wlan0
I/wpa_supplicant( 1137): End print parameters
I/wpa_supplicant( 1137): selected network = 1
D/wpa_supplicant( 1137): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-90
D/wpa_supplicant( 1137): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1137): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1137): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): ,WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): clear disabled list - type=1
I/wpa_supplicant( 1137): No suitable network found
W/wpa_supplicant( 1137): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1137): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1137): reply (376) for get BSS: id=0
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1137): freq=5220
I/wpa_supplicant( 1137): level=-50
I/wpa_supplicant( 1137): tsf=0000000205014839
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG7005g
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=1
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-90
I/wpa_supplicant( 1137): tsf=0000000205014865
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG700
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=2
I/wpa_supplicant( 1137): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-78
I/wpa_supplicant( 1137): tsf=0000000205014876
I/wpa_supplicant( 1137): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1137): ssid=Gonzos
I/wpa_supplicant( 1137): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 205014839, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -90, frequency: 2412, timestamp: 205014865, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -90, 0
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 205014876, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList,
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi:  0 [-90], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiManager( 1223): getScanResults enter 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(428a6208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428a6208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(428a7a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=238769, Int=0
,D/PMS     (  906): releaseWL(428a7a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(428a9ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428a9ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(428ab5e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=298769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428ab5e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(428ad868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428ad868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  906): killProcessQuiet, pid=4140
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4140:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4140
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(428b1ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=358769, Int=0
,D/PMS     (  906): releaseWL(428b1ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(428b42d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428b42d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(428b5bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=418769, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428b5bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(428b7e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428b7e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428b93d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(428b93d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(428beee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=478769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428beee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(428c1710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428c1710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(428c3010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=538769, Int=0
,D/PMS     (  906): releaseWL(428c3010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(428c5290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428c5290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428c67e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428c67e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1576): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1576): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428cc338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=598769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428cc338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428ce598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428ce598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1244): sku_id=99
,D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  906): acquireWL(428cfe98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=658769, Int=0
,D/PMS     (  906): releaseWL(428cfe98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428d3638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428d3638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428d5258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=718769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428d5258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428d7aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428d7aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428d93a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=778769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428d93a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428db620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428db620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428dcf20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=838769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428dcf20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428df748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428df748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428e1048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=898769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428e1048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428e32a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428e32a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428e4ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=958769, Int=0
,D/PMS     (  906): releaseWL(428e4ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(428ef750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d7db98: PendingIntentRecord{424cc118 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=794243, Int=0
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,V/AlarmManager(  906): sending alarm PendingIntent{426783e0: PendingIntentRecord{42745b00 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=958841, Int=0
,D/PMS     (  906): acquireWL(428f7b80): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428f7b80): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4330 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{424069d8: PendingIntentRecord{426b43f0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454983714818, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{41e1c8d0: PendingIntentRecord{426f7d78 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454984435151, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{41d54580: PendingIntentRecord{4275c828 com.google.android.gms startService}}, i=com.google.android.gms.icing.INDEX_RECURRING_MAINTENANCE, t=0, cnt=1, w=1454984448014, Int=86400000
,W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): acquireWL(428fcfa0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 4279): call getInstance()
,D/PMS     (  906): releaseWL(428ef750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4279): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/Icing   ( 2177): Performing maintenance.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4330/10049)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,I/Icing   ( 2177): updateResources: need to parse f{com.google.android.gms}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/Icing   ( 2177): Performing maintenance usage 2198885 budget 4147549874 free 99.947% index free 99.911% purge? false target 1726191044
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/Icing   ( 2177): Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
,D/PMS     (  906): releaseWL(428fcfa0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=4089
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4089:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4089
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(425152a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1374/10029)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025154
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025237
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025240
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025357
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026758
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029958
,D/PMS     (  906): releaseWL(425152a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(42632660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42632660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42793fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/SmartSyncUtils( 4279): isEpsOn(), nState = 0
V/AlarmManager(  906): sending alarm PendingIntent{424e2438: PendingIntentRecord{427de450 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454984518750, Int=0
,D/SmartSyncScreenOnOffTimeReceiver( 4279): [updateNmRange] bManual = false
D/PMS     (  906): acquireWL(424804f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4279 1000 null
,D/PMS     (  906): releaseWL(42793fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4279): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4279): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4279): SettingOnTime = 1454997600000, randomSettingOnTime = 1454997552000
D/SmartSyncScreenOnOffTimeReceiver( 4279): SettingOffTime = 1455069600000, randomSettingOffTime = 1455075607000
D/SmartSyncScreenOnOffTimeReceiver( 4279): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4279): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4279): bNightModeTurnOffOnce = false
D/PMS     (  906): acquireWL(42783f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423a8838: PendingIntentRecord{4280b350 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1454984518778, Int=0
,W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(424804f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4279): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4279): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4279): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 4279): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  906): getProviders()=[gps, network]
,D/LocationManagerService(  906): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  906): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/PMS     (  906): releaseWL(42783f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncDataLinkTurnOffService( 4279): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4279): isCharging status = 5
D/SmartSyncDataLinkTurnOffService( 4279): turnOffWifi ui setting = true
D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4279): isWifiHotSpotEnabled = false
D/SmartSyncUtils( 4279): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4279): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4279): turnOffWifi bWifiConnected = true
D/LocationManagerService(  906): getProviders()=[gps, network]
,D/LocationManagerService(  906): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  906): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 4279): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 4279): isCharging status = 5
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4279/1000)
,D/PMS     (  906): acquireWL(41b2deb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1018769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41b2deb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426a3298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426a3298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42849ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1078769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42849ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4280c650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4280c650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42356008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1138769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42356008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42709628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42709628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42889b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1198769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42889b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4251bc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4251bc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42838138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4216c518: PendingIntentRecord{42354390 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1258769, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42838138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42784760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42784760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4353): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4353): ====startRecUseTime====
D/htc.customization.log.level( 4353):  is 
W/CustomizationLogLevel( 4353): Level value is invalid, use default level 2
D/CustomizationManager( 4353):  Read ACC file spent 0.117 (s)
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4353): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4353): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4353): Parsing tag category name = system
I/CustomizationCIDLoader( 4353): Parsing tag category name = application
I/CustomizationCIDLoader( 4353): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4353): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4353): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4353): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4353): Parsing tag category name = Settings
D/CustomizationManager( 4353):  Read CID file spent 0.174 (s)
D/CustomizationManager( 4353):  All configurations done spent 0.174 (s)
W/HtcNativeFlag( 4353): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4353): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4353): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4353): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4353, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{422ea670 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{422ef560 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/DotMatrix( 1576): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1576): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1576): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  906): acquireWL(428fe228): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): releaseWL(428fe228): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/VoicemailCleanupService( 1298): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/[PluginManager]RegisterService( 1315): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1315): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/IcingCorporaProvider( 2810): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4367 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/IcingCorporaProvider( 2810): UpdateCorporaTask done [took 116 ms] updated apps [took 116 ms] 
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
E/ExternalAccountType( 1345): Unsupported attribute readOnly
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4367): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4367): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4367): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4367): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4367): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4367): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4367): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4367): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4367): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4367): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4367): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4367): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4367): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4367): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4367): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4367): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4367): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4367): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4367): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4367): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4367): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4367): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4367): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4367): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4367): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4367): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4367): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4367): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4367): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4367): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4367): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4367): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4367): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4367): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4367): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4367): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4367): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4367): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4367): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4367): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4367): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4367): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4367): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4367): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4367): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4367): threadid=11: thread exiting with uncaught exception (group=0x41708e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4367): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4367): Process: com.google.android.apps.docs, PID: 4367
E/AndroidRuntime( 4367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4367): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4367): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4367): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4367): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4367): 	at aho.run(AbstractDatabaseInstance.java:455)
E/SQLiteDatabase( 4367): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4367): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4367): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4367): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4367): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4367): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4367): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4367): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4367): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4367): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4367): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4367): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4367): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4367): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4367): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4367): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4367): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4367): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4367): Opened ClientFlag.db in read-only mode
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4367): killProcess, pid=4367
D/Process ( 4367): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4385 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/BroadcastQueue(  906): Skipping deliver [background] BroadcastRecord{42777698 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{42734d10 4367 com.google.android.apps.docs/10100/u0 remote:42457e70}: process crashing
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4367
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4367) has died.
W/ContextImpl( 4385): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4399 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4385): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4385): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4385): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4385): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4385): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4385): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4385): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4385): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4385): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4385): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4385): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4385): threadid=10: thread exiting with uncaught exception (group=0x41708e30)
E/AndroidRuntime( 4385): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4385): Process: com.android.keychain, PID: 4385
E/AndroidRuntime( 4385): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4385): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4385): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4385): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4385): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4385): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4385): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4385): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4385): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4385): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4385): killProcess, pid=4385
D/Process ( 4385): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454984777768.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
D/AppTag  ( 4399): getInstance(Context context)
I/ActivityManager(  906): Recipient 4385
I/ActivityManager(  906): Process com.android.keychain (pid 4385) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41bcbe50 +
I/Prism.WidgetManager( 1270): onLoadItems() +
D/AppTag  ( 4399): getInstance(Context context)
D/AppTag  ( 4399): onCreate()
D/PMS     (  906): acquireWL(4268ed90): PARTIAL_WAKE_LOCK  AsyncService 0x1 3556 10160 null
W/dalvikvm( 4019): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
W/PackageManager(  906): Unable to load service info ResolveInfo{427669c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PMS     (  906): releaseWL(4268ed90): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2177): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2177): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2177): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2177): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2177): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2177): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2177): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2177): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2177): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2177): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2177): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2177): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed

```
