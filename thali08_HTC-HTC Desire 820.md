#### Test 561517803567b2a_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
--------- beginning of /dev/log/system
I/ActivityManager(  911): Waited long enough for: ServiceRecord{42b83640 u0 com.htc.htclocationservice/.AutoSettingService}
D/WIFI_ICON( 1118): WifiActivity: 1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  911): acquireWL(43ddf098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(43ddf098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 4574): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4574): ====startRecUseTime====
D/htc.customization.log.level( 4574):  is 
W/CustomizationLogLevel( 4574): Level value is invalid, use default level 2
D/CustomizationManager( 4574):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4574): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4574): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4574): Parsing tag category name = system
I/CustomizationCIDLoader( 4574): Parsing tag category name = application
I/CustomizationCIDLoader( 4574): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4574): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4574): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4574): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4574): Parsing tag category name = Settings
D/CustomizationManager( 4574):  Read CID file spent 0.100 (s)
D/CustomizationManager( 4574):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 4574): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4574): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4574): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4574): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4574
D/PMS     (  911): acquireHCC(43e234b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(44210488): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
W/asset   (  911): Copying FileAsset 0x62e78250 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1128308984
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ea96c8
I/SocialFeedProvider( 1273): +onPause
D/PMS     (  911): acquireWL(4349fd60): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  911): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4586 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4586): Copying FileAsset 0x5c7cb428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1273): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4586): Binding Chromium to main looper Looper (main, tid 1) {41b4f5a0}
I/LibraryLoader( 4586): Expected native library version number "",actual native library version number ""
I/chromium( 4586): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4586): Initializing chromium process, renderers=0
D/PMS     (  911): acquireWL(42f0b280): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): acquireWL(4308c418): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  911): releaseWL(4308c418): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4478e348:true
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4586): 1102467032: getState(). Returning 12
,I/Adreno-EGL( 4586): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4586): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4586): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4586): Local Branch: 
I/Adreno-EGL( 4586): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4586): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4586):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4586): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4586): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4586): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4586): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4586): CordovaWebView is running on device made by: HTC
,W/AwContents( 4586): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  911): Disable input method client, pid=1273
,I/InputMethodManagerService(  911): Enable input method client, pid=4586
W/ResourceType( 4586): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4586): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b966c8, mServedView=org.apache.cordova.engine.SystemWebView{41b5c2f0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  911): Displayed com.test.thalitest/.MainActivity: +409ms
W/AwContents( 4586): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  911): releaseWL(4349fd60): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4586): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4586): JniHelper::setJavaVM(0x41622048), pthread_self() = 1663366856
,I/chromium( 4586): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 11.997MB for 63974-byte allocation
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 12.053MB for 95956-byte allocation
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 12.137MB for 143930-byte allocation
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 12.253MB for 215890-byte allocation
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 12.404MB for 323830-byte allocation
,I/ActivityManager(  911): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4634 uid=10077 gids={50077}
,D/PMS     (  911): acquireWL(43e62ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10077}
,V/AlarmManager(  911): sending alarm PendingIntent{42493c78: PendingIntentRecord{424936b0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452855647006, Int=60000
,D/PMS     (  911): releaseWL(43e62ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4634): SMSBackupAgentService started
,D/SMSBackup( 4634): Checking restore status
D/SMSBackup( 4634): Restore complete
,D/SMSBackup( 4634): cancelCheckAlarm
,D/SMSBackup( 4634): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  911): killProcessQuiet, pid=4374
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4374:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4374
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 13.082MB for 728606-byte allocation
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 13.673MB for 1092904-byte allocation
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 14.593MB for 1639352-byte allocation
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 15.840MB for 2459024-byte allocation
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
,D/PMS     (  911): releaseHCC(43e234b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  911): releaseHCC(44210488): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4586): Grow heap (frag case) to 18.025MB for 3688532-byte allocation
,W/jxcore-log( 4586): Initializing JXcore engine
,W/jxcore-log( 4586): JXcore engine is ready
,W/jxcore-log( 4586): Starting JXcore engine
,W/jxcore-log( 4586): Platform android
W/jxcore-log( 4586): 
,W/jxcore-log( 4586): Process ARCH arm
W/jxcore-log( 4586): 
,D/PMS     (  911): releaseWL(42f0b280): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4586): JXcore Cordova bridge is ready!
I/jxcore-log( 4586): 
,W/jxcore-log( 4586): JXcore engine is started
,E/jxcore  ( 4586): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4586): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4586): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4586): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  911): acquireWL(42e56c20): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
,I/FeedHostManager( 1273): [onResume]
,I/FeedProviderManager( 1273): onResume
I/SocialFeedProvider( 1273): +onResume
I/SocialFeedProvider( 1273): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1273): -onResume
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.launcher (1273/10075)
,I/InputMethodManagerService(  911): Disable input method client, pid=4586
,I/InputMethodManagerService(  911): Enable input method client, pid=1273
W/IInputConnectionWrapper( 4586): reportFullscreenMode on inactive InputConnection
,D/PMS     (  911): releaseWL(42e56c20): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  911): killProcessQuiet, pid=4396
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  911): Killing 4396:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,E/libEGL  ( 4586): call to OpenGL ES API with no current context (logged once per thread)
I/ActivityManager(  911): Recipient 4396
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  911): Client connection lost with reason: 4
,I/SensorManager(  911): mEventCount = 1200
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): [ScoreAP] + current TXpacket:244, mTXpacketCount:228, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  911): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiDataStallTracker(  911): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  911): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  911): acquireWL(423ec380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,D/WifiDataStallTracker(  911): updateDataStallInfo: mDataStallTxRxSum={txSum=201 rxSum=186} preTxRxSum={txSum=187 rxSum=176}
D/WifiDataStallTracker(  911): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  911): onDataStallAlarm: tag=20090 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20091 delay=15s
V/AlarmManager(  911): sending alarm PendingIntent{42326d20: PendingIntentRecord{42533840 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=108686, Int=0
D/PMS     (  911): releaseWL(423ec380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42129988
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
W/PMS     (  911): mWirelessDisplayManager is null
W/BatSI   (  911): Couldn't get kernel wake lock stats
D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42129988, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42325358
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@42185f60
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:,
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0,
V/LightsService(  911): setLight #0: color=#0
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC <<
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 413ms
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/NfcService( 1258): ScreenObserver: OFF
,D/NfcService( 1258): applyRouting - 0
I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/HABCtrl (  911): TPE algorithm. remove timeout.
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
D/PMS     (  911): OOBE c monitor 11
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
I/InputMethodManagerService(  911): Disable input method client, pid=1273
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4265b398)
,D/NfcService( 1258): applyRouting -2
,D/PMN     (  911): wakingUp
D/PMS     (  911): acquireWL(4267b410): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  911): acquireWL(4395c6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
D/PMS     (  911): releaseWL(4267b410): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/BatteryService(  911): n_update end
I/WindowManager(  911): No lock screen! windowToken=null
D/PMN     (  911): onScreenOn
D/PMS     (  911): releaseWL(4395c6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20092 delay=15s
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WIFI_ICON( 1118): WifiActivity: 0
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/HtcPowerSaver(  911): updateBatteryInfo
D/MtpService( 2463): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2463): [MTP][onReceive]-
D/NfcService( 1258): applyRouting - 0,
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/NfcService( 1258): applyRouting -2
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): acquireWL(434b3ea0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:On
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  911):    returned true
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(434b3ea0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/ClockThread( 1118): stop update clock
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  371): ParamSet string: screen_state=on
I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4655 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  911): updateScreenOn: false
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/ContextImpl( 4655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1817): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1817): onScreenOn: 1452855656032
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1817): onScreenOn: 1452855656032
D/PMS     (  911): acquireWL(442a76b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1444 10028 null
D/PMS     (  911): releaseWL(442a76b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42325358
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42325358, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@42185f60
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  911): goingToSleep
D/PMS     (  911): acquireWL(42574568): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
,D/PMS     (  911): acquireWL(42e25cf8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4655 1000 null
,D/PMS     (  911): releaseWL(42e25cf8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4655): isEpsOn(), nState = 0
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
,I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ea96c8
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20092 mDataStallAlarmIntent=PendingIntent{426b21f0: PendingIntentRecord{42533840 android broadcastIntent}}
I/SocialFeedProvider( 1273): +onPause
,I/SocialFeedProvider( 1273): -onPause
D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
I/AlarmManager(  911): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
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
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): acquireWL(4288f790): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/PMS     (  911): releaseWL(42574568): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  911): updateScreenOn: false
,D/ContactMessageStore( 1247): start background delete task...
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1405): receiver - intent: android.intent.action.USER_PRESENT
D/SmartSyncUtils( 4655): getMobilePolicyEnabled, result = true
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  911): releaseWL(4288f790): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/TetherSettings( 3845): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3845): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3845): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3845): Cust_ConnectToPC   : spcsc>false
D/        ( 3845): Cust_ConnectToPC   : IPT>true
D/        ( 3845): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3845): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3845): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3845): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3845): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1405): service - onCreate()
,I/PSReceiver( 3845): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
I/SmartNS_PSService( 3845): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
W/Settings( 3845): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3845):  defaultType:0
,W/ContextImpl( 3845): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1405): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  911): request 424b4830 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
W/ContextImpl( 4655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4655): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4655): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4655): isEpsOn(), nState = 0
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] getTotalRam: 1873 Mb
D/WifiService(  911): New client listening to asynchronous messages
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42185f60
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1817): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1817): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1817): disableBatteryAlarm
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  911): acquireWL(43234080): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1444 10028 null
,D/PMS     (  911): releaseWL(43234080): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1817): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1817): onScreenOff
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42185f60, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42185f60, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42185f60
,E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41da4d10 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41da4d10 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  911): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  911): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  911): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  911): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  911): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  911): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  911): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  911): 	at dalvik.system.NativeStart.main(Native Method)
,D/AutoSetting( 1503): service - handleMessage() stop self
,D/AutoSetting( 1503): service - onDestroy() END
,D/AutoSetting( 1503): service - handleMessage() quit looper
D/Process (  911): killProcessQuiet, pid=4297
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4297:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4297
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(442f6c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=117442, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(442f6c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  911): killProcessQuiet, pid=3955
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3955:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3955
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1405): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1405): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1405): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{433f4860 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  911): acquireWL(4393fd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  911): releaseWL(4393fd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(425e7fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41d10c40: PendingIntentRecord{424eb900 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=133229, Int=0
,D/PMS     (  911): acquireWL(43a48408): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
D/PMS     (  911): releaseWL(425e7fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(43d75af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  911): acquireWL(432be060): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 911 1000 WorkSource{10106}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  911): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4683 uid=10106 gids={50106, 3003, 5012}
,D/PMS     (  911): releaseWL(43a48408): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  911): releaseWL(43d75af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4683): LocationClient connecting
,D/PMS     (  911): acquireWL(425b4960): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
,D/PMS     (  911): releaseWL(425b4960): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4683): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4683): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4683): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4683): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4683): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4683): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ProviderInstaller( 4683): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(425d71a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,I/NewsWeather( 4683): Last usage 0, idle 1452855676s, sync interval 2592000s
,I/NewsWeather( 4683): setPeriodicSync in seconds 2592000
D/PMS     (  911): releaseWL(425d71a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4683): onConnected null
,D/PMS     (  911): acquireWL(43d84478): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
,W/GCoreFlp( 1444): No location to return for getLastLocation()
,I/NewsWeather( 4683): LocationClient onConnected: location null
D/PMS     (  911): acquireWL(442efaa8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
D/PMS     (  911): releaseWL(43d84478): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  911): releaseWL(442efaa8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4683): Skip sync for lookup editions
,I/NewsWeather( 4683): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4683): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1374): GoogleAccountDataService.getToken()
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1118): com.google.android.gms (false,0)
D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41c9d3a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4683): Unrecoverable authentication exception
E/NewsWeather( 4683): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4683): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4683): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4683): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1118): com.google.android.gms 3 20 7 12
,D/libc    ( 4683): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4683): [NET] getaddrinfo-,err=8
D/libc    ( 4683): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4683): [NET] getaddrinfo-, 1
,D/libc    ( 4683): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ea15 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4683): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4683): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4683): [NET] getaddrinfo-,err=8
,D/PMS     (  911): acquireWL(43349528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,D/PMS     (  911): releaseWL(43349528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4683): Failed to syncNewsAppData
,E/NewsWeather( 4683): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(43956608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/SyncManager(  911): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 68416, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/Process (  911): killProcessQuiet, pid=4446
D/PMS     (  911): releaseWL(432be060): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,I/ActivityManager(  911): Killing 4446:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1444/10028)
D/PMS     (  911): releaseWL(43956608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4446
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(43e51310): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(43e51310): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,I/GAV4    ( 4683): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  911): acquireWL(4320ed10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42524318: PendingIntentRecord{425242b8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141676, Int=0
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(434b33d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(4320ed10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =85c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo_proxy-, success
I/global  (  911): call createSocket() return a new socket.
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  911): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  911): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  911): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  911):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  911): acquireWL(4392ef68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10028}
,V/AlarmManager(  911): sending alarm PendingIntent{424ab8d8: PendingIntentRecord{425fac78 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143664, Int=0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1374/10028)
,D/PMS     (  911): releaseWL(4392ef68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  911): acquireWL(43cf1dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,D/PMS     (  911): releaseWL(43cf1dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1405): service - handleMessage() stop self
,D/AutoSetting( 1405): service - handleMessage() quit looper
,D/AutoSetting( 1405): service - onDestroy() END
D/Process (  911): killProcessQuiet, pid=4464
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4464:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4464
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): releaseWL(434b33d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  911): acquireWL(43942e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41d10c40: PendingIntentRecord{424eb900 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=163307, Int=0
,D/PMS     (  911): acquireWL(4399b020): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
,D/PMS     (  911): releaseWL(43942e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(42bdf5f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(4399b020): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  911): releaseWL(42bdf5f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(433caec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(433caec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4471be30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=177443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4471be30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(426da868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10026}
,V/AlarmManager(  911): sending alarm PendingIntent{438bcaf8: PendingIntentRecord{43990ab0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=177484, Int=0
,D/PMS     (  911): releaseWL(426da868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(438af5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(438af5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(4250e0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=237443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4250e0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(42e1bf50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42e1bf50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(43ac8ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41d10c40: PendingIntentRecord{424eb900 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=264020, Int=0
,D/PMS     (  911): acquireWL(42c556c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
,D/PMS     (  911): releaseWL(43ac8ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): acquireWL(42703660): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=13 [45][6][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): acquireWL(4429cc28): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 911 1000 WorkSource{10106}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(42c556c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  911): releaseWL(42703660): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000),
,D/PMS     (  911): acquireWL(42576828): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(42576828): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4683): Last usage 0, idle 1452855806s, sync interval 2592000s
,I/NewsWeather( 4683): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4683): Skip sync for lookup editions
,I/NewsWeather( 4683): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4683): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1374): GoogleAccountDataService.getToken()
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41e67028 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4683): Unrecoverable authentication exception
E/NewsWeather( 4683): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4683): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4683): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4683): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1118): com.google.android.gms 2 12 4 12
,D/PMS     (  911): acquireWL(4470afe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,E/NewsWeather( 4683): Failed to syncNewsAppData
,E/NewsWeather( 4683): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/PMS     (  911): releaseWL(4470afe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/PMS     (  911): acquireWL(442bb3d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/SyncManager(  911): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 134398, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  911): releaseWL(4429cc28): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1444/10028)
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  911): releaseWL(442bb3d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4269d8b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(4269d8b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(4250d5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41d10c40: PendingIntentRecord{424eb900 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=294068, Int=0
,D/PMS     (  911): acquireWL(424f7f28): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
,D/PMS     (  911): releaseWL(4250d5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(424d6018): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(424f7f28): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  911): releaseWL(424d6018): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  911): acquireWL(423e6588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=297443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(423e6588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  911): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4716 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  911): acquireWL(425fe060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10047}
V/AlarmManager(  911): sending alarm PendingIntent{423e9538: PendingIntentRecord{422a5968 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452855763524, Int=10800000
,V/AlarmManager(  911): sending alarm PendingIntent{438aef20: PendingIntentRecord{425654f8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452855796829, Int=1800000
,V/AlarmManager(  911): sending alarm PendingIntent{425ffed8: PendingIntentRecord{42284bb8 com.htc.cs.dm startService}}, i=com.htc.cs.action.EXECUTE_WORKFLOW, t=1, cnt=1, w=1452855846259, Int=0
,I/DeviceManagement( 4433): WorkflowService: Starting workflow service
D/PMS     (  911): acquireWL(42244328): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1226 10028 null
,D/PMS     (  911): releaseWL(425fe060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
I/DeviceManagement( 4433): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@41d1a700] args=[Bundle[mParcelledData.dataSize=60]]
I/DeviceManagement( 4433): UpdateWorkflow: ==================================================
I/DeviceManagement( 4433): UpdateWorkflow: TTL update...
,I/DeviceManagement( 4433): UpdateWorkflow: ==================================================
,I/DeviceManagement( 4433): SessionStateController: Checking invariants...
D/PMS     (  911): acquireWL(42381640): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1226 10028 null
D/PMS     (  911): releaseWL(42244328): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1226): Aggregate from 1452855635052 (log), 1452853996767 (data)
,I/DeviceManagement( 4433): BackgroundController: Invariants are unchanged.
I/DeviceManagement( 4433): Perf: *** Cache update - start...
,I/DeviceManagement( 4433): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 4433): EnabledAppController: *** Updating enabled app database...
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.aurora (4716/10047)
I/DeviceManagement( 4433): Perf: *** Enabled app cache update - complete: 2 ms
I/DeviceManagement( 4433): Perf: *** Config cache update - start...
I/DeviceManagement( 4433): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4433): ConfigCacheController: *** Updating stale config cache entries...
,D/PMS     (  911): releaseWL(42381640): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/dalvikvm( 4433): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
,W/dalvikvm( 4433): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 4433): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,W/System.err( 4433): Starting the internal HTTP client
,I/DeviceManagement( 4433): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
,I/DeviceManagement( 4433): DeviceClientResource: Active network...
I/DeviceManagement( 4433):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.cs.dm (4433/10098)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.cs.dm (4433/10098)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.cs.dm (4433/10098)
D/BuildInfo( 4433): Created new instance: com.htc.cs.lib.hms.BuildInfo@41e30f58
I/DeviceManagement( 4433): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [7][0][0]
,D/libc    ( 4433): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4433): [NET] getaddrinfo-, 1
,D/libc    ( 4433): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4433): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4433): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4433): [NET] getaddrinfo-,err=8
D/libc    ( 4433): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4433): [NET] getaddrinfo-, 1
,D/libc    ( 4433): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =69f0 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=204
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4433): [NET] getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/DeviceManagement( 4433): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4433): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4433): DeviceClientResourceController: handleDirectives: []
W/dalvikvm( 4433): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 4433): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 4433): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4433): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 4433): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 4433): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4433): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4433): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4433): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4433): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 4433): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4433): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
,W/dalvikvm( 4433): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4433): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
,W/dalvikvm( 4433): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 4433): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 4433): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,I/System.out( 4433): isCompatible false
I/System.out( 4433): createObjectMapper
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
,I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
,I/System.out( 4433): isCompatible false,
,I/DeviceManagement( 4433): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 4433): DeviceClientResource: Active network...
I/DeviceManagement( 4433):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.cs.dm (4433/10098)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.cs.dm (4433/10098)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=6 [15][1][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.cs.dm (4433/10098)
,D/libc    ( 4433): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4433): [NET] getaddrinfo-, 1
,D/libc    ( 4433): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4433): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4433): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4433): [NET] getaddrinfo-,err=8
D/libc    ( 4433): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4433): [NET] getaddrinfo-, 1
D/libc    ( 4433): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4095 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
,D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4433): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 4433): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4433): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4433): DeviceClientResourceController: handleDirectives: []
I/System.out( 4433): isCompatible false
,I/System.out( 4433): createObjectMapper
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false,
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
,I/System.out( 4433): isCompatible false
,I/DeviceManagement( 4433): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,I/DeviceManagement( 4433): DeviceClientResource: Active network...
I/DeviceManagement( 4433):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.cs.dm (4433/10098)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.cs.dm (4433/10098)
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [9][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.cs.dm (4433/10098)
,D/libc    ( 4433): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4433): [NET] getaddrinfo-, 1
,D/libc    ( 4433): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4433): [NET] getaddrinfo_proxy-, success
D/libc    ( 4433): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4433): [NET] getaddrinfo-,err=8
D/libc    ( 4433): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4433): [NET] getaddrinfo-, 1
D/libc    ( 4433): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5051 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4433): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 4433): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4433): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4433): DeviceClientResourceController: handleDirectives: []
I/System.out( 4433): isCompatible false
I/System.out( 4433): createObjectMapper
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
I/System.out( 4433): isCompatible false
,I/System.out( 4433): isCompatible false
,I/DeviceManagement( 4433): ConfigCacheController: *** Update config cache: updating 3 entries...
,I/DeviceManagement( 4433): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 4433): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 4433): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 4433): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4433): AlarmController: Scheduling TTL alarm for: 2016.01.16 at 12:04:08.296 CET (due to: com.htc.launcher)
,I/DeviceManagement( 4433): Perf: *** Config cache update - complete: 2072 ms
I/DeviceManagement( 4433): Perf: *** Cache update - complete: 2076 ms
,I/DeviceManagement( 4433): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@41d1a700]
,I/DeviceManagement( 4433): WorkflowService: Stopping workflow service
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4433, uid=10098, userID:0
,D/Process (  911): killProcessQuiet, pid=4487
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4487:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4487
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(426e8b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(426e8b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(426c5550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=357443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426c5550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1374): GoogleAccountDataService.getToken()
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1374): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1374): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1374): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1374): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1374): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1374): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1374): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,E/PlayEventLogger( 4149): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4149): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4149): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4149): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4149): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4149): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4149): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4149): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41ecf650 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 1 13 4 12
,D/libc    ( 4149): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4149): [NET] getaddrinfo-,err=8
D/libc    ( 4149): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4149): [NET] getaddrinfo-, 1
,D/libc    ( 4149): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6f67 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4149): [NET] getaddrinfo_proxy-, success
I/global  ( 4149): call createSocket() return a new socket.
D/libc    ( 4149): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4149): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4149): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4149): [NET] getaddrinfo-,err=8
,D/PMS     (  911): acquireWL(4475d370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4475d370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(434ed180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=417442, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(434ed180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(423f6cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(423f6cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(43322d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(43322d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(426e05d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=477443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426e05d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(442dd7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(442dd7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(425ca940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41d10c40: PendingIntentRecord{424eb900 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=523700, Int=0
,D/PMS     (  911): acquireWL(42ea5078): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
D/PMS     (  911): releaseWL(425ca940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(425e1e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=4 [41][2][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  911): acquireWL(426d1ea8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 911 1000 WorkSource{10106}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(42ea5078): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  911): releaseWL(425e1e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(42621140): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,I/NewsWeather( 4683): Last usage 0, idle 1452856066s, sync interval 2592000s
,I/NewsWeather( 4683): setPeriodicSync in seconds 2592000
D/PMS     (  911): releaseWL(42621140): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4683): Skip sync for lookup editions
,I/NewsWeather( 4683): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4683): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1374): GoogleAccountDataService.getToken()
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4683): Unrecoverable authentication exception
E/NewsWeather( 4683): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4683): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4683): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4683): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41ef7340 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4683): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4683): [NET] getaddrinfo-,err=8
D/libc    ( 4683): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4683): [NET] getaddrinfo-, 1
,D/libc    ( 4683): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
I/RemoteViews.Performance( 1118): com.google.android.gms 2 13 5 12
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ea70 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4683): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4683): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4683): [NET] getaddrinfo-,err=8
,E/NewsWeather( 4683): Failed to syncNewsAppData
,E/NewsWeather( 4683): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  911): acquireWL(42beaad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
D/PMS     (  911): releaseWL(42beaad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(434f6560): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/SyncManager(  911): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 264447, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  911): releaseWL(426d1ea8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  911): releaseWL(434f6560): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1444/10028)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(42a03938): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(42a03938): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/PMS     (  911): acquireWL(426d7220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(426d7220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43e9d630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=537442, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43e9d630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(447b3dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(447b3dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4394e198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41d10c40: PendingIntentRecord{424eb900 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=553769, Int=0
,D/PMS     (  911): acquireWL(43dc9cc0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
D/PMS     (  911): releaseWL(4394e198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(44259dd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(43dc9cc0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  911): releaseWL(44259dd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  911): acquireWL(43349878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): releaseWL(43349878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(4394a7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=597443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4394a7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43335ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43335ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1247): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1247): mDeleteTask = null, bDeleting = false
,D/ContactMessageStore( 1247): start background delete task...
D/AccFlag ( 1247): sku_id=99
,D/ContactMessageStore( 1247): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,D/PMS     (  911): acquireWL(42f794f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42f794f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(434f4008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=657443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(434f4008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(426e96b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(426e96b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(44233a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=717443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44233a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43409868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43409868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  911): killProcessQuiet, pid=4185
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4185:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 4185
,D/PMS     (  911): acquireWL(42584b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(42584b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43a3d990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=777443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43a3d990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43e61ab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43e61ab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(426e9c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=837443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426e9c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42b47b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): releaseWL(42b47b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42eb3878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42eb3878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(441c4310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=897443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(441c4310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43234178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43234178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42576af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=957443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42576af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42676cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42676cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(438a7e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  911): sending alarm PendingIntent{41df3568: PendingIntentRecord{42483820 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784036, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{41ef0c80: PendingIntentRecord{425faa38 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928506, Int=0
,D/PMS     (  911): acquireWL(42f50da0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1374 10028 null
,V/AlarmManager(  911): sending alarm PendingIntent{423d7590: PendingIntentRecord{4261c7d0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452856483753, Int=900000
,D/PMS     (  911): releaseWL(42f50da0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,V/AlarmManager(  911): sending alarm PendingIntent{434f1b78: PendingIntentRecord{42602518 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452856556200, Int=0
,D/PMS     (  911): acquireWL(43489ea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,D/ConnectivityService(  911): Done.
D/ConnectivityService(  911): Setting timer for 720seconds
,W/ContextImpl( 4655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  911): releaseWL(43489ea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4655): call getInstance()
,D/SmartSyncUtils( 4655): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4655): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4655): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4655): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/PMS     (  911): acquireWL(42504db0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4655 1000 null
,D/PMS     (  911): releaseWL(438a7e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4655): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4655): SettingOnTime = 1452924000000, randomSettingOnTime = 1452920557000
,D/SmartSyncScreenOnOffTimeReceiver( 4655): SettingOffTime = 1452902400000, randomSettingOffTime = 1452908184000
D/PMS     (  911): acquireWL(42e90208): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10028 null
,D/SmartSyncScreenOnOffTimeReceiver( 4655): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4655): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4655): bNightModeTurnOffOnce = false
W/BatSI   (  911): Couldn't get kernel wake lock stats
D/PMS     (  911): releaseWL(42504db0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GCM     ( 1374): Message class mow
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1374/10028)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1374/10028)
D/PMS     (  911): releaseWL(42e90208): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  911): acquireWL(434a2640): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
D/PMS     (  911): releaseWL(434a2640): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/PMS     (  911): acquireWL(43433a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1017442, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43433a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42e1d180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42e1d180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4261e7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41d10c40: PendingIntentRecord{424eb900 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1042809, Int=0
,D/PMS     (  911): acquireWL(425e6388): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
,D/PMS     (  911): releaseWL(4261e7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): acquireWL(425647c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=3 [65][2][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): acquireWL(426207a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 911 1000 WorkSource{10106}
D/PMS     (  911): releaseWL(425e6388): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  911): releaseWL(425647c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(4245f5a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(4245f5a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
I/NewsWeather( 4683): Last usage 0, idle 1452856585s, sync interval 2592000s
I/NewsWeather( 4683): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4683): Skip sync for lookup editions
,I/NewsWeather( 4683): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4683): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1374): GoogleAccountDataService.getToken()
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4683): Unrecoverable authentication exception
E/NewsWeather( 4683): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4683): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4683): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4683): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4683): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41f25338 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4683): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4683): [NET] getaddrinfo-,err=8
D/libc    ( 4683): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4683): [NET] getaddrinfo-, 1
,D/libc    ( 4683): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =631c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/RemoteViews.Performance( 1118): com.google.android.gms 5 11 4 12
,D/libc    ( 4683): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4683): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4683): [NET] getaddrinfo-,err=8
,E/NewsWeather( 4683): Failed to syncNewsAppData
,E/NewsWeather( 4683): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  911): acquireWL(42f4ccf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(446ab7e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/SyncManager(  911): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 524297, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  911): releaseWL(42f4ccf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  911): releaseWL(426207a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1444/10028)
D/PMS     (  911): releaseWL(446ab7e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(42466458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(42466458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/PMS     (  911): acquireWL(42703760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,D/PMS     (  911): acquireWL(43705ef8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
,V/AlarmManager(  911): sending alarm PendingIntent{41d10c40: PendingIntentRecord{424eb900 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1072948, Int=0
,D/PMS     (  911): releaseWL(42703760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(441b7cd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(43705ef8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  911): releaseWL(441b7cd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  911): acquireWL(42f0a428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1077442, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42f0a428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42691418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42691418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4473eb58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(4473eb58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43353878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1137443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43353878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(425dc578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(425dc578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  911): updateBatteryInfo
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 4655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,D/TetherSettings( 3845): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3845): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3845): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3845): Cust_ConnectToPC   : spcsc>false
D/        ( 3845): Cust_ConnectToPC   : IPT>true
D/        ( 3845): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3845): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3845): Index of the first 1 = 3
W/Settings( 3845): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3845): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3845): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3845): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3845): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3845): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,D/SmartNS_Utility( 3845): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(426e2b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(426e2b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(431df1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1197443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(431df1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42bd96d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(42bd96d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(439d8760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): onReceive BATTERY_CHANGED
,D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  911): releaseWL(439d8760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(4422f878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1257443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4422f878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(434ff0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/PMS     (  911): releaseWL(434ff0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42f38520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): releaseWL(42f38520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(4472f690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1317443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4472f690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43831fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): releaseWL(43831fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus,
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(448582b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(448582b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
,D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(426b5278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1377443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426b5278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43127558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43127558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
,D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(439701a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(439701a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43ccc470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1437443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43ccc470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42697800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(42697800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(434680e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1497443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(434680e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(44275b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44275b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(442169d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(442169d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(438bb2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1557443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(438bb2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(439bfcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
,D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(439bfcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(434eb050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): releaseWL(434eb050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(442edb18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1617443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(442edb18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42e68fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42e68fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42624118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(42624118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42f23ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1677443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42f23ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43aa2350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43aa2350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(426b5c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1737443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426b5c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43e11368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43e11368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  911): updateBatteryInfo
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(4351d7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(4351d7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43351e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1797443, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43351e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/PMS     (  911): acquireWL(42b4ee48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(42b4ee48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43ab8850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43ab8850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(42eac1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c34490: PendingIntentRecord{41c13700 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1857442, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  911): Prepared write state in 37ms
,D/PMS     (  911): releaseWL(42eac1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  911): Pruning old procstats: /data/system/procstats/state-2016-01-14-11-03-10.bin
,D/PMS     (  911): acquireWL(42bcc9f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42bcc9f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43e6d450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43e6d450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4791): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4791): ====startRecUseTime====
D/htc.customization.log.level( 4791):  is 
W/CustomizationLogLevel( 4791): Level value is invalid, use default level 2
D/CustomizationManager( 4791):  Read ACC file spent 0.108 (s)
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4791): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4791): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4791): Parsing tag category name = system
I/CustomizationCIDLoader( 4791): Parsing tag category name = application
I/CustomizationCIDLoader( 4791): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4791): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4791): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4791): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4791): Parsing tag category name = Settings
D/CustomizationManager( 4791):  Read CID file spent 0.160 (s)
D/CustomizationManager( 4791):  All configurations done spent 0.160 (s)
W/HtcNativeFlag( 4791): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4791): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4791): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4791): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4791, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  911): killProcessQuiet, pid=4586
I/ActivityManager(  911): Killing 4586:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
D/Process (  911): killProcessQuiet, pid=4549
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  911): killProcessQuiet, pid=4149
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  911): Killing 4549:com.google.android.gms.unstable/u0a28 (adj 15): empty for 1815s
I/ActivityManager(  911): Killing 4149:com.android.vending/u0a73 (adj 15): empty for 1821s
D/Process (  911): killProcessQuiet, pid=4245
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  911): killProcessQuiet, pid=4066
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  911): killProcessQuiet, pid=4521
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  911): killProcessQuiet, pid=4506
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  911): Killing 4245:com.google.android.configupdater/u0a16 (adj 15): empty for 1835s
I/ActivityManager(  911): Killing 4066:com.google.android.gm/u0a107 (adj 15): empty for 1835s
I/ActivityManager(  911): Killing 4521:com.android.settings:remote/1000 (adj 15): empty for 1835s
I/ActivityManager(  911): Killing 4506:com.htc.calendar/u0a13 (adj 15): empty for 1835s
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4549
I/ActivityManager(  911): Recipient 4245
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  911): Copying FileAsset 0x63d737d0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  911): Recipient 4149
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4506
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4066
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4521
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1594): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1594): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/acms    ( 1886): Unregistering com.test.thalitest
E/acms    ( 1886): Could not unregister removed application com.test.thalitest
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/GeofencerStateMachine( 1444): Ignoring removeGeofence because network location is disabled.
D/PMS     (  911): acquireWL(42503b70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1444 10028 null
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  911): releaseWL(42503b70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/PackageBroadcastService( 1226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  911): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4805 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  911): Delaying start of: ServiceRecord{44251fe0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4805): install
I/MultiDex( 4805): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/ExternalAccountType( 1332): Unsupported attribute readOnly
I/PeopleContactsSync( 1226): CP2 sync disabled
I/MultiDex( 4805): loading existing secondary dex files
I/MultiDex( 4805): load found 1 secondary dex files
I/MultiDex( 4805): install done
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1226, uid=10028, userID:0
I/Icing   ( 1226): doRemovePackageData com.test.thalitest
D/PMS     (  911): acquireWL(42e2e6b8): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
D/PMS     (  911): releaseWL(42e2e6b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  911): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4822 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4805): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  911): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4822): install
I/MultiDex( 4822): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4822): loading existing secondary dex files
I/MultiDex( 4822): load found 1 secondary dex files
I/MultiDex( 4822): install done
I/ProviderInstaller( 4822): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  911): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1405): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1405): handle notify Blinkfeed plugin client changed
I/ActivityManager(  911): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4841 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  911): killProcessQuiet, pid=4634
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4634:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1810s
I/ActivityManager(  911): Recipient 4634
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4805): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4805): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4805): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4805): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4805): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4805): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4805): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4805): threadid=12: thread exiting with uncaught exception (group=0x4171ae30)
E/AndroidRuntime( 4805): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4805): Process: com.google.android.gms.drive, PID: 4805
E/AndroidRuntime( 4805): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4805): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4805): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4805): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4805): 	at ctn.run(SourceFile:985)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms.drive
D/Process ( 4805): killProcess, pid=4805
D/Process ( 4805): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4841, uid=10073, userID:0
D/Finsky  ( 4841): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (4841/10073)
I/ActivityManager(  911): Recipient 4805
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.gms.drive (pid 4805) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/TrimMemoryManager( 1273): [trimMemory] 5
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (4841/10073)
D/Finsky  ( 4841): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  911): acquireWL(4261fca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41df3568: PendingIntentRecord{42483820 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1733674, Int=0
V/AlarmManager(  911): sending alarm PendingIntent{441c3d78: PendingIntentRecord{425faa38 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1913754, Int=0
W/Settings( 4841): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4841): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4841): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4841): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4841): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4841): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4841): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4841): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4841): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4841): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4841): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4841): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4841): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4841): threadid=25: thread exiting with uncaught exception (group=0x4171ae30)
V/AlarmManager(  911): sending alarm PendingIntent{423d7590: PendingIntentRecord{4261c7d0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452857383753, Int=900000
E/ActivityManager(  911): App crashed! Process: com.android.vending
E/AndroidRuntime( 4841): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4841): Process: com.android.vending, PID: 4841
E/AndroidRuntime( 4841): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4841): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4841): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4841): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4841): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4841): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4841): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4841): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4841): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4841): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4841, uid=10073, userID:0
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
D/Process (  911): killProcessQuiet, pid=1503
I/ActivityManager(  911): Killing 1503:com.htc.bgp/u0a14 (adj 15): empty for 1802s
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4841): killProcess, pid=4841
D/Process ( 4841): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2895): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  911): Recipient 4841
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4877 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  911): Process com.android.vending (pid 4841) has died.
E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  911): Recipient 1503
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteLog( 2895): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2895): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x636dedc0
W/dalvikvm( 2895): threadid=14: thread exiting with uncaught exception (group=0x4171ae30)
E/ActivityManager(  911): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2895): killProcess, pid=2895
E/AndroidRuntime( 2895): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2895): Process: com.google.android.googlequicksearchbox:search, PID: 2895
E/AndroidRuntime( 2895): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2895): 	at cid.d(PG:186)
E/AndroidRuntime( 2895): 	at clo.g(PG:594)
E/AndroidRuntime( 2895): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2895): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2895): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2895): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2895): 	at clr.tL(PG:827)
E/AndroidRuntime( 2895): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2895): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2895): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2895): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2895): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2895): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  911): Client com.google.android.googlequicksearchbox (pid 2895): Died!
I/ActivityManager(  911): Recipient 2895
I/ActivityManager(  911): Process com.google.android.googlequicksearchbox:search (pid 2895) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bddd98 +
I/Prism.WidgetManager( 1273): onLoadItems() +
D/WifiService(  911): Client connection lost with reason: 4
E/SQLiteDatabase( 4877): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4877): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4877): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4877): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4877): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4877): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4877): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4877): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4877): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4877): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4877): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4877): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4877): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4877): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4877): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4877): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4877): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4877): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4877): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4877): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4877): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4877): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4877): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4877): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4877): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4877): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4877): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4877): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4877): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4877): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4877): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4877): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4877): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4877): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4877): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4877): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4877): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4877): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4877): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4877): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4877): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4877): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4877): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4877): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4877): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4877): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4877): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4877): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4877): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4877): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4877): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4877): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4877): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4877): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4877): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4877): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4877): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4877): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4877): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4877): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4877): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4877): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4877): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4877): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4877): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4877): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4877): threadid=11: thread exiting with uncaught exception (group=0x4171ae30)
E/AndroidRuntime( 4877): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4877): Process: com.google.android.apps.docs, PID: 4877
E/AndroidRuntime( 4877): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4877): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4877): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4877): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4877): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4877): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4877): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4877): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
D/Process ( 4877): killProcess, pid=4877
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4893 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4877): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  911): Recipient 4877
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4877) has died.

```
