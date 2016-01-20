#### Test 564496606be5677_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  907): acquireWL(42f7aac8): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
D/PMS     (  907): releaseWL(42f7aac8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): acquireWL(42f07cb8): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
D/PMS     (  907): releaseWL(42f07cb8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): acquireWL(4241d038): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
D/PMS     (  907): releaseWL(4241d038): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): acquireWL(41df9020): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
D/PMS     (  907): releaseWL(41df9020): PARTIAL_WAKE_LOCK  Icing 0x1 null
,--------- beginning of /dev/log/main
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
I/SensorManager(  907): mEventCount = 1200
D/CustomizationManager( 4634): ====startRecUseTime====
D/htc.customization.log.level( 4634):  is 
W/CustomizationLogLevel( 4634): Level value is invalid, use default level 2
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4643 uid=10077 gids={50077}
D/PMS     (  907): acquireWL(424bfc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
V/AlarmManager(  907): sending alarm PendingIntent{424c4aa0: PendingIntentRecord{4245d248 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453288517921, Int=60000
D/PMS     (  907): releaseWL(424bfc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
D/SMSBackup( 4643): SMSBackupAgentService started
D/SMSBackup( 4643): Checking restore status
D/SMSBackup( 4643): Restore complete
D/SMSBackup( 4643): cancelCheckAlarm
D/SMSBackup( 4643): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  907): killProcessQuiet, pid=4435
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4435:com.google.android.apps.genie.geniewidget/u0a106 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4435
D/PMS     (  907): acquireWL(421c1008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
D/PMS     (  907): acquireWL(420bfc88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
D/PMS     (  907): releaseWL(421c1008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  907): releaseWL(420bfc88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/CustomizationManager( 4634):  Read ACC file spent 0.069 (s)
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4634): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4634): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4634): Parsing tag category name = system
I/CustomizationCIDLoader( 4634): Parsing tag category name = application
I/CustomizationCIDLoader( 4634): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4634): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4634): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4634): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4634): Parsing tag category name = Settings
D/CustomizationManager( 4634):  Read CID file spent 0.115 (s)
D/CustomizationManager( 4634):  All configurations done spent 0.115 (s)
W/HtcNativeFlag( 4634): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4634): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4634): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4634): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4634
D/PMS     (  907): acquireHCC(41b673b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(42ecd120): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1103349816
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b3f068
E/cutils-trace( 4634): Error opening trace file: No such file or directory (2)
D/PMS     (  907): acquireWL(425cfbe0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4659 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4659): Binding Chromium to main looper Looper (main, tid 1) {41b085e0}
I/LibraryLoader( 4659): Expected native library version number "",actual native library version number ""
I/chromium( 4659): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4659): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(44144598): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): acquireWL(43dead48): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42382e58:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  907): releaseWL(44144598): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4659): 1102179424: getState(). Returning 12
I/Adreno-EGL( 4659): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4659): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4659): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4659): Local Branch: 
I/Adreno-EGL( 4659): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4659): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4659):                  aa63bbd948f41d15fc72f585e
W/chromium( 4659): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4659): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4659): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4659): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4659): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4659): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4659): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4659): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4659): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4659): CordovaWebView is running on device made by: HTC
,W/AwContents( 4659): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +286ms
W/ResourceType( 4659): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4659): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b50310, mServedView=org.apache.cordova.engine.SystemWebView{41b15f78 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Disable input method client, pid=1270
,I/InputMethodManagerService(  907): Enable input method client, pid=4659
W/AwContents( 4659): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  907): releaseWL(425cfbe0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4659): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4659): JniHelper::setJavaVM(0x415e2048), pthread_self() = 1663792712
,I/chromium( 4659): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WIFI_ICON( 1118): WifiActivity: 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 11.993MB for 42652-byte allocation
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 12.070MB for 95956-byte allocation
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 12.149MB for 143930-byte allocation
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  907): acquireWL(44365b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{43f3e600: PendingIntentRecord{4252d940 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=106057, Int=0
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=112 rxSum=88} preTxRxSum={txSum=109 rxSum=86}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20280 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20281 delay=15s
D/PMS     (  907): releaseWL(44365b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 12.264MB for 215890-byte allocation
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 12.439MB for 323830-byte allocation
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 12.710MB for 485740-byte allocation
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 13.716MB for 1092904-byte allocation
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 14.627MB for 1639352-byte allocation
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 15.882MB for 2459024-byte allocation
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(41b673b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(42ecd120): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4659): Grow heap (frag case) to 18.056MB for 3688532-byte allocation
,W/jxcore-log( 4659): Initializing JXcore engine
,W/jxcore-log( 4659): JXcore engine is ready
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:154, mTXpacketCount:151, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,W/jxcore-log( 4659): Starting JXcore engine
,W/jxcore-log( 4659): Platform android
W/jxcore-log( 4659): 
,W/jxcore-log( 4659): Process ARCH arm
W/jxcore-log( 4659): 
,D/PMS     (  907): releaseWL(43dead48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4659): JXcore Cordova bridge is ready!
I/jxcore-log( 4659): 
,W/jxcore-log( 4659): JXcore engine is started
,E/jxcore  ( 4659): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4659): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4659): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4659): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  907): acquireWL(44179768): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
,I/FeedHostManager( 1270): [onResume]
,I/FeedProviderManager( 1270): onResume
I/SocialFeedProvider( 1270): +onResume
I/SocialFeedProvider( 1270): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1270): -onResume
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1270/10075)
,I/InputMethodManagerService(  907): Disable input method client, pid=4659
,W/IInputConnectionWrapper( 4659): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  907): Enable input method client, pid=1270
,D/PMS     (  907): releaseWL(44179768): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  907): killProcessQuiet, pid=3322
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  907): Killing 3322:com.android.defcontainer/u0a19 (adj 15): empty #17
,E/libEGL  ( 4659): call to OpenGL ES API with no current context (logged once per thread)
I/ActivityManager(  907): Recipient 3322
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42229ac0
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42229ac0, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fd5b28
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@41cc8b68
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 380ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0,
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMS     (  907): OOBE c monitor 11,
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=1270,
D/NfcService( 1254): applyRouting -2,
V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42560b18)
,I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  907): acquireWL(425cb718): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  907): releaseWL(425cb718): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): wakingUp
D/PMS     (  907): acquireWL(42ba0738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMS     (  907): releaseWL(42ba0738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
,D/PMN     (  907): onScreenOn
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/MtpService( 2000): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1254): applyRouting - 0
D/MtpService( 2000): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting -2
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/AutoSetting( 1416): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  907): acquireWL(42c47750): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  907): releaseWL(42c47750): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
,D/AutoSetting( 1416): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20282 delay=15s
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1118): stop update clock
,D/TetherSettings( 4383): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4383): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4383): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4383): Cust_ConnectToPC   : spcsc>false
D/        ( 4383): Cust_ConnectToPC   : IPT>true
,D/        ( 4383): Cust_ConnectToPC   : Singel_USB>false
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/Settings( 4383): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4383): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4383): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4383): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:On
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
I/PSReceiver( 4383): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/SmartNS_PSService( 4383): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4383): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4383):  defaultType:0
W/ContextImpl( 4383): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1118): WifiActivity: 0
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  373): ParamSet string: screen_state=on
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  907): updateScreenOn: false
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4714 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): onScreenOn: 1453288524927
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1794): onScreenOn: 1453288524927
D/PMS     (  907): acquireWL(439d70b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1443 10028 null
D/PMS     (  907): releaseWL(439d70b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fd5b28
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  907): pid=907, uid=1000
,W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
,W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fd5b28, eanble = 0, strlen(mName) = 91
,W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@41cc8b68
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
W/ContextImpl( 4714): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): acquireWL(423c6c58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/SmartSyncUtils( 4714): isEpsOn(), nState = 0
,I/FeedHostManager( 1270): [onPause]
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20282 mDataStallAlarmIntent=PendingIntent{42502820: PendingIntentRecord{4252d940 android broadcastIntent}}
,I/FeedProviderManager( 1270): onPause
,I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b3f068
I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:Off
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1159): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  907):    returned true
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
D/PMS     (  907): acquireWL(441c3198): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4714 1000 null
D/PMS     (  907): acquireWL(42ab1358): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,V/SRS_Proc(  373): ParamSet string: screen_state=off
D/PMS     (  907): releaseWL(423c6c58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/ContactMessageStore( 1243): start background delete task...
,D/SmartSyncUtils( 4714): getMobilePolicyEnabled, result = true
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
D/NetworkPolicy(  907): updateScreenOn: false
D/PMS     (  907): releaseWL(441c3198): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  907): killProcessQuiet, pid=4059
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Killing 4059:com.google.android.music:main/u0a154 (adj 15): empty #17
D/PMS     (  907): releaseWL(42ab1358): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4714): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4714): isEpsOn(), nState = 0
D/SmartSyncUtils( 4714): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4714): isEpsOn(), nState = 0
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41cc8b68
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  907): New client listening to asynchronous messages
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41cc8b68, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41cc8b68, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41cc8b68
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42333690 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42333690 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1416): service - mHandler: cancel location update
,D/AutoSetting( 1416): service -           changes count: 0
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): acquireWL(44342a50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1443 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1794): onScreenOff
D/PMS     (  907): releaseWL(44342a50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  907): Recipient 4059
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.music (pid 4059): Died!
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1526): service - handleMessage() stop self
,D/AutoSetting( 1526): service - onDestroy() END
,D/AutoSetting( 1526): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4490
,I/ActivityManager(  907): Killing 4490:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4490
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/Process (  907): killProcessQuiet, pid=4092
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4092:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4092
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(442490d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(442490d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4436dfa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5dd8: PendingIntentRecord{424addf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=134099, Int=0
,D/PMS     (  907): acquireWL(42ca2948): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4436dfa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43d93d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(43de7ef0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  907): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4738 uid=10106 gids={50106, 3003, 5012}
,D/PMS     (  907): releaseWL(42ca2948): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(43d93d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4738): LocationClient connecting
,D/PMS     (  907): acquireWL(42590938): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
,D/PMS     (  907): releaseWL(42590938): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4738): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4738): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4738): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4738): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4738): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4738): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ProviderInstaller( 4738): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42ee2d28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42ee2d28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4738): Last usage 0, idle 1453288548s, sync interval 2592000s
,I/NewsWeather( 4738): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4738): onConnected null
,D/PMS     (  907): acquireWL(425cc4e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
,D/PMS     (  907): acquireWL(42613740): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
,W/GCoreFlp( 1443): No location to return for getLastLocation()
,I/NewsWeather( 4738): LocationClient onConnected: location null
D/PMS     (  907): releaseWL(425cc4e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(42613740): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4738): Skip sync for lookup editions
,I/NewsWeather( 4738): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4738): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1599): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1599): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,E/NewsWeather( 4738): Unrecoverable authentication exception
E/NewsWeather( 4738): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4738): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4738): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4738): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41bc6238 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4738): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4738): [NET] getaddrinfo-,err=8
D/libc    ( 4738): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4738): [NET] getaddrinfo-, 1
,D/libc    ( 4738): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
I/RemoteViews.Performance( 1118): com.google.android.gms 2 11 5 12
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =3710 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4738): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4738): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4738): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(43ed6f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,E/NewsWeather( 4738): Failed to syncNewsAppData
,E/NewsWeather( 4738): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(43ed6f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(443066b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 69233, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(43de7ef0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/Process (  907): killProcessQuiet, pid=4024
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  907): Killing 4024:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/PMS     (  907): releaseWL(443066b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(425812d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1443/10028)
D/PMS     (  907): releaseWL(425812d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1333): Unsupported attribute readOnly
,I/ActivityManager(  907): Recipient 4024
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV4    ( 4738): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(4424b298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41f1c7e8: PendingIntentRecord{423d9208 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141725, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(4431c128): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(4424b298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =ccf8 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/PMS     (  907): acquireWL(442b7798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10028}
,V/AlarmManager(  907): sending alarm PendingIntent{430e97f8: PendingIntentRecord{41dbe070 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141845, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  907): releaseWL(442b7798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  907): acquireWL(42fc9148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11
D/libc    (  366): [NET]res_nsend:resplen=238
D/libc    (  366): [NET]res_queryN: exit 3, ancount=10
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/PMS     (  907): releaseWL(42fc9148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1416): service - handleMessage() stop self
,D/AutoSetting( 1416): service - onDestroy() END
,D/AutoSetting( 1416): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4528
I/ActivityManager(  907): Killing 4528:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,I/ActivityManager(  907): Recipient 4528
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): acquireWL(444aa578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=146768, Int=0
,D/PMS     (  907): releaseWL(444aa578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): releaseWL(4431c128): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2227/10028)
,D/PMS     (  907): acquireWL(442f7f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5dd8: PendingIntentRecord{424addf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=164187, Int=0
,D/PMS     (  907): acquireWL(442f6d80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(442db740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(442f7f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): releaseWL(442f6d80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(442db740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43d558a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43d558a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43370a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{42bb2780: PendingIntentRecord{42a93f78 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175421, Int=0
,D/PMS     (  907): releaseWL(43370a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(43365268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43365268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(426f2a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=206767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426f2a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42678460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(42678460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(425dd1d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425dd1d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(425629b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5dd8: PendingIntentRecord{424addf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=265017, Int=0
,D/PMS     (  907): acquireWL(4255fc48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(425629b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(425494c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=10 [46][5][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(4245dfb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,D/PMS     (  907): releaseWL(4255fc48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(425494c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42436490): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42436490): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4738): Last usage 0, idle 1453288678s, sync interval 2592000s
I/NewsWeather( 4738): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4738): Skip sync for lookup editions
,I/NewsWeather( 4738): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4738): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1599): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1599): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4738): Unrecoverable authentication exception
E/NewsWeather( 4738): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4738): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4738): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4738): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41e8c208 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 1 9 3 12
,D/PMS     (  907): acquireWL(4233e000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  907): releaseWL(4233e000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
E/NewsWeather( 4738): Failed to syncNewsAppData
,E/NewsWeather( 4738): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(44335108): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4245dfb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 135285, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/PMS     (  907): releaseWL(44335108): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1443/10028)
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42521528): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42521528): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1333): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(4416a328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=266768, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4416a328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43f28688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43f28688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(44172e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5dd8: PendingIntentRecord{424addf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=295079, Int=0
,D/PMS     (  907): acquireWL(423470d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(44172e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(443a4708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(423470d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(443a4708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(42ef33e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/PMS     (  907): releaseWL(42ef33e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(426b9f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=326767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426b9f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(42dc49f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42dc49f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1599): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1599): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,E/PlayEventLogger( 4327): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4327): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4327): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4327): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4327): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4327): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4327): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4327): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41b21168 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 2 11 4 12
,D/libc    ( 4327): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4327): [NET] getaddrinfo-,err=8
D/libc    ( 4327): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4327): [NET] getaddrinfo-, 1
,D/libc    ( 4327): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024,
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =a3d5 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4327): [NET] getaddrinfo_proxy-, success
I/global  ( 4327): call createSocket() return a new socket.
,D/libc    ( 4327): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4327): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4327): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4327): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(44192360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(44192360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(426b9d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=386767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426b9d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43e17960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43e17960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(42e8d7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42e8d7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43dd5068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=446767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43dd5068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43ddb9a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): releaseWL(43ddb9a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(433bb5a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=506768, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(433bb5a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(44362a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5dd8: PendingIntentRecord{424addf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=524885, Int=0
,D/PMS     (  907): acquireWL(423aba08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(44362a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42e282d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=8 [45][4][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(44371230): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,D/PMS     (  907): releaseWL(423aba08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42e282d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43dd18c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43dd18c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4738): Last usage 0, idle 1453288938s, sync interval 2592000s
I/NewsWeather( 4738): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4738): Skip sync for lookup editions
,I/NewsWeather( 4738): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4738): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1599): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1599): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41eae778 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4738): Unrecoverable authentication exception
E/NewsWeather( 4738): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4738): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4738): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4738): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1118): com.google.android.gms 3 13 5 12
D/libc    ( 4738): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4738): [NET] getaddrinfo-,err=8
D/libc    ( 4738): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4738): [NET] getaddrinfo-, 1
,D/libc    ( 4738): [NET] getaddrinfo_proxy+
,D/libc    (  366): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =8f89 +++++
,D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4738): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 4738): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4738): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(442fd240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,E/NewsWeather( 4738): Failed to syncNewsAppData
,E/NewsWeather( 4738): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(442fd240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(439d36d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 265421, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(44371230): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1443/10028)
,W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(439d36d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4436a328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4436a328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1333): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(43f14378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43f14378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(4308e430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4308e430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43aad908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5dd8: PendingIntentRecord{424addf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=554951, Int=0
,D/PMS     (  907): acquireWL(43e9bf80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(43aad908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44358ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43e9bf80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(44358ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(43f7e430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=566768, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43f7e430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42b2c118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42b2c118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43444520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43444520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1243): sku_id=99
D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/PMS     (  907): acquireWL(43ea3670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=626767, Int=0
I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43ea3670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42319648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42319648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4343aa60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4343aa60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4794 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  907): acquireWL(442faf10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10047}
,V/AlarmManager(  907): sending alarm PendingIntent{41e28930: PendingIntentRecord{41e28d18 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453288634717, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{43e7d578: PendingIntentRecord{41f51d78 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453289089225, Int=0
,D/PMS     (  907): releaseWL(442faf10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4794/10047)
I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4327): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4327): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4327): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4327): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4327): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/Process (  907): killProcessQuiet, pid=4423
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4423:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4423
,D/PMS     (  907): acquireWL(4336f048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=686768, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4336f048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(442d1cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10073}
,V/AlarmManager(  907): sending alarm PendingIntent{4208fef8: PendingIntentRecord{44285c28 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453289104451, Int=0
,D/PMS     (  907): releaseWL(442d1cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4327): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  907): acquireWL(4263d338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4263d338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43365bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(43365bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/Process (  907): killProcessQuiet, pid=4558
,I/ActivityManager(  907): Killing 4558:com.htc.backup/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4558
,D/PMS     (  907): acquireWL(4307ceb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=746767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4307ceb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42f35fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  907): releaseWL(42f35fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42fbb580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41de1580: PendingIntentRecord{42445688 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786697, Int=0
,D/PMS     (  907): releaseWL(42fbb580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(43e982f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43e982f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43a8ccf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=806767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43a8ccf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41b00e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(41b00e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4335a830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4335a830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4432f4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=866767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4432f4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42b2a190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(42b2a190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42e939b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42e939b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43a26430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=926767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43a26430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(433beda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(433beda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42a6a248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=986767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42a6a248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  907): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4816 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,D/PMS     (  907): acquireWL(4331dad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10075}
,V/AlarmManager(  907): sending alarm PendingIntent{43a78910: PendingIntentRecord{43d40340 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{42451f30: PendingIntentRecord{41b6e000 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=929292, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{423ef320: PendingIntentRecord{423aacc8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453289355048, Int=900000
,D/PMS     (  907): acquireWL(42d011c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1372 10028 null
,V/AlarmManager(  907): sending alarm PendingIntent{424e0a68: PendingIntentRecord{43d9d8c0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453289425034, Int=0
,D/PMS     (  907): releaseWL(42d011c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  907): acquireWL(43331198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,W/ContextImpl( 4714): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): releaseWL(43331198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4714): call getInstance()
,D/SmartSyncUtils( 4714): isEpsOn(), nState = 0
,D/PMS     (  907): acquireWL(42723630): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4714 1000 null
,D/PowerUsageList:PowerUsageHelper( 4714): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4714): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4714): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4714): AlarmOnTime = -1
D/PMS     (  907): releaseWL(4331dad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(430730a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/SmartSyncScreenOnOffTimeReceiver( 4714): SettingOnTime = 1453338000000, randomSettingOnTime = 1453335544000
D/SmartSyncScreenOnOffTimeReceiver( 4714): SettingOffTime = 1453334400000, randomSettingOffTime = 1453334814000
D/SmartSyncScreenOnOffTimeReceiver( 4714): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4714): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4714): bNightModeTurnOffOnce = false
D/PMS     (  907): releaseWL(42723630): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/ImageRamCache( 4816): create image Cache, size: 31457280.
I/ImageRamCache( 4816): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4816): create image Cache, size: 12582912.
,I/FeedSettings( 4816): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4816): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4816): GroupBudget 60 45 15
,D/GCM     ( 1372): Message class mow
,I/Prism.ExternalStringMa_( 4816): changeLocale(): en_GB
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10028)
I/Prism.AllAppsOptionsMa_( 4816): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4816): loadGridSize() with Alternative
D/PMS     (  907): releaseWL(430730a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(43ac2890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  907): releaseWL(43ac2890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    ( 4816): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4816): [NET] getaddrinfo-,err=8
D/libc    ( 4816): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4816): [NET] getaddrinfo-, 1
,D/libc    ( 4816): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =99f0 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  366): [NET]res_nsend:resplen=206
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4816): [NET] getaddrinfo_proxy-, success
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (4816/10075)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (4816/10075)
,D/Process (  907): killProcessQuiet, pid=4575
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4575:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4575
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(41f38ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(41f38ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43ddb6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  907): releaseWL(43ddb6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(442ce600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5dd8: PendingIntentRecord{424addf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1044424, Int=0
,D/PMS     (  907): acquireWL(42528ce0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(442ce600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(41e830e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=1 [65][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(43954eb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
D/PMS     (  907): releaseWL(42528ce0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  907): releaseWL(41e830e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4350c930): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/NewsWeather( 4738): Last usage 0, idle 1453289457s, sync interval 2592000s
,I/NewsWeather( 4738): setPeriodicSync in seconds 2592000
D/PMS     (  907): releaseWL(4350c930): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4738): Skip sync for lookup editions
,I/NewsWeather( 4738): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4738): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1599): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1599): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,E/NewsWeather( 4738): Unrecoverable authentication exception
E/NewsWeather( 4738): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4738): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4738): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4738): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4738): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{42032b40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4738): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4738): [NET] getaddrinfo-,err=8
D/libc    ( 4738): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4738): [NET] getaddrinfo-, 1
,D/libc    ( 4738): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =dcb6 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,I/RemoteViews.Performance( 1118): com.google.android.gms 2 12 4 12
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4738): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4738): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4738): [NET] getaddrinfo-,err=8
,E/NewsWeather( 4738): Failed to syncNewsAppData
,E/NewsWeather( 4738): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): acquireWL(433d0c28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(441e1638): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 525498, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(433d0c28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  907): releaseWL(43954eb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1443/10028)
,D/PMS     (  907): releaseWL(441e1638): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(443422a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(443422a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1333): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(44294458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1046767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44294458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43aad8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43aad8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43266208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5dd8: PendingIntentRecord{424addf0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1074665, Int=0
,D/PMS     (  907): acquireWL(43d07ed0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(43266208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4449dc38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43d07ed0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(4449dc38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(4416be38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4416be38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43ec4af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1106767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43ec4af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(430d3780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(430d3780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42d87028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1166767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42d87028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43aab278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43aab278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/PowerUI ( 1118): closing low battery warning: level=100
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(43ede280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1226767, Int=0
,D/PMS     (  907): releaseWL(43ede280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43382320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  907): releaseWL(43382320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42fe0f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4235d418: PendingIntentRecord{423586d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1286767, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42fe0f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43aaaf00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1599): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1599): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(43aaaf00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4847): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4847): ====startRecUseTime====
D/htc.customization.log.level( 4847):  is 
W/CustomizationLogLevel( 4847): Level value is invalid, use default level 2
D/CustomizationManager( 4847):  Read ACC file spent 0.118 (s)
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4847): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4847): Parsing tag category name = system
I/CustomizationCIDLoader( 4847): Parsing tag category name = application
I/CustomizationCIDLoader( 4847): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4847): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4847): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4847): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4847): Parsing tag category name = Settings
D/CustomizationManager( 4847):  Read CID file spent 0.178 (s)
D/CustomizationManager( 4847):  All configurations done spent 0.178 (s)
W/HtcNativeFlag( 4847): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4847): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4847): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4847): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4847, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=4659
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 4659:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1599): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1599): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1599): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1443): Ignoring removeGeofence because network location is disabled.
I/acms    ( 1886): Unregistering com.test.thalitest
E/acms    ( 1886): Could not unregister removed application com.test.thalitest
D/PMS     (  907): acquireWL(43a9eb40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1443 10028 null
D/PMS     (  907): releaseWL(43a9eb40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 4816): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4816): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PackageBroadcastService( 2227): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4862 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
E/ExternalAccountType( 1333): Unsupported attribute readOnly
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4862): install
I/MultiDex( 4862): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/MultiDex( 4862): loading existing secondary dex files
I/MultiDex( 4862): load found 1 secondary dex files
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4862): install done
I/ActivityManager(  907): Delaying start of: ServiceRecord{4437f698 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4878 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2227): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2227, uid=10028, userID:0
I/Icing   ( 2227): doRemovePackageData com.test.thalitest
D/PMS     (  907): acquireWL(42094958): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
I/ProviderInstaller( 4862): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  907): releaseWL(42094958): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4878): install
I/MultiDex( 4878): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4878): loading existing secondary dex files
I/MultiDex( 4878): load found 1 secondary dex files
I/MultiDex( 4878): install done
I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4878): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  907): Resuming delayed broadcast
E/SharedPreferencesImpl( 1208): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1416): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteDatabase( 2227): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2227): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2227): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2227): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2227): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2227): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2227): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2227): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2227): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2227): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2227): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2227): Runtime exception while performing operation
E/ClearPendingStateOp( 2227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2227): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2227): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2227): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2227): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2227): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2227): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2227): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2227): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2227): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1416): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1416): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca168b8
F/ClearPendingStateOp( 2227): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2227): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2227): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2227): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2227): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2227): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2227): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2227): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2227): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2227): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2227): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/[PluginManager]RegisterService( 1416): provider may killed!
W/[PluginManager]RegisterService( 1416): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1416): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1416): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1416): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1416): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1416): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1416): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1416): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1416): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1416): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1416): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1416): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1416): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1416): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1416): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1416): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
E/DropBoxManagerService(  907): Can't write: system_app_wtf
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
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
I/IcingCorporaProvider( 3046): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4901 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 3046): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3046): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca90450
W/dalvikvm( 3046): threadid=14: thread exiting with uncaught exception (group=0x416dae30)
E/AndroidRuntime( 3046): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 3046): Process: com.google.android.googlequicksearchbox:search, PID: 3046
E/AndroidRuntime( 3046): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3046): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3046): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 3046): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3046): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3046): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 3046): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 3046): 	at cid.d(PG:186)
E/AndroidRuntime( 3046): 	at clo.g(PG:594)
E/AndroidRuntime( 3046): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 3046): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 3046): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 3046): 	at clp.Rl(PG:910)
E/AndroidRuntime( 3046): 	at clr.tL(PG:827)
E/AndroidRuntime( 3046): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 3046): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 3046): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3046): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3046): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3046): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 3046): killProcess, pid=3046
D/Process ( 3046): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4862): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4862): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4862): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4862): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4862): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4862): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4862): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4862): threadid=12: thread exiting with uncaught exception (group=0x416dae30)
E/AndroidRuntime( 4862): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4862): Process: com.google.android.gms.drive, PID: 4862
E/AndroidRuntime( 4862): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4862): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4862): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4862): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4862): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4862): 	at ctn.run(SourceFile:985)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
D/Process ( 4862): killProcess, pid=4862
D/Process ( 4862): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 4862
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4862) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  907): Recipient 3046
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 3046): Died!
D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Process com.google.android.googlequicksearchbox:search (pid 3046) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
E/SQLiteDatabase( 4901): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4901): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4901): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4901): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4901): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4901): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4901): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4901): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4901): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4901): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4901): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4901): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4901): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4901): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4901): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4901): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4901): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4901): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4901): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4901): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4901): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4901): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4901): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4901): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4901): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4901): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4901): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4901): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4901): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4901): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4901): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4901): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4901): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4901): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4901): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4901): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4901): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4901): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4901): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4901): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4901): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4901): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4901): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4901): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4901): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4901): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4901): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4901): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4901): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4901): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4901): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4901): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4901): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4901): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4901): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4901): Opened ClientFlag.db in read-only mode
W/PackageManager(  907): Unable to load service info ResolveInfo{44460980 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4901): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4901): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4901): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4901): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4901): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4901): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4901): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4901): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4901): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4901): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4901): threadid=11: thread exiting with uncaught exception (group=0x416dae30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4901): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4901): Process: com.google.android.apps.docs, PID: 4901
E/AndroidRuntime( 4901): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4901): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4901): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4901): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4901): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4901): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4901): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4901): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4901): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4901): killProcess, pid=4901
D/Process ( 4901): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4919 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4901
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4901) has died.
W/ContextImpl( 4919): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/Prism.ItemManager( 4816): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4816): loadItems() com.htc.launcher.pageview.WidgetManager@41b78778 +
I/Prism.WidgetManager( 4816): onLoadItems() +
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b9dff0 +
I/Prism.WidgetManager( 1270): onLoadItems() +
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4932 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4919): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4919): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4919): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4919): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4919): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4919): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4919): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4919): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4919): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4919): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4919): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4919): threadid=10: thread exiting with uncaught exception (group=0x416dae30)
E/AndroidRuntime( 4919): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4919): Process: com.android.keychain, PID: 4919
E/AndroidRuntime( 4919): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4919): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4919): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4919): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4919): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4919): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4919): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4919): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4919): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4919): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4932): getInstance(Context context)
D/Process ( 4919): killProcess, pid=4919
D/Process ( 4919): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453289731090.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 4919
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4919) has died.
D/AppTag  ( 4932): getInstance(Context context)
D/AppTag  ( 4932): onCreate()
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10323ms
I/DeviceManagement( 4545): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4545): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
D/PMS     (  907): acquireWL(426e73c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4362 10160 null
I/ActivityManager(  907): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/DeviceManagement( 4545): WorkflowService: Starting workflow service
I/DeviceManagement( 4545): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ce2f20] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4545): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4545): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4545): PackageUpdateWorkflow: ==================================================
D/PMS     (  907): releaseWL(426e73c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
I/DeviceManagement( 4545): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4545): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 4545): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4545): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5ca87630
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4952 uid=10099 gids={50099, 3003, 5012}
W/DeviceManagement( 4545): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ce2f20]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 4545): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 4545): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 4545): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4545): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4545): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4545): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4545): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4545): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4545): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4545): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4545): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4545): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
