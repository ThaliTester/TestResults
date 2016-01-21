#### Test 568182548138a64_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1120): WifiActivity: 0
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{42dc80b0 u0 com.htc.htclocationservice/.AutoSettingService}
--------- beginning of /dev/log/main
E/cutils-trace( 4482): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4482): ====startRecUseTime====
D/htc.customization.log.level( 4482):  is 
W/CustomizationLogLevel( 4482): Level value is invalid, use default level 2
D/CustomizationManager( 4482):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4482): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4482): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4482): Parsing tag category name = system
I/CustomizationCIDLoader( 4482): Parsing tag category name = application
I/CustomizationCIDLoader( 4482): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4482): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4482): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4482): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4482): Parsing tag category name = Settings
D/CustomizationManager( 4482):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4482):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 4482): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4482): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4482): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4482): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4482
D/PMS     (  909): acquireHCC(42563ae0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(420831f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1121773400
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
D/PMS     (  909): acquireWL(425c06a8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c3eac8
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4493 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1275): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4493): Binding Chromium to main looper Looper (main, tid 1) {41ade5b8}
I/LibraryLoader( 4493): Expected native library version number "",actual native library version number ""
I/chromium( 4493): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4493): Initializing chromium process, renderers=0
D/PMS     (  909): acquireWL(442c7c70): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): acquireWL(4241f7f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4256ba68:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4493): 1102004208: getState(). Returning 12
D/PMS     (  909): releaseWL(442c7c70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4493): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4493): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4493): Local Branch: 
I/Adreno-EGL( 4493): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4493): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4493):                  aa63bbd948f41d15fc72f585e
W/chromium( 4493): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4493): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4493): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4493): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4493): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4493): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4493): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4493): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4493): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4493): CordovaWebView is running on device made by: HTC
,W/AwContents( 4493): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +254ms
,W/ResourceType( 4493): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4493): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b256a0, mServedView=org.apache.cordova.engine.SystemWebView{41aeb308 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  909): Disable input method client, pid=1275
,I/InputMethodManagerService(  909): Enable input method client, pid=4493
W/AwContents( 4493): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  909): releaseWL(425c06a8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/JsMessageQueue( 4493): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4493): JniHelper::setJavaVM(0x415b1048), pthread_self() = 1663773816
,I/chromium( 4493): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 12.047MB for 63974-byte allocation
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 12.087MB for 95956-byte allocation
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 12.160MB for 143930-byte allocation
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 12.275MB for 215890-byte allocation
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 12.450MB for 323830-byte allocation
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 13.125MB for 728606-byte allocation
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 13.723MB for 1092904-byte allocation
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 14.642MB for 1639352-byte allocation
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 15.887MB for 2459024-byte allocation
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4493): Grow heap (frag case) to 18.073MB for 3688532-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(42563ae0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(420831f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4493): Initializing JXcore engine
,W/jxcore-log( 4493): JXcore engine is ready
,W/jxcore-log( 4493): Starting JXcore engine
,W/jxcore-log( 4493): Platform android
W/jxcore-log( 4493): 
,W/jxcore-log( 4493): Process ARCH arm
W/jxcore-log( 4493): 
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 4493): JXcore Cordova bridge is ready!
I/jxcore-log( 4493): 
,W/jxcore-log( 4493): JXcore engine is started
,E/jxcore  ( 4493): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4493): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4493): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  909): acquireWL(430f7c70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
,I/FeedHostManager( 1275): [onResume]
,I/FeedProviderManager( 1275): onResume
,I/SocialFeedProvider( 1275): +onResume
I/SocialFeedProvider( 1275): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1275): -onResume
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.launcher (1275/10075)
,I/InputMethodManagerService(  909): Disable input method client, pid=4493
,W/IInputConnectionWrapper( 4493): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  909): Enable input method client, pid=1275
,D/PMS     (  909): releaseWL(430f7c70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  909): killProcessQuiet, pid=3131
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  909): Killing 3131:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3131
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/libEGL  ( 4493): call to OpenGL ES API with no current context (logged once per thread)
,D/PMS     (  909): releaseWL(4241f7f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4541 uid=10077 gids={50077}
,D/PMS     (  909): acquireWL(435cccd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10077}
V/AlarmManager(  909): sending alarm PendingIntent{424e5870: PendingIntentRecord{4250fd78 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453415999559, Int=60000
,D/PMS     (  909): releaseWL(435cccd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4541): SMSBackupAgentService started
,D/SMSBackup( 4541): Checking restore status
D/SMSBackup( 4541): Restore complete
,D/SMSBackup( 4541): cancelCheckAlarm
,D/SMSBackup( 4541): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  909): killProcessQuiet, pid=3662
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3662:com.htc.task/u0a70 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3662
,D/PMS     (  909): acquireWL(43c52778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=104415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c52778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1120): now=1453416000059 next=59941
,D/PMS     (  909): acquireWL(425e77f8): PARTIAL_WAKE_LOCK  Icing 0x1 2236 10028 null
,D/PMS     (  909): releaseWL(425e77f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(430a0710): PARTIAL_WAKE_LOCK  Icing 0x1 2236 10028 null
,D/PMS     (  909): releaseWL(430a0710): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(425f6da0): PARTIAL_WAKE_LOCK  Icing 0x1 2236 10028 null
,D/PMS     (  909): releaseWL(425f6da0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  909): acquireWL(44264958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{424b48d8: PendingIntentRecord{4251a9a8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=106674, Int=0
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=122 rxSum=118} preTxRxSum={txSum=122 rxSum=118}
D/WifiDataStallTracker(  909): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  909): onDataStallAlarm: tag=19679 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19680 delay=15s
D/PMS     (  909): releaseWL(44264958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:173, mTXpacketCount:173, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/SensorManager(  909): mEventCount = 1050
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42153118
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42153118, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420da1c8
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@42612d88
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  909): mWirelessDisplayManager is null
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 393ms
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
D/PMS     (  909): OOBE c monitor 11
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  909): Disable input method client, pid=1275
D/NfcService( 1259): ScreenObserver: OFF
V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43e18608)
,D/NfcService( 1259): applyRouting - 0
,I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  909): wakingUp
,D/NfcService( 1259): applyRouting -2
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/PMS     (  909): acquireWL(43e6f708): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  909): acquireWL(43e826e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43e6f708): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  909): releaseWL(43e826e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/WindowManager(  909): No lock screen! windowToken=null
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
D/PMN     (  909): onScreenOn
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2493): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1259): applyRouting - 0
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/MtpService( 2493): [MTP][onReceive]-
,D/NfcService( 1259): applyRouting -2
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19681 delay=15s
D/PMS     (  909): acquireWL(43cc6840): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  909): releaseWL(43cc6840): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
I/ClockThread( 1120): stop update clock
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): SET_SCREEN_ON:On
I/wpa_supplicant( 1137): htc_wext_set_keepalive +
I/wpa_supplicant( 1137): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1137): getPrivFuncNum +	
I/wpa_supplicant( 1137): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING - ret = 0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4566 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  909): updateScreenOn: false
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4566): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1813): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1813): onScreenOn: 1453416006608
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1813): onScreenOn: 1453416006608
D/PMS     (  909): acquireWL(43cf4ba0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1480 10028 null
D/PMS     (  909): releaseWL(43cf4ba0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  909): acquireWL(43e16ac8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4566 1000 null
D/SmartSyncUtils( 4566): isEpsOn(), nState = 0
I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420da1c8
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420da1c8, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@42612d88
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(44246b58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,I/FeedHostManager( 1275): [onPause]
,I/FeedProviderManager( 1275): onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c3eac8
I/SocialFeedProvider( 1275): +onPause
,I/SocialFeedProvider( 1275): -onPause
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19681 mDataStallAlarmIntent=PendingIntent{43c80e70: PendingIntentRecord{4251a9a8 android broadcastIntent}}
D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
,D/PMS     (  909): releaseWL(44246b58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1137): SET_SCREEN_ON:Off
I/wpa_supplicant( 1137): htc_wext_set_keepalive +
I/wpa_supplicant( 1137): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1137): getPrivFuncNum +	
I/wpa_supplicant( 1137): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1137): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1137): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1137): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  909):    returned true
D/PMS     (  909): acquireWL(43e0c6d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43e16ac8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  909): updateScreenOn: false
,D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/AutoSetting( 1428): receiver - intent: android.intent.action.USER_PRESENT
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1428): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(43e0c6d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/TetherSettings( 4327): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4327): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4327): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4327): Cust_ConnectToPC   : spcsc>false
,D/        ( 4327): Cust_ConnectToPC   : IPT>true
,D/        ( 4327): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4327): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4327): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4327): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,I/PSReceiver( 4327): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4327): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4327):  defaultType:0
,D/AutoSetting( 1428): service - mHandler: cancel location update
,D/AutoSetting( 1428): service -           changes count: 0
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1813): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1813): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1813): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1813): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1813): onScreenOff
D/PMS     (  909): acquireWL(43c96308): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1480 10028 null
D/PMS     (  909): releaseWL(43c96308): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/SmartSyncUtils( 4566): isEpsOn(), nState = 0
W/ContextImpl( 4566): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42612d88
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
,W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42612d88, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42612d88, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42612d88
,E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4255ee40 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4255ee40 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/SmartSyncUtils( 4566): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4566): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4566): getMobilePolicyEnabled, result = true
D/WifiService(  909): New client listening to asynchronous messages
,D/Process (  909): killProcessQuiet, pid=3962
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3962:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3962
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  909): Client com.google.android.music (pid 3962): Died!
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=3945
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3945:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3945
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  909): killProcessQuiet, pid=3984
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3984:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3984
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(43e88c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/PMS     (  909): acquireWL(43e84368): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,V/AlarmManager(  909): sending alarm PendingIntent{41dda6b8: PendingIntentRecord{42481b30 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=128111, Int=0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): releaseWL(43e88c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43e2f700): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0,
,D/PMS     (  909): acquireWL(43ca7f10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 909 1000 WorkSource{10106}
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  909): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4591 uid=10106 gids={50106, 3003, 5012}
,D/PMS     (  909): releaseWL(43e84368): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(43e2f700): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4591): LocationClient connecting
,D/PMS     (  909): acquireWL(43c94cb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1480 10028 null
,D/PMS     (  909): releaseWL(43c94cb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4591): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4591): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4591): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4591): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4591): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4591): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...,
,I/ProviderInstaller( 4591): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43c90aa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43c90aa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4591): Last usage 0, idle 1453416024s, sync interval 2592000s
,I/NewsWeather( 4591): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4591): onConnected null
D/PMS     (  909): acquireWL(436b57e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1480 10028 null
,W/GCoreFlp( 1480): No location to return for getLastLocation()
,I/NewsWeather( 4591): LocationClient onConnected: location null
D/PMS     (  909): acquireWL(436b2d60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1480 10028 null
D/PMS     (  909): releaseWL(436b57e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  909): releaseWL(436b2d60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4591): Skip sync for lookup editions
,I/NewsWeather( 4591): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4591): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1595): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/NewsWeather( 4591): Unrecoverable authentication exception
E/NewsWeather( 4591): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4591): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4591): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4591): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41b25eb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 3 12 3 12
D/libc    ( 4591): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4591): [NET] getaddrinfo-,err=8
D/libc    ( 4591): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4591): [NET] getaddrinfo-, 1
,D/libc    ( 4591): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ed05 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4591): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 4591): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4591): [NET] getaddrinfo-,err=8
,D/PMS     (  909): acquireWL(4232c828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  909): releaseWL(4232c828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4591): Failed to syncNewsAppData
,E/NewsWeather( 4591): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(420cad98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/SyncManager(  909): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 66785, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  909): releaseWL(43ca7f10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1334): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1334): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  909): killProcessQuiet, pid=4298
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Killing 4298:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1480/10028)
D/PMS     (  909): releaseWL(420cad98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(425e60f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(425e60f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  909): Recipient 4298
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,D/AccTypeManager( 1334): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1334): Unsupported attribute readOnly
,D/PMS     (  909): acquireWL(425bf3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(425bf3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/GAV4    ( 4591): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1428): service - handleMessage() stop self
D/PMS     (  909): acquireWL(43db5c30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10028}
V/AlarmManager(  909): sending alarm PendingIntent{425ea398: PendingIntentRecord{425e4d38 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141152, Int=0
V/AlarmManager(  909): sending alarm PendingIntent{42420620: PendingIntentRecord{42438c78 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141155, Int=0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  909): acquireWL(420cdb28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  909): releaseWL(420cdb28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1428): service - onDestroy() END
,D/AutoSetting( 1428): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4349
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4349:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4349
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(425deb10): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(43db5c30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =203b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10,
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.,
D/libc    (  909): [NET] getaddrinfo+,hn 12(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  909): releaseWL(425deb10): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2236/10028)
,D/PMS     (  909): acquireWL(42b17160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41dda6b8: PendingIntentRecord{42481b30 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=158197, Int=0
,D/PMS     (  909): acquireWL(43db6300): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): releaseWL(42b17160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42e91688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43db6300): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(42e91688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(4361a7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=164415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4361a7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(430e0360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(430e0360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(425c3750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{42ced570: PendingIntentRecord{43a92710 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175142, Int=0
,D/PMS     (  909): releaseWL(425c3750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(42ec9a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42ec9a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43e29b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=224415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43e29b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42ec3038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/PMS     (  909): releaseWL(42ec3038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(423df6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423df6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4262ad68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41dda6b8: PendingIntentRecord{42481b30 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=251859, Int=0
,D/PMS     (  909): acquireWL(425bfc20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,D/PMS     (  909): releaseWL(4262ad68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(43c574f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=6 [46][3][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(42ebd790): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 909 1000 WorkSource{10106}
D/PMS     (  909): releaseWL(425bfc20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  909): releaseWL(43c574f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4367ee10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,I/NewsWeather( 4591): Last usage 0, idle 1453416147s, sync interval 2592000s
,I/NewsWeather( 4591): setPeriodicSync in seconds 2592000
D/PMS     (  909): releaseWL(4367ee10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4591): Skip sync for lookup editions
,I/NewsWeather( 4591): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4591): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1595): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/NewsWeather( 4591): Unrecoverable authentication exception
E/NewsWeather( 4591): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4591): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4591): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4591): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41e6bfa8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 17 5 12
,D/PMS     (  909): acquireWL(43565260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  909): releaseWL(43565260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4591): Failed to syncNewsAppData
,E/NewsWeather( 4591): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4356d030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/SyncManager(  909): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 129207, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  909): releaseWL(42ebd790): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1334): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1334): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): releaseWL(4356d030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1480/10028)
D/PMS     (  909): acquireWL(43e25f50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(43e25f50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1334): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1334): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(436a5a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41dda6b8: PendingIntentRecord{42481b30 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=281912, Int=0
,D/PMS     (  909): acquireWL(436d46f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
D/PMS     (  909): releaseWL(436a5a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(441c5fd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(436d46f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(441c5fd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(43cb7190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=284415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43cb7190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42e8a7a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(42e8a7a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(4425b488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  909): n_update end
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(4425b488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43debf00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=344415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43debf00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(436bc2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436bc2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1595): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41e60c98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4253): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4253): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4253): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 15 3 12
,D/libc    ( 4253): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4253): [NET] getaddrinfo-,err=8
D/libc    ( 4253): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4253): [NET] getaddrinfo-, 1
,D/libc    ( 4253): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =83aa +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4253): [NET] getaddrinfo_proxy-, success
I/global  ( 4253): call createSocket() return a new socket.
D/libc    ( 4253): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4253): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4253): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4253): [NET] getaddrinfo-,err=8
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(43380988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=404415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43380988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(438076e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(438076e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43c857d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(43c857d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43cb6340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=464415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43cb6340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(442fec90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(442fec90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43c6a288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c6a288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  909): << updateStatus
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(43c711e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{41dda6b8: PendingIntentRecord{42481b30 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=497839, Int=0
,D/PMS     (  909): acquireWL(43c8f698): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
D/PMS     (  909): releaseWL(43c711e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(44246290): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=4 [48][2][0]
,D/PMS     (  909): acquireWL(42d91dc0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 909 1000 WorkSource{10106}
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(42c34148): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 909 1000 WorkSource{10160}
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(43c8f698): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(44246290): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43e065a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43e065a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43694ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43694ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/NewsWeather( 4591): Last usage 0, idle 1453416393s, sync interval 2592000s
,I/NewsWeather( 4591): setPeriodicSync in seconds 2592000
D/PMS     (  909): acquireWL(42f01948): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(42f01948): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4591): Skip sync for lookup editions
,I/NewsWeather( 4591): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4591): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4420d678): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42c34148): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  909): releaseWL(4420d678): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1595): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/NewsWeather( 4591): Unrecoverable authentication exception
E/NewsWeather( 4591): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4591): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4591): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4591): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41dfda28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4591): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4591): [NET] getaddrinfo-,err=8
D/libc    ( 4591): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4591): [NET] getaddrinfo-, 1
D/libc    ( 4591): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2434 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4591): [NET] getaddrinfo_proxy-, success,
,I/RemoteViews.Performance( 1120): com.google.android.gms 4 10 4 12
,D/libc    ( 4591): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4591): [NET] getaddrinfo-,err=8
,E/NewsWeather( 4591): Failed to syncNewsAppData
,E/NewsWeather( 4591): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  909): acquireWL(430d27f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(425da268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/SyncManager(  909): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 252535, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  909): releaseWL(430d27f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  909): releaseWL(42d91dc0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1334): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1334): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1480/10028)
,D/PMS     (  909): releaseWL(425da268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42682568): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42682568): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1334): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1334): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(436e52d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=524415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(436e52d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43dc1118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41dda6b8: PendingIntentRecord{42481b30 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=527906, Int=0
,D/PMS     (  909): acquireWL(441eae30): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
D/PMS     (  909): releaseWL(43dc1118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(423412e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(441eae30): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(423412e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(43e91de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  909): releaseWL(43e91de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(42599dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42599dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(441eb7e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=584415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(441eb7e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43685ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(43685ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(437f0820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(437f0820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1248): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1248): sku_id=99
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete,
,D/PMS     (  909): acquireWL(43df9998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=644415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43df9998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(435f9dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/BatteryService(  909): n_update end
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(435f9dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43af4e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43af4e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(436a0f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=704415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(436a0f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(442d9408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442d9408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  909): killProcessQuiet, pid=4383
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4383:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4383
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(43ddbf78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=764415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43ddbf78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42a3ec00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42a3ec00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(442e78f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442e78f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43e723d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=824415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43e723d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43e2f700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(43e2f700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43cc3670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43cc3670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43c8e980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=884415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c8e980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43c8d878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PMS     (  909): releaseWL(43c8d878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43c686b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c686b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43c50d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=944415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c50d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43c50460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(43c50460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(436e9808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436e9808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42f4ff90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41dda6b8: PendingIntentRecord{42481b30 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=989014, Int=0
,D/PMS     (  909): acquireWL(42f2eac8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): releaseWL(42f4ff90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42db1b58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=16 [50][8][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): acquireWL(41feed88): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 909 1000 WorkSource{10106}
,D/PMS     (  909): releaseWL(42f2eac8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(42db1b58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4229e708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,I/NewsWeather( 4591): Last usage 0, idle 1453416884s, sync interval 2592000s
,I/NewsWeather( 4591): setPeriodicSync in seconds 2592000
D/PMS     (  909): releaseWL(4229e708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4591): Skip sync for lookup editions
,I/NewsWeather( 4591): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4591): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1595): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/NewsWeather( 4591): Unrecoverable authentication exception
E/NewsWeather( 4591): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4591): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4591): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4591): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4591): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41ff55b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4591): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4591): [NET] getaddrinfo-,err=8
D/libc    ( 4591): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4591): [NET] getaddrinfo-, 1
,D/libc    ( 4591): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
I/RemoteViews.Performance( 1120): com.google.android.gms 1 16 4 12
D/libc    (  364): [NET] +++++ res_nsend xid =fb40 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4591): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4591): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4591): [NET] getaddrinfo-,err=8
,D/PMS     (  909): acquireWL(442ace18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  909): releaseWL(442ace18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4591): Failed to syncNewsAppData
,E/NewsWeather( 4591): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4369dc70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/SyncManager(  909): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 498406, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  909): releaseWL(41feed88): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1334): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1334): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): releaseWL(4369dc70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1480/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(423db080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(423db080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1334): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1334): Unsupported attribute readOnly
,D/PMS     (  909): acquireWL(422da5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1004415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(422da5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,D/PMS     (  909): acquireWL(42559cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41e07a78: PendingIntentRecord{42419a50 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785966, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{42500508: PendingIntentRecord{425ba9a0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=927981, Int=0
,D/PMS     (  909): acquireWL(42dea570): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1372 10028 null
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,D/PMS     (  909): releaseWL(42dea570): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4659 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{424ac200: PendingIntentRecord{425cc688 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453416116222, Int=10800000
,V/AlarmManager(  909): sending alarm PendingIntent{420c2800: PendingIntentRecord{4260d7b0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453416836396, Int=900000
,V/AlarmManager(  909): sending alarm PendingIntent{43dbef38: PendingIntentRecord{426a9920 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453416906744, Int=0
,W/ContextImpl( 4566): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  909): acquireWL(425b53f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PowerUsageService( 4566): call getInstance()
,D/SmartSyncUtils( 4566): isEpsOn(), nState = 0
,D/PMS     (  909): releaseWL(425b53f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageList:PowerUsageHelper( 4566): MY_DEBUG = false,
D/PMS     (  909): releaseWL(42559cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  909): acquireWL(431a5718): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4566 1000 null
,D/PMS     (  909): acquireWL(43cde370): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/SmartSyncScreenOnOffTimeReceiver( 4566): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4566): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4566): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4566): SettingOnTime = 1453442400000, randomSettingOnTime = 1453441957000
D/SmartSyncScreenOnOffTimeReceiver( 4566): SettingOffTime = 1453420800000, randomSettingOffTime = 1453424287000
D/SmartSyncScreenOnOffTimeReceiver( 4566): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4566): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4566): bNightModeTurnOffOnce = false
W/BatSI   (  909): Couldn't get kernel wake lock stats
D/PMS     (  909): releaseWL(431a5718): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4659/10047)
,D/GCM     ( 1372): Message class mow
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  909): releaseWL(43cde370): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  909): acquireWL(43ac1568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  909): releaseWL(43ac1568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,I/ActivityManager(  909): Killing 4406:com.htc.backup/1000 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4406
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4406
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  909): acquireWL(43de3458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43de3458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42c80a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41dda6b8: PendingIntentRecord{42481b30 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1019068, Int=0
,D/PMS     (  909): acquireWL(43584bf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
D/PMS     (  909): releaseWL(42c80a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43dc0000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43584bf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(43dc0000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(43a42070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a42070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43df5418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1064415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43df5418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4361d638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4361d638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(442bc6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442bc6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43e0a618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1124415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43e0a618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43e08c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43e08c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43cc9d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PMS     (  909): releaseWL(43cc9d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43c8f1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1184415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c8f1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43c8e3b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c8e3b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/DotMatrix( 1595): [EventService] reorderNotification, total:1
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1619): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  909): batLight: plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c80000
D/qdlights(  909): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
W/ContextImpl( 4566): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  909): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,D/TetherSettings( 4327): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4327): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4327): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4327): Cust_ConnectToPC   : spcsc>false
D/        ( 4327): Cust_ConnectToPC   : IPT>true
D/        ( 4327): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4327): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4327): Index of the first 1 = -1
W/Settings( 4327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4327): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4327): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4327): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4327): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43c5b7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c5b7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=98
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43b494a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43b494a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(43b442f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1244415, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43b442f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43b42110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(43b42110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(436c4c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(436c4c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,98,-1,false,false,false,-1),
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4367afd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42374bc0: PendingIntentRecord{42366210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1304415, Int=0
,I/FeedHostManager( 1275): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{41c80d40: PendingIntentRecord{424582b0 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1453417200000, Int=0
V/AlarmManager(  909): sending alarm PendingIntent{42187738: PendingIntentRecord{4257f088 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_UPDATE_GOLDEN_TABLE, t=0, cnt=1, w=1453417200000, Int=86400000
D/PMS     (  909): acquireWL(43649730): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1275 10075 null
D/PMS     (  909): releaseWL(43649730): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/PMS     (  909): acquireWL(42db1b58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4566 1000 null
,D/PMS     (  909): releaseWL(4367afd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4204d588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10070}
,V/AlarmManager(  909): sending alarm PendingIntent{42e54430: PendingIntentRecord{43a9b328 com.htc.task broadcastIntent}}, i=com.htc.task.date.change, t=1, cnt=1, w=1453417200676, Int=0
,I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4688 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  909): releaseWL(4204d588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10070}
,D/TodoTaskshortcut( 4688): update TASK shortcut>
,I/ActivityManager(  909): Killing 4369:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4369
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4369
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1248): notify MmsSms
,D/AccFlag ( 1248): sense_version=6.0
,D/AccFlag ( 1248): sku_id=99
,D/TelephUtils( 1248): QUERY for  <hidden uri>  [ com.android.phone ] tid: 38
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4701 uid=10038 gids={50038}
,D/SMSBackup( 4541): Got a database change event
,D/Process (  909): killProcessQuiet, pid=4424
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  909): Killing 4424:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4424
,D/PMS     (  909): releaseWL(42db1b58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4714): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4714): ====startRecUseTime====
D/htc.customization.log.level( 4714):  is 
W/CustomizationLogLevel( 4714): Level value is invalid, use default level 2
D/CustomizationManager( 4714):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4714): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4714): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4714): Parsing tag category name = system
I/CustomizationCIDLoader( 4714): Parsing tag category name = application
I/CustomizationCIDLoader( 4714): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4714): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4714): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4714): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4714): Parsing tag category name = Settings
D/CustomizationManager( 4714):  Read CID file spent 0.162 (s)
D/CustomizationManager( 4714):  All configurations done spent 0.162 (s)
W/HtcNativeFlag( 4714): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4714): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4714): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4714): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4714, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  909): killProcessQuiet, pid=4493
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  909): Killing 4493:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
D/DotMatrix( 1595): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1595): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1906): Unregistering com.test.thalitest
E/acms    ( 1906): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1480): Ignoring removeGeofence because network location is disabled.
D/PMS     (  909): acquireWL(43e3c910): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1480 10028 null
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1275): Deferring update until onResume
D/Launcher( 1275): waitUntilResume // bindAppsRemoved
D/PMS     (  909): releaseWL(43e3c910): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1302): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1334): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1334): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/PackageBroadcastService( 2236): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  909):   Scheme: "mms"
I/ActivityManager(  909): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4728 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/AccTypeManager( 1334): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/ActivityManager(  909): Delaying start of: ServiceRecord{442be9c0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PeopleContactsSync( 2236): CP2 sync disabled
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/PMS     (  909): acquireWL(42338288): PARTIAL_WAKE_LOCK  Icing 0x1 2236 10028 null
I/Icing   ( 2236): doRemovePackageData com.test.thalitest
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2236, uid=10028, userID:0
I/MultiDex( 4728): install
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  909): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4746 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4728): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/ExternalAccountType( 1334): Unsupported attribute readOnly
D/PMS     (  909): releaseWL(42338288): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4728): loading existing secondary dex files
I/MultiDex( 4728): load found 1 secondary dex files
I/MultiDex( 4728): install done
I/MultiDex( 4746): install
I/ProviderInstaller( 4728): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4746): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4746): loading existing secondary dex files
I/MultiDex( 4746): load found 1 secondary dex files
I/MultiDex( 4746): install done
I/ActivityManager(  909): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4746): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/SQLiteDatabase( 2236): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2236): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2236): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2236): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2236): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2236): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2236): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2236): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2236): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2236): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2236): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2236): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2236): Runtime exception while performing operation
E/ClearPendingStateOp( 2236): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2236): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2236): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2236): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2236): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2236): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2236): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2236): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2236): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2236): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2236): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  909): Resuming delayed broadcast
F/ClearPendingStateOp( 2236): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2236): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2236): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2236): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2236): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2236): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2236): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2236): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2236): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2236): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2236): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2236): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1212): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1428): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1428): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1428): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c8a7bd0
W/[PluginManager]RegisterService( 1428): provider may killed!
W/[PluginManager]RegisterService( 1428): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1428): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1428): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1428): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1428): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1428): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1428): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1428): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1428): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1428): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1428): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1428): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1428): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1428): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1428): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  909): Can't write: system_app_wtf
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
I/[PluginManager]RegisterService( 1428): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2923): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4768 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4728): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4728): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4728): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4728): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4728): threadid=12: thread exiting with uncaught exception (group=0x416a9e30)
E/SQLiteLog( 2923): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2923): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5c91d878
W/dalvikvm( 2923): threadid=14: thread exiting with uncaught exception (group=0x416a9e30)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms.drive
E/ActivityManager(  909): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 4728): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4728): Process: com.google.android.gms.drive, PID: 4728
E/AndroidRuntime( 4728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4728): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4728): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4728): 	at ctn.run(SourceFile:985)
E/AndroidRuntime( 2923): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2923): Process: com.google.android.googlequicksearchbox:search, PID: 2923
E/AndroidRuntime( 2923): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2923): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2923): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2923): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2923): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2923): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2923): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2923): 	at cid.d(PG:186)
E/AndroidRuntime( 2923): 	at clo.g(PG:594)
E/AndroidRuntime( 2923): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2923): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2923): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2923): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2923): 	at clr.tL(PG:827)
E/AndroidRuntime( 2923): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2923): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2923): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2923): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2923): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 4728): killProcess, pid=4728
D/Process ( 4728): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/Process ( 2923): killProcess, pid=2923
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/Process ( 2923): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
I/ActivityManager(  909): Recipient 4728
I/ActivityManager(  909): Process com.google.android.gms.drive (pid 4728) has died.
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/WifiService(  909): Client connection lost with reason: 4
D/MediaRouterService(  909): Client com.google.android.googlequicksearchbox (pid 2923): Died!
I/ActivityManager(  909): Recipient 2923
I/ActivityManager(  909): Process com.google.android.googlequicksearchbox:search (pid 2923) has died.
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b6ef10 +
I/Prism.WidgetManager( 1275): onLoadItems() +
E/SQLiteDatabase( 4768): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4768): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4768): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4768): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4768): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4768): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4768): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4768): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4768): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4768): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4768): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4768): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4768): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4768): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4768): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4768): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4768): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4768): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4768): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4768): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4768): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4768): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4768): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4768): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4768): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4768): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4768): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4768): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4768): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4768): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4768): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4768): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4768): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4768): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4768): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4768): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4768): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4768): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4768): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4768): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4768): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4768): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4768): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4768): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4768): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4768): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4768): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4768): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4768): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4768): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4768): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4768): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4768): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4768): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4768): threadid=11: thread exiting with uncaught exception (group=0x416a9e30)
E/AndroidRuntime( 4768): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4768): Process: com.google.android.apps.docs, PID: 4768
E/AndroidRuntime( 4768): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4768): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4768): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4768): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4768): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4768): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4768): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/Process ( 4768): killProcess, pid=4768
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4786 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4768): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/PackageManager(  909): Unable to load service info ResolveInfo{425c43e0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
D/Process (  909): killProcessQuiet, pid=4064
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4064:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  909): Recipient 4768
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.apps.docs (pid 4768) has died.
W/ContextImpl( 4786): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4799 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4786): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4786): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4786): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4786): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4786): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4786): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4786): threadid=10: thread exiting with uncaught exception (group=0x416a9e30)
I/ActivityManager(  909): Recipient 4064
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/AndroidRuntime( 4786): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4786): Process: com.android.keychain, PID: 4786
E/AndroidRuntime( 4786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4786): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4786): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4786): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4786): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4786): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.android.keychain
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4786): killProcess, pid=4786
D/Process ( 4786): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4799): getInstance(Context context)
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453417209315.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4786
I/ActivityManager(  909): Process com.android.keychain (pid 4786) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10222ms

```
