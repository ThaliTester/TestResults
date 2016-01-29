#### Test 575312430087a60_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
--------- beginning of /dev/log/system
D/WIFI_ICON( 1120): WifiActivity: 0
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/cutils-trace( 4445): Error opening trace file: No such file or directory (2)
D/AutoSetting( 1347): service - mHandler: update timezone
D/AutoSetting( 1347): service - handleMessage() stop self
D/AutoSetting( 1521): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1347): service - onDestroy() END
D/AutoSetting( 1347): service - handleMessage() quit looper
D/Process (  907): killProcessQuiet, pid=4238
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1521): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
I/ActivityManager(  907): Killing 4238:com.htc.backup/1000 (adj 15): empty #17
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1521): service - onCreate()
D/AutoSetting( 1521): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1521): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1521): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1521): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1521): service - mHandler: update timezone
D/CustomizationManager( 4445): ====startRecUseTime====
D/htc.customization.log.level( 4445):  is 
W/CustomizationLogLevel( 4445): Level value is invalid, use default level 2
D/AutoSetting( 1521): service - processTimeZoneID() system nitz: 
D/AutoSetting( 1521): service - processTimeZoneID() system nitz is valid: false (false)
I/ActivityManager(  907): Recipient 4238
D/AutoSetting( 1521): service - processTimeZoneID() single-timezone, pop up dialog
D/AutoSetting( 1521): service - showManualTimeZoneSelector() send notification (single)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41e9b268 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1120): com.htc.htclocationservice 1 7 2 11
D/CustomizationManager( 4445):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4445): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4445): Parsing tag category name = system
I/CustomizationCIDLoader( 4445): Parsing tag category name = application
I/CustomizationCIDLoader( 4445): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4445): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4445): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4445): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4445): Parsing tag category name = Settings
D/CustomizationManager( 4445):  Read CID file spent 0.104 (s)
D/CustomizationManager( 4445):  All configurations done spent 0.104 (s)
W/HtcNativeFlag( 4445): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4445): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4445): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4445): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4445
D/PMS     (  907): acquireHCC(42542938): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(4267ac70): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x6cdfa178 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1132108192
I/FeedHostManager( 1277): [onPause]
I/FeedProviderManager( 1277): onPause
I/FeedHostManager( 1277): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bb8088
I/SocialFeedProvider( 1277): +onPause
I/SocialFeedProvider( 1277): -onPause
D/PMS     (  907): acquireWL(42640620): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4461 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4461): Copying FileAsset 0x5c6edde0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1277): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4461): Binding Chromium to main looper Looper (main, tid 1) {41a77178}
I/LibraryLoader( 4461): Expected native library version number "",actual native library version number ""
I/chromium( 4461): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4461): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@435583d0:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  907): acquireWL(42ad2bc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): acquireWL(42db4f50): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): releaseWL(42ad2bc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4461): 1101582312: getState(). Returning 12
I/Adreno-EGL( 4461): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4461): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4461): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4461): Local Branch: 
I/Adreno-EGL( 4461): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4461): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4461):                  aa63bbd948f41d15fc72f585e
W/chromium( 4461): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4461): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4461): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4461): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4461): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4461): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4461): CordovaWebView is running on device made by: HTC
,W/AwContents( 4461): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1277
,W/ResourceType( 4461): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4461): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41abe698, mServedView=org.apache.cordova.engine.SystemWebView{41a84300 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  907): Enable input method client, pid=4461
W/XT9_C   ( 1214): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1214): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1214): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1214): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4461): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +281ms
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42640620): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1188): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/JsMessageQueue( 4461): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4461): JniHelper::setJavaVM(0x41550048), pthread_self() = 1662045424
,I/chromium( 4461): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 11.233MB for 323830-byte allocation
,I/HtcModeClient( 1521): handler message = 4011
,E/HtcModeClient( 1521): Check connection and retry 11 times.
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 11.499MB for 485740-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 11.876MB for 728606-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 12.455MB for 1092904-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 13.325MB for 1639352-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 14.721MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(42542938): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(4267ac70): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 15.413MB for 2288606-byte allocation
,W/jxcore-log( 4461): Initializing JXcore engine
,W/jxcore-log( 4461): JXcore engine is ready
,W/jxcore-log( 4461): Starting JXcore engine
,W/jxcore-log( 4461): Platform android
W/jxcore-log( 4461): 
,W/jxcore-log( 4461): Process ARCH arm
W/jxcore-log( 4461): 
,I/jxcore-log( 4461): JXcore Cordova bridge is ready!
I/jxcore-log( 4461): 
,W/jxcore-log( 4461): JXcore engine is started
,E/jxcore  ( 4461): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4461): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4461): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4461): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  907): acquireWL(43c63a38): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
,I/FeedHostManager( 1277): [onResume]
,I/FeedProviderManager( 1277): onResume
,I/SocialFeedProvider( 1277): +onResume
,I/SocialFeedProvider( 1277): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1277): -onResume
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1277/10076)
,I/InputMethodManagerService(  907): Disable input method client, pid=4461
,W/IInputConnectionWrapper( 4461): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  907): Enable input method client, pid=1277
,D/PMS     (  907): releaseWL(43c63a38): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  907): killProcessQuiet, pid=4202
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  907): Killing 4202:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/libEGL  ( 4461): call to OpenGL ES API with no current context (logged once per thread)
I/ActivityManager(  907): Recipient 4202
,D/PMS     (  907): releaseWL(42db4f50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1188): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  907): acquireWL(42ee2c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=102 rxSum=93} preTxRxSum={txSum=30 rxSum=28}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=21082 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21083 delay=15s
V/AlarmManager(  907): sending alarm PendingIntent{425b7940: PendingIntentRecord{42490608 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=90418, Int=0
D/PMS     (  907): releaseWL(42ee2c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcModeClient( 1521): handler message = 4011
,E/HtcModeClient( 1521): Check connection and retry 12 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1188): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1188): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:136, mTXpacketCount:83, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/SensorManager(  907): mEventCount = 750
,I/HtcModeClient( 1521): handler message = 4011
,E/HtcModeClient( 1521): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1521): Don't start project servcice
,D/HtcModeClient( 1521): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1521): connectState: CONNECTION_READY = false
D/SilentMusic( 1521): call stop
D/HtcModeClient( 1521): close connection
,W/HtcModeClient( 1521): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1521): read the terminate packet, so break
,D/PMS     (  907): acquireWL(424f9398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{426b36e0: PendingIntentRecord{437a35c0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454091957056, Int=0
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4510 uid=10078 gids={50078}
,V/AlarmManager(  907): sending alarm PendingIntent{4248a920: PendingIntentRecord{424c5048 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454091959083, Int=60000
,D/PMS     (  907): releaseWL(424f9398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4510): SMSBackupAgentService started
,D/SMSBackup( 4510): Checking restore status
,D/SMSBackup( 4510): Restore complete
,D/SMSBackup( 4510): cancelCheckAlarm
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
D/SMSBackup( 4510): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Finsky  ( 4074): [425] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4074): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  907): killProcessQuiet, pid=4256
,I/ActivityManager(  907): Killing 4256:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Recipient 4256
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1188): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): acquireWL(425cf8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=97192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425cf8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1120): now=1454091960060 next=59940
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{428a6838 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1188): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,V/LightsService(  907): setLight #0: color=#26
,V/LightsService(  907): setLight #0: color=#1f
,V/LightsService(  907): setLight #0: color=#1c
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/LightsService(  907): setLight #0: color=#14
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1188): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=102 rxSum=93} preTxRxSum={txSum=102 rxSum=93}
D/WifiDataStallTracker(  907): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=21083 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21084 delay=15s
D/PMS     (  907): acquireWL(432209c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4251cd90: PendingIntentRecord{42490608 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105427, Int=0
D/PMS     (  907): releaseWL(432209c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  907): mEventCount = 900
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0],
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1188): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42149ce8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/PMS     (  907): mWirelessDisplayManager is null
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42149ce8, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42025640
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@43ccffb0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 348ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
D/NfcService( 1261): ScreenObserver: OFF
,D/NfcService( 1261): applyRouting - 0
,D/NfcService( 1261): applyRouting -2
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=1277
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMS     (  907): acquireWL(433249a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@433e8230)
,I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMS     (  907): releaseWL(433249a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): wakingUp
I/WindowManager(  907): No lock screen! windowToken=null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  907): onScreenOn
D/PMS     (  907): acquireWL(43be8048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43be8048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/MtpService( 2374): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/PMS     (  907): runPSCheck
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 2374): [MTP][onReceive]-
,D/NfcService( 1261): applyRouting - 0
,D/AutoSetting( 1347): receiver - intent: android.intent.action.USER_PRESENT
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  907): acquireWL(43be7450): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
V/NotificationService(  907): batLight: Full, plugged
,D/NfcService( 1261): applyRouting -2
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/TetherSettings( 3820): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3820): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3820): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3820): Cust_ConnectToPC   : spcsc>false
D/        ( 3820): Cust_ConnectToPC   : IPT>true
D/        ( 3820): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3820): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AutoSetting( 1347): service - onCreate()
E/SmartNS_Utility( 3820): hasRemovableStorageSlot: true
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21085 delay=15s
D/SmartNS_Utility( 3820): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3820): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/PMS     (  907): releaseWL(43be7450): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
,I/PSReceiver( 3820): onReceive:android.intent.action.USER_PRESENT
,I/ClockThread( 1120): stop update clock
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1188): SET_SCREEN_ON:On
I/wpa_supplicant( 1188): htc_wext_set_keepalive +
I/wpa_supplicant( 1188): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1188): getPrivFuncNum +	
I/wpa_supplicant( 1188): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1188): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1188): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1188): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1188): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1347): service - AddressCache: using context: com.htc.Weather
I/SmartNS_PSService( 3820): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3820): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3820):  defaultType:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1347): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  907): request 42571be8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1188): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:136, mTXpacketCount:136, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/NetworkPolicy(  907): updateScreenOn: false
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4316): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(42946280): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(43542ba8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4316 1000 null
D/PMS     (  907): releaseWL(42946280): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42e31638): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42e31638): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): onScreenOn: 1454091971207
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1779): onScreenOn: 1454091971207
D/PMS     (  907): releaseWL(43542ba8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42025640
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42025640, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@43ccffb0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(426617c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/FeedHostManager( 1277): [onPause]
,I/FeedProviderManager( 1277): onPause
I/FeedHostManager( 1277): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bb8088
I/SocialFeedProvider( 1277): +onPause
,I/SocialFeedProvider( 1277): -onPause
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=21085 mDataStallAlarmIntent=PendingIntent{42332128: PendingIntentRecord{42490608 android broadcastIntent}}
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,D/PMS     (  907): releaseWL(426617c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(425a0d48): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1188): SET_SCREEN_ON:Off
I/wpa_supplicant( 1188): htc_wext_set_keepalive +
I/wpa_supplicant( 1188): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1188): getPrivFuncNum +	
I/wpa_supplicant( 1188): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1188): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1188): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1188): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1188): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/NetworkPolicy(  907): updateScreenOn: false
,W/ContextImpl( 4316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4316): isEpsOn(), nState = 0
,D/ContactMessageStore( 1245): start background delete task...
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1245): size: 0 , 0
D/ContactMessageStore( 1245): Background delete complete
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@43ccffb0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@43ccffb0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@43ccffb0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/wpa_supplicant( 1188): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@43ccffb0
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(425a0d48): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4276cbd0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4276cbd0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43539fe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43539fe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): acquireWL(4267ef88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4267ef88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1779): onScreenOff
,D/SmartSyncUtils( 4316): getMobilePolicyEnabled, result = true
D/AutoSetting( 1347): service - mHandler: cancel location update
,D/AutoSetting( 1347): service -           changes count: 0
,D/SmartSyncUtils( 4316): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4316): getMobilePolicyEnabled, result = true
D/WifiService(  907): New client listening to asynchronous messages
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1521): service - handleMessage() stop self
,D/AutoSetting( 1521): service - onDestroy() END
,D/AutoSetting( 1521): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=3923
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3923:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3923
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(43c60900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{4244a490: PendingIntentRecord{42c83620 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122623, Int=0
,D/PMS     (  907): releaseWL(43c60900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43c5ad10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1376/10029)
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43c23628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43c23628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43c5ad10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43acb5b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,D/PMS     (  907): releaseWL(43acb5b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(438a5c60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(437ef4a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(436d83f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1227): Vacuum at: now=1454091985714 tag=VacuumService
,D/PMS     (  907): releaseWL(438a5c60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437ef4a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42c528a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,D/PMS     (  907): releaseWL(42c528a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(436d83f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(425f2040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1376/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(425f2040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4200f8d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767,
,D/PMS     (  907): releaseWL(4200f8d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4249e2a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4249e2a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(423b74c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42e93a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43005d00 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  907): releaseWL(42e93a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42536780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(423b74c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(422cd2b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,D/PMS     (  907): releaseWL(422cd2b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1227): Scheduling Phenotype for one-off execution 6778 seconds from now (1454091986616)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/GetConfigurationSnapshotOperation( 1227): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1227): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1227): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,W/dalvikvm( 1227): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
,D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1227): [NET] getaddrinfo-, 1
,D/libc    ( 1227): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5341 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1227): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1227): [NET] getaddrinfo-,err=8
D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
,D/PMS     (  907): releaseWL(42536780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43302be8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,D/PMS     (  907): releaseWL(43302be8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(423d8610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=10 [10][1][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1376/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1188): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1188): nl80211: survey data missing!
E/wpa_supplicant( 1188): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1188): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,D/PMS     (  907): releaseWL(423d8610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4257fc88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4257fc88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus,
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42320fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{43c049a8: PendingIntentRecord{435a9188 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138599, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1376/10029)
,D/PMS     (  907): releaseWL(42320fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1347): service - handleMessage() stop self
,D/AutoSetting( 1347): service - handleMessage() quit looper
,D/AutoSetting( 1347): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4113
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4113:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4113
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42604ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424c26f8: PendingIntentRecord{424c22c0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142532, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(43590200): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(42604ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =57a4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): releaseWL(43590200): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  907): acquireWL(42618c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157191, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42618c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42913990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42913990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42a11988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{4301aaf8: PendingIntentRecord{436ace00 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174754, Int=0
,D/PMS     (  907): releaseWL(42a11988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(437bc310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(437bc310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43314980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43314980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43c40168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c40168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42db5768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42db5768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(423d8140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=277192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(423d8140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43ca1b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43ca1b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c604e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PMS     (  907): releaseWL(43c604e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42665b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=337192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42665b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(425bd270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(425bd270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42db7728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42db7728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(4260ff68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(4260ff68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42590040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=457191, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42590040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43b2e8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b2e8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42d6fbc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=517191, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42d6fbc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(4355a6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4355a6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4265fa58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=577192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4265fa58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(431d0960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(431d0960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1245): sku_id=99
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  907): acquireWL(43c99df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=637192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c99df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43acd6f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(43acd6f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(425862e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425862e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c99820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=697191, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c99820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(428ea4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428ea4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43497ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(43497ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(435bb518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=757192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(435bb518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42a00100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42a00100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b31b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=817191, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b31b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42922bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42922bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(433ef400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): releaseWL(433ef400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(426bad90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=877191, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426bad90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42a7c9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42a7c9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(429a7b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41cfde90: PendingIntentRecord{4240cd68 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782892, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{41c5b418: PendingIntentRecord{42473110 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=913195, Int=0
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4574 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{425170c0: PendingIntentRecord{424c3bb8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454092075035, Int=10800000
,D/PMS     (  907): acquireWL(429aa328): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(429a7b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(41ddc0b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(429aa328): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(41ddc0b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4574/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,D/Process (  907): killProcessQuiet, pid=3631
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3631:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3631
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42774c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42774c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42583588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=937192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42583588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42e5f958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{4261ffd8: PendingIntentRecord{435e70c0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=949102, Int=0
,D/PMS     (  907): acquireWL(42c8fc98): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{41b95fb0: PendingIntentRecord{41d46f80 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454092795403, Int=900000
,D/PMS     (  907): releaseWL(42c8fc98): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4316): call getInstance()
,D/PMS     (  907): releaseWL(42e5f958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4316): MY_DEBUG = false
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(43c801e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024850
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025316
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025319
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025327
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026899
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029767
,D/PMS     (  907): releaseWL(43c801e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  907): acquireWL(43c635b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/BatteryService(  907): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(43c635b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43c31e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c31e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c288e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=997192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c288e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c28670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e17ba0: PendingIntentRecord{42c77980 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454092871292, Int=0
,D/SmartSyncUtils( 4316): isEpsOn(), nState = 0
D/PMS     (  907): releaseWL(43c28670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  907): acquireWL(43c28168): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4316 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4316): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4316): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4316): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4316): SettingOnTime = 1454133600000, randomSettingOnTime = 1454132232000
,D/SmartSyncScreenOnOffTimeReceiver( 4316): SettingOffTime = 1454119200000, randomSettingOffTime = 1454122909000
,D/SmartSyncScreenOnOffTimeReceiver( 4316): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4316): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4316): bNightModeTurnOffOnce = false
,D/PMS     (  907): releaseWL(43c28168): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  907): acquireWL(43c22120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c22120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c21e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1057192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c21e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c21b20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c21b20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c03ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1117192, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c03ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43bd6268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43bd6268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43b3baf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1177191, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b3baf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b32310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b32310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(43b32010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1237191, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b32010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43ab51a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43ab51a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),D/CustomizationManager( 4593): ====startRecUseTime====
D/htc.customization.log.level( 4593):  is 
W/CustomizationLogLevel( 4593): Level value is invalid, use default level 2
D/CustomizationManager( 4593):  Read ACC file spent 0.130 (s)
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4593): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4593): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4593): Parsing tag category name = system
I/CustomizationCIDLoader( 4593): Parsing tag category name = application
I/CustomizationCIDLoader( 4593): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4593): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4593): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4593): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4593): Parsing tag category name = Settings
D/CustomizationManager( 4593):  Read CID file spent 0.185 (s)
D/CustomizationManager( 4593):  All configurations done spent 0.185 (s)
W/HtcNativeFlag( 4593): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4593): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4593): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4593): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4593, uid=2000 user=0
D/Process (  907): killProcessQuiet, pid=4461
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
I/ActivityManager(  907): Killing 4461:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
W/asset   (  907): Copying FileAsset 0x6cdefdc8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  907): Skipping PackageSetting{421776d8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
W/SQLiteConnectionPool( 2191): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/PMS     (  907): acquireWL(425ddcb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1227): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  907): releaseWL(425ddcb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1290): Cleaning up data for package: com.test.thalitest
I/Launcher( 1277): Deferring update until onResume
D/Launcher( 1277): waitUntilResume // bindAppsRemoved
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
W/SystemReader( 1261): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
D/Prism.PackageStateRece_( 1277): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1347): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1347): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/IcingCorporaProvider( 2836): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
E/ExternalAccountType( 1333): Unsupported attribute readOnly
W/Parcel  ( 1261): Reading a NULL string not supported here.
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
E/cutils-trace( 4593): Error opening trace file: No such file or directory (2)
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4608 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  907): acquireWL(436a6d58): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(436a6d58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(436982a8): PARTIAL_WAKE_LOCK  Icing 0x1 2191 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2836): UpdateCorporaTask done [took 423 ms] updated apps [took 423 ms] 
E/SQLiteDatabase( 4608): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4608): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4608): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4608): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4608): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4608): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4608): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4608): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4608): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4608): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4608): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4608): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4608): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4608): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4608): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4608): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4608): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4608): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4608): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4608): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4608): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4608): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4608): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4608): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4608): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4608): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4608): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4608): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4608): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4608): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4608): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4608): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4608): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4608): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4608): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4608): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4608): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4608): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4608): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4608): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4608): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4608): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4608): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4608): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4608): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4608): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4608): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4608): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4608): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4608): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4608): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4608): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4608): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4608): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4608): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4608): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4608): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4608): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4608): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4608): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4608): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4608): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4608): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4608): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4608): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4608): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4608): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4608): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4608): threadid=11: thread exiting with uncaught exception (group=0x41648e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4608): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4608): Process: com.google.android.apps.docs, PID: 4608
E/AndroidRuntime( 4608): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4608): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4608): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4608): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4608): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4608): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4608): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4608): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4608): 	at aho.run(AbstractDatabaseInstance.java:455)
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
D/Process ( 4608): killProcess, pid=4608
D/Process ( 4608): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4626 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4608
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4608) has died.
W/PackageManager(  907): Unable to load service info ResolveInfo{4231c4b0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
W/ContextImpl( 4626): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4626): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4626): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4626): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4626): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4626): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4626): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4626): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4626): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4626): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4626): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4626): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4626): threadid=10: thread exiting with uncaught exception (group=0x41648e30)
E/AndroidRuntime( 4626): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4626): Process: com.android.keychain, PID: 4626
E/AndroidRuntime( 4626): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4626): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4626): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4626): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4626): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4626): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4626): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4626): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4626): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4626): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4639 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4626): killProcess, pid=4626
D/Process ( 4626): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454093159791.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4626
I/ActivityManager(  907): Process com.android.keychain (pid 4626) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4639): getInstance(Context context)
D/AppTag  ( 4639): getInstance(Context context)
D/AppTag  ( 4639): onCreate()
D/PMS     (  907): acquireWL(43544208): PARTIAL_WAKE_LOCK  AsyncService 0x1 3554 10160 null
D/PMS     (  907): releaseWL(43544208): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4074): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2191): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2191): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2191): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2191): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2191): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2191): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2191): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x655dec20
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 2191): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2191): Module APK com.google.android.play.games already loaded
E/DriveAsyncService( 2191): disk I/O error (code 3850)
E/DriveAsyncService( 2191): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2191): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2191): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2191): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2191): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2191): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2191): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2191): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2191): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 2191): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2191): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65dbd990
W/dalvikvm( 2191): threadid=49: thread exiting with uncaught exception (group=0x41648e30)
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
E/SQLiteDatabase( 2191): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2191): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2191): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2191): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2191): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2191): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2191): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2191): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2191): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2191): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 2191): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2191): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2191): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2191): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2191): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2191): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2191): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2191): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2191): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 2191): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2191): Process: com.google.android.gms, PID: 2191
E/AndroidRuntime( 2191): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2191): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2191): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2191): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2191): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2191): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2191): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2191): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2191): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2191): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2191): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 2191): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2191): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2191): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2191): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2191): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2191): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2191): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2191): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2191): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2191): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2191): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2191): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/Process ( 2191): killProcess, pid=2191
D/Process ( 2191): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/SQLiteLog( 2191): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
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
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  907): acquireWL(42664ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b9e7e8: PendingIntentRecord{421e4f58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1297191, Int=0
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  907): releaseWL(42664ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/ActivityManager(  907): Recipient 2191
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): handleWLDeath(436982a8): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  907): Process com.google.android.gms (pid 2191) has died.
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10998ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10995ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10994ms
E/SQLiteLog( 1376): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1376): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5c995968
W/dalvikvm( 1376): threadid=1: thread exiting with uncaught exception (group=0x41648e30)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1376): FATAL EXCEPTION: main
E/AndroidRuntime( 1376): Process: com.google.process.gapps, PID: 1376
E/AndroidRuntime( 1376): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1376): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1376): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1376): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1376): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1376): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1376): 	... 10 more
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
D/Process ( 1376): killProcess, pid=1376
D/Process ( 1376): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4668 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4668): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4668 dbg=false s=true
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b0bd50 +
I/DeviceManagement( 4668): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/Prism.WidgetManager( 1277): onLoadItems() +
I/DeviceManagement( 4668): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4668): WorkflowService: Starting workflow service
I/DeviceManagement( 4668): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41aabf18] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4668): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4668): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4668): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4668): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4682 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4668): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4668): SessionStateController: Checking invariants...
I/ActivityManager(  907): Recipient 1376
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.process.gapps (pid 1376) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20805ms
D/WifiService(  907): Client connection lost with reason: 4
D/Documents( 4682): Loading roots for com.android.providers.downloads.documents
D/Documents( 4682): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4682): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4682): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4682): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4682): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4682): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4682): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4682): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4682): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4682): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4682): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4682): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4682): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4682): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4682): threadid=1: thread exiting with uncaught exception (group=0x41648e30)
E/AndroidRuntime( 4682): FATAL EXCEPTION: main
E/AndroidRuntime( 4682): Process: com.android.documentsui, PID: 4682
E/AndroidRuntime( 4682): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4682): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4682): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4682): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4682): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4682): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4682): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4682): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4682): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4682): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4682): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4682): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4682): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4682): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4682): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4682): 	... 10 more
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4696 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4709 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/Process (  907): killProcessQuiet, pid=4352
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 

```
