#### Test 56449660bb41d23_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  904): Waited long enough for: ServiceRecord{423cb508 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4501): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4501): ====startRecUseTime====
D/htc.customization.log.level( 4501):  is 
W/CustomizationLogLevel( 4501): Level value is invalid, use default level 2
D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/CustomizationManager( 4501):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4501): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4501): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4501): Parsing tag category name = system
I/CustomizationCIDLoader( 4501): Parsing tag category name = application
I/CustomizationCIDLoader( 4501): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4501): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4501): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4501): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4501): Parsing tag category name = Settings
D/CustomizationManager( 4501):  Read CID file spent 0.104 (s)
D/CustomizationManager( 4501):  All configurations done spent 0.104 (s)
W/HtcNativeFlag( 4501): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4501): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4501): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4501): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4501
D/PMS     (  904): acquireHCC(429ca7c0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(4351ac38): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/asset   (  904): Copying FileAsset 0x640d8c00 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1112517344
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d82880
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
D/PMS     (  904): acquireWL(44205730): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4512 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1269): [trimMemory] 20
W/asset   ( 4512): Copying FileAsset 0x5c77c428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4512): Binding Chromium to main looper Looper (main, tid 1) {41af9610}
I/LibraryLoader( 4512): Expected native library version number "",actual native library version number ""
I/chromium( 4512): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4512): Initializing chromium process, renderers=0
D/PMS     (  904): acquireWL(42516940): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): acquireWL(426030f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4254da20:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4512): 1102114888: getState(). Returning 12
D/PMS     (  904): releaseWL(42516940): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4512): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4512): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4512): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4512): Local Branch: 
I/Adreno-EGL( 4512): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4512): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4512):                  aa63bbd948f41d15fc72f585e
W/chromium( 4512): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4512): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4512): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4512): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4512): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4512): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4512): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4512): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4512): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4512): CordovaWebView is running on device made by: HTC
,W/AwContents( 4512): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  904): Disable input method client, pid=1269
,W/ResourceType( 4512): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4512): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b406f8, mServedView=org.apache.cordova.engine.SystemWebView{41b06360 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4512): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +290ms
I/InputMethodManagerService(  904): Enable input method client, pid=4512
D/PMS     (  904): releaseWL(44205730): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4512): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4512): JniHelper::setJavaVM(0x415cb048), pthread_self() = 1663869600
,I/chromium( 4512): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 12.036MB for 63974-byte allocation
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 12.096MB for 95956-byte allocation
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 12.172MB for 143930-byte allocation
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 12.264MB for 215890-byte allocation
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 12.439MB for 323830-byte allocation
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 13.114MB for 728606-byte allocation
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 13.715MB for 1092904-byte allocation
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 14.619MB for 1639352-byte allocation
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 15.881MB for 2459024-byte allocation
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(429ca7c0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(4351ac38): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4512): Grow heap (frag case) to 18.053MB for 3688532-byte allocation
,W/jxcore-log( 4512): Initializing JXcore engine
,W/jxcore-log( 4512): JXcore engine is ready
,W/jxcore-log( 4512): Starting JXcore engine
,W/jxcore-log( 4512): Platform android
W/jxcore-log( 4512): 
,W/jxcore-log( 4512): Process ARCH arm
W/jxcore-log( 4512): 
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4556 uid=10077 gids={50077}
,D/PMS     (  904): acquireWL(4420c8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
,V/AlarmManager(  904): sending alarm PendingIntent{42358038: PendingIntentRecord{426bbed0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453390869723, Int=60000
,D/PMS     (  904): releaseWL(4420c8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/SMSBackup( 4556): SMSBackupAgentService started
,D/SMSBackup( 4556): Checking restore status
D/SMSBackup( 4556): Restore complete
,D/SMSBackup( 4556): cancelCheckAlarm
,D/SMSBackup( 4556): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3434
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3434:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3434
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): releaseWL(426030f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4512): JXcore Cordova bridge is ready!
I/jxcore-log( 4512): 
,W/jxcore-log( 4512): JXcore engine is started
,E/jxcore  ( 4512): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4512): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4512): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4512): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 27ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  904): acquireWL(43aa4b90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
,I/FeedHostManager( 1269): [onResume]
,I/FeedProviderManager( 1269): onResume
I/SocialFeedProvider( 1269): +onResume
I/SocialFeedProvider( 1269): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1269): -onResume
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (1269/10075)
,I/InputMethodManagerService(  904): Disable input method client, pid=4512
,W/IInputConnectionWrapper( 4512): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  904): Enable input method client, pid=1269
,D/PMS     (  904): releaseWL(43aa4b90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  904): killProcessQuiet, pid=3860
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  904): Killing 3860:com.google.android.music:main/u0a154 (adj 15): empty #17
,E/libEGL  ( 4512): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  904): Recipient 3860
,D/MediaRouterService(  904): Client com.google.android.music (pid 3860): Died!
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:186, mTXpacketCount:185, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=128 rxSum=120} preTxRxSum={txSum=128 rxSum=120}
D/WifiDataStallTracker(  904): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  904): onDataStallAlarm: tag=21185 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=21186 delay=15s
D/PMS     (  904): acquireWL(43671150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{425a2c50: PendingIntentRecord{4254d5e0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=108390, Int=0
D/PMS     (  904): releaseWL(43671150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  904): mEventCount = 1200
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42155380
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42155380, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42365f60
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@4255b528
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  904): mWirelessDisplayManager is null
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 419ms
,D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
,D/PMS     (  904): nativeSetAutoSuspend:true done,
D/HABCtrl (  904): TPE algorithm. remove timeout.
D/PMS     (  904): OOBE c monitor 11
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
D/PMS     (  904): acquireWL(4201ac00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=1269
I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1254): ScreenObserver: OFF
D/NfcService( 1254): applyRouting - 0
V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42503598)
D/NfcService( 1254): applyRouting -2
V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
D/PMS     (  904): releaseWL(4201ac00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  904): wakingUp
D/PMS     (  904): acquireWL(423490c0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/WindowManager(  904): No lock screen! windowToken=null
D/PMS     (  904): releaseWL(423490c0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  904): onScreenOn
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/MtpService( 1992): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 1992): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting - 0
,D/AutoSetting( 1382): receiver - intent: android.intent.action.USER_PRESENT
D/NfcService( 1254): applyRouting -2
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  904): acquireWL(4246ef58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  904): releaseWL(4246ef58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,D/AutoSetting( 1382): service - onCreate()
,I/ClockThread( 1114): stop update clock
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/TetherSettings( 4350): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/        ( 4350): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4350): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4350): Cust_ConnectToPC   : spcsc>false
D/        ( 4350): Cust_ConnectToPC   : IPT>true
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
,D/        ( 4350): Cust_ConnectToPC   : Singel_USB>false
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=21187 delay=15s
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1382): service - AddressCache: using context: com.htc.Weather
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1,
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:On
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/Settings( 4350): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/AutoSetting( 1382): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,E/SmartNS_Utility( 4350): hasRemovableStorageSlot: true
,D/LocationManagerService(  904): request 4253eb60 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
V/SRS_Proc(  370): ParamSet string: screen_state=on
D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
D/SmartNS_Utility( 4350): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/SmartNS_NSReceiver( 4350): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/PSReceiver( 4350): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
I/SmartNS_PSService( 4350): onReceive:android.intent.action.USER_PRESENT
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
W/ContextImpl( 4350): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  904): updateScreenOn: false
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/Settings( 4350): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4350):  defaultType:0
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4584 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): acquireWL(441e7980): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1480 10028 null
D/PMS     (  904): releaseWL(441e7980): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1803): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1803): onScreenOn: 1453390877549
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1803): onScreenOn: 1453390877550
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42365f60
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42365f60, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@4255b528
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
W/ContextImpl( 4584): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): acquireWL(42ed0af0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,I/FeedHostManager( 1269): [onPause]
,I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d82880
I/SocialFeedProvider( 1269): +onPause
,I/SocialFeedProvider( 1269): -onPause
,D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=21187 mDataStallAlarmIntent=PendingIntent{4255d748: PendingIntentRecord{4254d5e0 android broadcastIntent}}
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:Off
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1165): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  904):    returned true
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(42f64e40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
D/PMS     (  904): releaseWL(42ed0af0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  904): updateScreenOn: false
,D/SmartSyncUtils( 4584): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(43dbbdf8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4584 1000 null
,D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(42f64e40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/SmartSyncUtils( 4584): getMobilePolicyEnabled, result = true
D/PMS     (  904): releaseWL(43dbbdf8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4584): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/ContactMessageStore( 1243): start background delete task...
,D/SmartSyncUtils( 4584): isEpsOn(), nState = 0
D/ContactMessageStore( 1243): size: 0 , 0
D/ContactMessageStore( 1243): Background delete complete
,D/SmartSyncUtils( 4584): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4584): isEpsOn(), nState = 0
D/WifiService(  904): New client listening to asynchronous messages
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4255b528
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4255b528, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4255b528, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4255b528
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4255d800 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4255d800 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1803): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1803): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1803): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1803): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1803): onScreenOff
D/PMS     (  904): acquireWL(43e03f20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1480 10028 null
,D/PMS     (  904): releaseWL(43e03f20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1382): service - mHandler: cancel location update
D/AutoSetting( 1382): service -           changes count: 0
,D/AutoSetting( 1525): service - handleMessage() stop self
,D/AutoSetting( 1525): service - onDestroy() END
,D/AutoSetting( 1525): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4297
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Killing 4297:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4297
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,D/Process (  904): killProcessQuiet, pid=3895
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3895:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3895
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{4320af78 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  904): acquireWL(43258400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c39878: PendingIntentRecord{42493880 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=131455, Int=0
,D/PMS     (  904): acquireWL(4367dd98): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43258400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(425f5820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(435988a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 904 1000 WorkSource{10106}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  904): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4608 uid=10106 gids={50106, 3003, 5012}
,D/PMS     (  904): releaseWL(4367dd98): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(425f5820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4608): LocationClient connecting
,D/PMS     (  904): acquireWL(43c8f7e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1480 10028 null
,D/PMS     (  904): releaseWL(43c8f7e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4608): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4608): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4608): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4608): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4608): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4608): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ProviderInstaller( 4608): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43749170): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,I/NewsWeather( 4608): Last usage 0, idle 1453390896s, sync interval 2592000s
,I/NewsWeather( 4608): setPeriodicSync in seconds 2592000
D/PMS     (  904): releaseWL(43749170): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4608): onConnected null
,D/PMS     (  904): acquireWL(4366a7c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1480 10028 null
,W/GCoreFlp( 1480): No location to return for getLastLocation()
,I/NewsWeather( 4608): LocationClient onConnected: location null
D/PMS     (  904): acquireWL(4373b060): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1480 10028 null
D/PMS     (  904): releaseWL(4366a7c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  904): releaseWL(4373b060): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4608): Skip sync for lookup editions
,I/NewsWeather( 4608): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4608): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1413): GoogleAccountDataService.getToken()
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1413): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1607): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1607): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  904): acquireWL(43516018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,E/NewsWeather( 4608): Unrecoverable authentication exception
E/NewsWeather( 4608): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4608): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1114): com.google.android.gms (false,0)
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(43516018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41c460b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/libc    ( 4608): [NET] getaddrinfo-,err=8
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4608): [NET] getaddrinfo-, 1
,D/libc    ( 4608): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =cf85 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4608): [NET] getaddrinfo_proxy-, success
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 15 5 12
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4608): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(42e61de8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1413 10028 null
,D/PMS     (  904): releaseWL(42e61de8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4608): Failed to syncNewsAppData
,E/NewsWeather( 4608): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43727480): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/SyncManager(  904): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 67786, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  904): releaseWL(435988a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/Process (  904): killProcessQuiet, pid=4318
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  904): Killing 4318:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/PMS     (  904): releaseWL(43727480): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1480/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(42cc6e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/PMS     (  904): releaseWL(42cc6e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  904): Recipient 4318
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,I/GAV4    ( 4608): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  904): acquireWL(42c38778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42414098: PendingIntentRecord{423caa60 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142749, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{41d0e818: PendingIntentRecord{425ce5e8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143200, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(439534f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1413/10028)
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a0f4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  904): releaseWL(42c38778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  904): acquireWL(441dc630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1413 10028 null
D/PMS     (  904): releaseWL(441dc630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1382): service - handleMessage() stop self
,D/AutoSetting( 1382): service - handleMessage() quit looper
,D/AutoSetting( 1382): service - onDestroy() END
,D/Process (  904): killProcessQuiet, pid=4369
,I/ActivityManager(  904): Killing 4369:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS,
,I/ActivityManager(  904): Recipient 4369
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  904): releaseWL(439534f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  904): acquireWL(43197850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=155437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43197850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2254/10028)
,D/PMS     (  904): acquireWL(43cf96f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c39878: PendingIntentRecord{42493880 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=161544, Int=0
,D/PMS     (  904): acquireWL(423a48f0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(4311ae70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43cf96f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): releaseWL(423a48f0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(4311ae70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43a22c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(43a22c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(438287f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{42ae4680: PendingIntentRecord{4388e1c8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=177017, Int=0
,D/PMS     (  904): releaseWL(438287f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(44298588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/BatteryService(  904): n_update end
,D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PMS     (  904): releaseWL(44298588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(44260af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=215437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44260af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43463e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(43463e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(43981370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(43981370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(4424bbd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c39878: PendingIntentRecord{42493880 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=260074, Int=0
,D/PMS     (  904): acquireWL(441b9598): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
D/PMS     (  904): releaseWL(4424bbd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43915768): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=15 [46][7][0]
,I/wpa_supplicant( 1165): Change stage from stage0 to stage1
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(44235358): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 904 1000 WorkSource{10106}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): releaseWL(441b9598): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(43915768): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(4417a7a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,I/NewsWeather( 4608): Last usage 0, idle 1453391024s, sync interval 2592000s
,I/NewsWeather( 4608): setPeriodicSync in seconds 2592000
D/PMS     (  904): releaseWL(4417a7a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4608): Skip sync for lookup editions
,I/NewsWeather( 4608): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4608): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1413): GoogleAccountDataService.getToken()
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1413): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/NewsWeather( 4608): Unrecoverable authentication exception
E/NewsWeather( 4608): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4608): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/DotMatrix( 1607): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1607): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41cb2488 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 4 2 12
,E/NewsWeather( 4608): Failed to syncNewsAppData
,E/NewsWeather( 4608): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  904): acquireWL(441ab438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1413 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(43e89e80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/PMS     (  904): releaseWL(441ab438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SyncManager(  904): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 132735, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  904): releaseWL(44235358): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  904): releaseWL(43e89e80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1480/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(431683d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(431683d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/PMS     (  904): acquireWL(425e3ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=275437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425e3ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(425da418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c39878: PendingIntentRecord{42493880 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=290133, Int=0
,D/PMS     (  904): acquireWL(425d2f48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/PMS     (  904): releaseWL(425da418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(425aa988): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(425d2f48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(425aa988): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42373710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42373710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(41c4ef60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=335437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(41c4ef60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(4247da78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  904): n_update end
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(4247da78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,W/GLSUser ( 1413): GoogleAccountDataService.getToken()
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1413): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,W/GLSActivity( 1413): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1413): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1413): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1413): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1413): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1413): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1413): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1413): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1607): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1607): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ea9ee8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4252): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4252): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4252): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4252): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4252): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4252): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4252): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4252): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 12 3 12
,D/libc    ( 4252): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4252): [NET] getaddrinfo-,err=8
D/libc    ( 4252): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4252): [NET] getaddrinfo-, 1
,D/libc    ( 4252): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b776 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4252): [NET] getaddrinfo_proxy-, success
I/global  ( 4252): call createSocket() return a new socket.
D/libc    ( 4252): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4252): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4252): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4252): [NET] getaddrinfo-,err=8
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(430dde60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=395437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(430dde60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(426030e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(426030e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(424bbbd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=455437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(424bbbd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(426b6978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(426b6978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(438a1e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(438a1e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(441e79e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c39878: PendingIntentRecord{42493880 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=515307, Int=0
,D/PMS     (  904): acquireWL(42bd84a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43466470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(441e79e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=5 [51][3][0]
,I/wpa_supplicant( 1165): Change stage from stage1 to stage0
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(43ea4828): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 904 1000 WorkSource{10106}
,D/PMS     (  904): releaseWL(42bd84a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(43466470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0],
,D/PMS     (  904): acquireWL(43b30a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=515437, Int=0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43b53cc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43b53cc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
I/NewsWeather( 4608): Last usage 0, idle 1453391280s, sync interval 2592000s
,I/NewsWeather( 4608): setPeriodicSync in seconds 2592000
D/PMS     (  904): releaseWL(43b30a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/NewsWeather( 4608): Skip sync for lookup editions
,I/NewsWeather( 4608): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4608): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1413): GoogleAccountDataService.getToken()
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1413): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1607): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1607): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4608): Unrecoverable authentication exception
E/NewsWeather( 4608): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4608): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41eb5d10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4608): [NET] getaddrinfo-,err=8
D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
I/RemoteViews.Performance( 1114): com.google.android.gms 3 12 4 12
D/libc    ( 4608): [NET] getaddrinfo-, 1
,D/libc    ( 4608): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =432b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4608): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4608): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(42016f28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1413 10028 null
,E/NewsWeather( 4608): Failed to syncNewsAppData
,E/NewsWeather( 4608): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  904): releaseWL(42016f28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(4373fcc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/SyncManager(  904): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 260629, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  904): releaseWL(43ea4828): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  904): releaseWL(4373fcc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1480/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(442ded78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): releaseWL(442ded78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/PMS     (  904): acquireWL(436a8dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(436a8dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42561bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/PMS     (  904): acquireWL(43675578): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,V/AlarmManager(  904): sending alarm PendingIntent{41c39878: PendingIntentRecord{42493880 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=545356, Int=0
,D/PMS     (  904): releaseWL(42561bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(442c3c88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43675578): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(442c3c88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  904): acquireWL(43c4d240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43c4d240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42df3308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=575437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42df3308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(436d3730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(436d3730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(423a12f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(423a12f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4661 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  904): acquireWL(43e19f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10047}
,V/AlarmManager(  904): sending alarm PendingIntent{425b9240: PendingIntentRecord{426be290 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453390986416, Int=10800000
,V/AlarmManager(  904): sending alarm PendingIntent{435e0a70: PendingIntentRecord{42693320 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453391383242, Int=0
,D/PMS     (  904): releaseWL(43e19f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1413): GoogleAccountDataService.getToken()
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4661/10047)
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1413): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1413): GoogleAccountDataService.getToken()
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1413): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4252): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4252): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1413): GoogleAccountDataService.getToken()
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1413): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4252): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4252): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4252): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/Process (  904): killProcessQuiet, pid=4399
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4399:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4399
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/PMS     (  904): acquireWL(437411f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{4254dba8: PendingIntentRecord{43df3028 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453391398400, Int=0
,D/PMS     (  904): releaseWL(437411f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4252): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  904): acquireWL(42c317f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=635437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42c317f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43511170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(43511170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43aab9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=695437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43aab9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(442416c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(442416c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(429a3b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(429a3b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  904): killProcessQuiet, pid=4418
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4418:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4418
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(431687e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=755437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(431687e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42f82ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(42f82ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43ae5208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43ae5208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42a2c310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=815437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42a2c310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43717720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43717720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43954550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=875437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43954550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43243118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43243118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/PMS     (  904): acquireWL(4323f4e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41d0c3a0: PendingIntentRecord{4242b780 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786817, Int=0
,D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,I/ActivityManager(  904): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4680 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  904): sending alarm PendingIntent{438c8c58: PendingIntentRecord{43901118 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,D/PMS     (  904): releaseWL(4323f4e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
,I/ImageRamCache( 4680): create image Cache, size: 31457280.
I/ImageRamCache( 4680): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4680): create image Cache, size: 12582912.
,I/FeedSettings( 4680): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4680): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4680): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4680): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4680): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4680): loadGridSize() with Alternative
,D/libc    ( 4680): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4680): [NET] getaddrinfo-,err=8
D/libc    ( 4680): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4680): [NET] getaddrinfo-, 1
D/libc    ( 4680): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4613 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=206
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4680): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (4680/10075)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (4680/10075)
,D/Process (  904): killProcessQuiet, pid=4386
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4386:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4386
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(4344e490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4344e490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4425a4e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=935437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4425a4e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43e4b398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{42431f20: PendingIntentRecord{42559498 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=929591, Int=0
V/AlarmManager(  904): sending alarm PendingIntent{423b37e8: PendingIntentRecord{423e6be0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453391706713, Int=900000
,D/PMS     (  904): acquireWL(43553108): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1413 10028 null
,D/PMS     (  904): releaseWL(43553108): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,W/ContextImpl( 4584): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): acquireWL(43e9cfc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1413 10028 null
,D/PMS     (  904): releaseWL(43e9cfc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  904): releaseWL(43e4b398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageService( 4584): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4584): MY_DEBUG = false
,D/PMS     (  904): acquireWL(43ae1608): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1413 10028 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/GCM     ( 1413): Message class mow
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1413/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1413/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1413/10028)
,D/PMS     (  904): releaseWL(43ae1608): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  904): acquireWL(42fc5378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1413 10028 null
,D/PMS     (  904): releaseWL(42fc5378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(424f1520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(424f1520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(429a5018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(429a5018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4208d168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=995437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4208d168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(438a8958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/SmartSyncUtils( 4584): isEpsOn(), nState = 0
V/AlarmManager(  904): sending alarm PendingIntent{4367ac88: PendingIntentRecord{442b1858 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453391777727, Int=0
,D/PMS     (  904): acquireWL(43458ca8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4584 1000 null
,D/PMS     (  904): releaseWL(438a8958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4584): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4584): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4584): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4584): SettingOnTime = 1453442400000, randomSettingOnTime = 1453441531000
,D/SmartSyncScreenOnOffTimeReceiver( 4584): SettingOffTime = 1453420800000, randomSettingOffTime = 1453424151000
,D/SmartSyncScreenOnOffTimeReceiver( 4584): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4584): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4584): bNightModeTurnOffOnce = false
D/PMS     (  904): releaseWL(43458ca8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  904): acquireWL(425f26b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(425f26b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42041468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c39878: PendingIntentRecord{42493880 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1025316, Int=0
,D/PMS     (  904): acquireWL(41e04620): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
D/PMS     (  904): releaseWL(42041468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(441d6e50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=10 [65][7][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  904): acquireWL(432e4ef0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 904 1000 WorkSource{10106}
,D/PMS     (  904): releaseWL(41e04620): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(441d6e50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43674770): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,I/NewsWeather( 4608): Last usage 0, idle 1453391789s, sync interval 2592000s
,I/NewsWeather( 4608): setPeriodicSync in seconds 2592000
D/PMS     (  904): releaseWL(43674770): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4608): Skip sync for lookup editions
,I/NewsWeather( 4608): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4608): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1413): GoogleAccountDataService.getToken()
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1413): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1413): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1607): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1607): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4608): Unrecoverable authentication exception
E/NewsWeather( 4608): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4608): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4608): [NET] getaddrinfo-,err=8
D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4608): [NET] getaddrinfo-, 1
,D/libc    ( 4608): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1,
D/libc    (  363): [NET] +++++ res_nsend xid =c6d2 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4608): [NET] getaddrinfo_proxy-, success
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41f26428 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 12 5 12
,D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4608): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(442a6e18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1413 10028 null
,D/PMS     (  904): releaseWL(442a6e18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4608): Failed to syncNewsAppData
,E/NewsWeather( 4608): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(436d3798): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/SyncManager(  904): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 515957, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  904): releaseWL(432e4ef0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): releaseWL(436d3798): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1480/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(4423bb40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/PMS     (  904): releaseWL(4423bb40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/PMS     (  904): acquireWL(43174568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43174568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4352a410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c39878: PendingIntentRecord{42493880 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1055379, Int=0
,D/PMS     (  904): acquireWL(43a4e8b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/PMS     (  904): releaseWL(4352a410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42682580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1055437, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42682580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43a82228): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/PMS     (  904): releaseWL(43a4e8b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(43a82228): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  904): acquireWL(438a8f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(438a8f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43ae1190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43ae1190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(442443d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1115437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(442443d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(44242240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44242240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(431d4b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(431d4b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4389efa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1175437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4389efa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(437488d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437488d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42d000d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/PMS     (  904): releaseWL(42d000d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(4258e238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1235437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4258e238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42be6fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/BatteryService(  904): n_update end
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetPhoneState( 1639): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/DotMatrix( 1607): [EventService] reorderNotification, total:1
D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  904): updateBatteryInfo
V/NotificationService(  904): batLight: plugged
D/PMS     (  904): releaseWL(42be6fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c80000
D/qdlights(  904): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/ContextImpl( 4584): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,D/TetherSettings( 4350): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4350): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 4350): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4350): Cust_ConnectToPC   : spcsc>false
D/        ( 4350): Cust_ConnectToPC   : IPT>true
D/        ( 4350): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4350): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4350): Index of the first 1 = -1
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
W/Settings( 4350): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4350): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4350): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4350): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4350): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4350): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4350): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  904): acquireWL(4352cfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4352cfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(425ed938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1607): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1607): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): releaseWL(425ed938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null,
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42635848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41fd5870: PendingIntentRecord{41fd5758 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1295437, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42635848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4718): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4718): ====startRecUseTime====
D/htc.customization.log.level( 4718):  is 
W/CustomizationLogLevel( 4718): Level value is invalid, use default level 2
D/CustomizationManager( 4718):  Read ACC file spent 0.113 (s)
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4718): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4718): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4718): Parsing tag category name = system
I/CustomizationCIDLoader( 4718): Parsing tag category name = application
I/CustomizationCIDLoader( 4718): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4718): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4718): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4718): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4718): Parsing tag category name = Settings
D/CustomizationManager( 4718):  Read CID file spent 0.168 (s)
D/CustomizationManager( 4718):  All configurations done spent 0.168 (s)
W/HtcNativeFlag( 4718): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4718): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4718): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4718): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4718, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  904): killProcessQuiet, pid=4512
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  904): Killing 4512:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
W/asset   (  904): Copying FileAsset 0x64127f90 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1607): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1607): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1607): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1881): Unregistering com.test.thalitest
W/GeofencerStateMachine( 1480): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/acms    ( 1881): Could not unregister removed application com.test.thalitest
D/PMS     (  904): acquireWL(43de6188): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1480 10028 null
D/PMS     (  904): releaseWL(43de6188): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Prism.ItemManager( 4680): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4680): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/VoicemailCleanupService( 1294): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/Launcher( 1269): Deferring update until onResume
D/Launcher( 1269): waitUntilResume // bindAppsRemoved
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PackageBroadcastService( 2254): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4733 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1329): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
W/Parcel  ( 1254): Reading a NULL string not supported here.
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/MultiDex( 4733): install
I/ActivityManager(  904): Delaying start of: ServiceRecord{43e2e868 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4733): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  904):   Scheme: "mms"
I/MultiDex( 4733): loading existing secondary dex files
I/MultiDex( 4733): load found 1 secondary dex files
I/MultiDex( 4733): install done
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2254): CP2 sync disabled
D/PMS     (  904): acquireWL(4240a440): PARTIAL_WAKE_LOCK  Icing 0x1 2254 10028 null
I/Icing   ( 2254): doRemovePackageData com.test.thalitest
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2254, uid=10028, userID:0
I/ProviderInstaller( 4733): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  904): releaseWL(4240a440): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4751 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4751): install
I/MultiDex( 4751): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4751): loading existing secondary dex files
I/MultiDex( 4751): load found 1 secondary dex files
I/MultiDex( 4751): install done
I/ActivityManager(  904): Resuming delayed broadcast
I/ProviderInstaller( 4751): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1382): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1382): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
E/SQLiteDatabase( 4733): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4733): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4733): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4733): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4733): threadid=12: thread exiting with uncaught exception (group=0x416c3e30)
I/IcingCorporaProvider( 2942): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/AndroidRuntime( 4733): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4733): Process: com.google.android.gms.drive, PID: 4733
E/AndroidRuntime( 4733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4733): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4733): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4733): 	at ctn.run(SourceFile:985)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4772 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/Process ( 4733): killProcess, pid=4733
D/Process ( 4733): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop135.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
E/SQLiteLog( 2942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2942): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x644e37f8
W/dalvikvm( 2942): threadid=15: thread exiting with uncaught exception (group=0x416c3e30)
E/AndroidRuntime( 2942): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2942): Process: com.google.android.googlequicksearchbox:search, PID: 2942
E/AndroidRuntime( 2942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2942): 	at cid.d(PG:186)
E/AndroidRuntime( 2942): 	at clo.g(PG:594)
E/AndroidRuntime( 2942): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2942): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2942): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2942): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2942): 	at clr.tL(PG:827)
E/AndroidRuntime( 2942): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2942): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2942): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PackageManager(  904): Unable to load service info ResolveInfo{4236da38 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2942): killProcess, pid=2942
D/Process ( 2942): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
I/ActivityManager(  904): Recipient 4733
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4733) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  904): Recipient 2942
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 2942) has died.
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 2942): Died!
D/WifiService(  904): Client connection lost with reason: 4
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
W/AtomicFile(  904): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  904): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4772): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4772): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4772): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4772): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4772): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4772): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4772): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4772): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4772): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4772): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4772): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4772): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4772): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4772): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4772): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4772): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4772): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4772): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4772): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4772): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4772): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4772): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4772): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4772): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4772): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4772): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4772): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4772): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4772): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4772): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4772): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4772): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4772): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4772): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4772): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4772): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4772): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4772): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4772): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4772): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4772): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4772): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4772): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4772): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4772): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4772): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4772): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4772): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4772): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4772): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4772): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4772): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4772): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4772): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4772): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4772): threadid=11: thread exiting with uncaught exception (group=0x416c3e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4772): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4772): Process: com.google.android.apps.docs, PID: 4772
E/AndroidRuntime( 4772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4772): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4772): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4772): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4772): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4772): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
D/Process ( 4772): killProcess, pid=4772
D/Process ( 4772): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4789 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Recipient 4772
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  904): killProcessQuiet, pid=4442
I/ActivityManager(  904): Killing 4442:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4772) has died.
I/ActivityManager(  904): Recipient 4442
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4789): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4789): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4789): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4789): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4789): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4789): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4789): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4789): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4789): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4789): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4789): threadid=10: thread exiting with uncaught exception (group=0x416c3e30)
E/ActivityManager(  904): App crashed! Process: com.android.keychain
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4802 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4789): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4789): Process: com.android.keychain, PID: 4789
E/AndroidRuntime( 4789): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4789): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4789): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4789): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4789): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4789): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4789): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4789): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4789): killProcess, pid=4789
D/Process ( 4789): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453392079678.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
I/ActivityManager(  904): Recipient 4789
I/ActivityManager(  904): Process com.android.keychain (pid 4789) has died.
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10616ms
I/Prism.ItemManager( 4680): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4680): loadItems() com.htc.launcher.pageview.WidgetManager@41b5e6e0 +
I/Prism.WidgetManager( 4680): onLoadItems() +
D/AppTag  ( 4802): getInstance(Context context)
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b86e78 +
I/Prism.WidgetManager( 1269): onLoadItems() +
D/AppTag  ( 4802): getInstance(Context context)
D/AppTag  ( 4802): onCreate()
D/PMS     (  904): acquireWL(4234a860): PARTIAL_WAKE_LOCK  AsyncService 0x1 4214 10160 null
D/PMS     (  904): releaseWL(4234a860): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4820 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4820): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4820 dbg=false s=true
I/DeviceManagement( 4820): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4820): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4820): WorkflowService: Starting workflow service
I/DeviceManagement( 4820): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b27f08] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4820): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4820): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4820): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4820): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  904): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4834 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4820): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4820): SessionStateController: Checking invariants...
D/Documents( 4834): Loading roots for com.android.providers.downloads.documents
D/Documents( 4834): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4834): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4834): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4834): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4834): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4834): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4834): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4834): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4834): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4834): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4834): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4834): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4834): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4834): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4834): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4834): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4834): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4834): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4834): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4834): threadid=1: thread exiting with uncaught exception (group=0x416c3e30)
E/AndroidRuntime( 4834): FATAL EXCEPTION: main
E/AndroidRuntime( 4834): Process: com.android.documentsui, PID: 4834
E/AndroidRuntime( 4834): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4834): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4834): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4834): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4834): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4834): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4834): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4834): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4834): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4834): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4834): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4834): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4834): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4834): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4834): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4834): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4834): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4834): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4834): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4834): 	... 10 more
I/ActivityManager(  904): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4848 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process (  904): killProcessQuiet, pid=4460
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/ActivityManager(  904): App crashed! Process: com.android.documentsui
I/ActivityManager(  904): Killing 4460:com.htc.calendar/u0a13 (adj 15): empty #17
D/GCM     ( 1413): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453392079980.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
D/Process ( 4834): killProcess, pid=4834
D/Process ( 4834): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Recipient 4460
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Recipient 4834
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.documentsui (pid 4834) has died.
D/GCM     ( 1413): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ExternalStorage( 4848): After updating volumes, found 1 active roots
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4864 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4820): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4820): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4820): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4820): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4820): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4820): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4820): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4820): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4820): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 4820): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4820): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4820): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4820): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4820): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4820): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4820): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4820): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4820): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 4820): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4820): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4820): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4820): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4820): 	at com.htc.cs.d
```
