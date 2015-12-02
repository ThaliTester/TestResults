#### Test 52383621d5a0cb8_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,E/cutils-trace( 4901): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4901): ====startRecUseTime====
D/htc.customization.log.level( 4901):  is 
W/CustomizationLogLevel( 4901): Level value is invalid, use default level 2
D/CustomizationManager( 4901):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4901): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4901): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4901): Parsing tag category name = system
I/CustomizationCIDLoader( 4901): Parsing tag category name = application
I/CustomizationCIDLoader( 4901): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4901): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4901): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4901): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4901): Parsing tag category name = Settings
D/CustomizationManager( 4901):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4901):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4901): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4901): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4901): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4901): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4901
D/PMS     (  906): acquireHCC(43cb3388): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(422e15c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6dbbe890 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1112940624
D/PMS     (  906): acquireWL(43b109e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b13f18
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4912 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1268): [trimMemory] 20
W/asset   ( 4912): Copying FileAsset 0x5c792428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4912): Binding Chromium to main looper Looper (main, tid 1) {41b186f0}
I/LibraryLoader( 4912): Expected native library version number "",actual native library version number ""
I/chromium( 4912): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4912): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(43cc1700): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(4416b7f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/PMS     (  906): releaseWL(43cc1700): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440157c0:true
D/BluetoothAdapter( 4912): 1102242088: getState(). Returning 12
,I/Adreno-EGL( 4912): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4912): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4912): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4912): Local Branch: 
I/Adreno-EGL( 4912): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4912): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4912):                  aa63bbd948f41d15fc72f585e
W/chromium( 4912): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4912): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4912): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4912): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4912): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4912): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4912): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4912): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4912): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4912): CordovaWebView is running on device made by: HTC
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/ActivityManager(  906): Waited long enough for: ServiceRecord{423f4348 u0 com.htc.htclocationservice/.AutoSettingService}
W/AwContents( 4912): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1268
W/ResourceType( 4912): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4912): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b5f7d8, mServedView=org.apache.cordova.engine.SystemWebView{41b25440 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  906): Enable input method client, pid=4912
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4912): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +405ms
D/PMS     (  906): releaseWL(43b109e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4912): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4912): JniHelper::setJavaVM(0x415e9048), pthread_self() = 1663010416
D/JX-Cordova( 4912): jxcore cordova android initializing
W/dalvikvm( 4912): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 11.500MB for 65338-byte allocation
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 11.542MB for 98002-byte allocation
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 11.625MB for 146998-byte allocation
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 11.726MB for 220492-byte allocation
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 11.905MB for 330734-byte allocation
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 12.595MB for 744140-byte allocation
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 13.205MB for 1116206-byte allocation
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 14.132MB for 1674304-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(43cb3388): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(422e15c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 15.506MB for 2511452-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4912): Grow heap (frag case) to 17.558MB for 3767174-byte allocation
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/jxcore-log( 4912): Initializing JXcore engine
,W/jxcore-log( 4912): JXcore engine is ready
,W/jxcore-log( 4912): Starting JXcore engine
,W/jxcore-log( 4912): Platform android
W/jxcore-log( 4912): 
,W/jxcore-log( 4912): Process ARCH arm
W/jxcore-log( 4912): 
,D/PMS     (  906): releaseWL(4416b7f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4912): JXcore Cordova bridge is ready!
I/jxcore-log( 4912): 
,W/jxcore-log( 4912): JXcore engine is started
,I/chromium( 4912): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4912): Skipped 148 frames!  The application may be doing too much work on its main thread.
,E/jxcore  ( 4912): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 4912): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 4912): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4912): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  906): acquireWL(43cc0a10): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
,D/WIFI_ICON( 1115): WifiActivity: 1
,I/FeedHostManager( 1268): [onResume]
,I/FeedProviderManager( 1268): onResume
,I/SocialFeedProvider( 1268): +onResume
I/SocialFeedProvider( 1268): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1268): -onResume
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1268/10075)
,I/InputMethodManagerService(  906): Disable input method client, pid=4912
,I/InputMethodManagerService(  906): Enable input method client, pid=1268
,W/IInputConnectionWrapper( 4912): reportFullscreenMode on inactive InputConnection
,D/PMS     (  906): releaseWL(43cc0a10): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  906): killProcessQuiet, pid=4204
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  906): Killing 4204:com.google.android.music:main/u0a154 (adj 15): empty #17
,E/libEGL  ( 4912): call to OpenGL ES API with no current context (logged once per thread)
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4204
,D/MediaRouterService(  906): Client com.google.android.music (pid 4204): Died!
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): acquireWL(43866fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(43866c80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41d4e548: PendingIntentRecord{424c9dc8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=103530, Int=0
D/PMS     (  906): releaseWL(43866fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43853388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43866c80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43853388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4957 uid=10077 gids={50077}
D/PMS     (  906): acquireWL(4265f160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
V/AlarmManager(  906): sending alarm PendingIntent{42359f30: PendingIntentRecord{4238c348 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449056485507, Int=60000
,D/PMS     (  906): releaseWL(4265f160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4957): SMSBackupAgentService started
,D/SMSBackup( 4957): Checking restore status
D/SMSBackup( 4957): Restore complete
,D/SMSBackup( 4957): cancelCheckAlarm
,D/SMSBackup( 4957): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=4723
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4723:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4723
,D/WifiService(  906): Client connection lost with reason: 4
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  906): mEventCount = 1200
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:248, mTXpacketCount:248, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(425c9190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=193 rxSum=153} preTxRxSum={txSum=193 rxSum=153}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19927 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19928 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{43152ad8: PendingIntentRecord{42514f38 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=107896, Int=0
D/PMS     (  906): releaseWL(425c9190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4215beb0
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  906): setLight #0: color=#0
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4215beb0, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fe5830
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@4283db70
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 373ms
D/PMS     (  906): nativeSetInteractive:false
,D/PMS     (  906): nativeSetInteractive:false done
,D/PMS     (  906): nativeSetAutoSuspend:true
,D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
,D/PMS     (  906): OOBE c monitor 11
,I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,D/NfcService( 1251): ScreenObserver: OFF
,D/NfcService( 1251): applyRouting - 0
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43244a00)
,D/NfcService( 1251): applyRouting -2
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): Disable input method client, pid=1268
D/PMS     (  906): acquireWL(4335c570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(4386a100): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/PMS     (  906): releaseWL(4386a100): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  906): releaseWL(4335c570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,D/MtpService( 2008): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2008): [MTP][onReceive]-
,D/NfcService( 1251): applyRouting - 0
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  906): acquireWL(4401fb00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/AutoSetting( 1416): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1251): applyRouting -2
D/PMS     (  906): releaseWL(4401fb00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1416): service - onCreate()
,D/AutoSetting( 1416): service - AddressCache: using context: com.htc.Weather
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/AutoSetting( 1416): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  906): request 424abef8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19929 delay=15s
,D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
,I/ClockThread( 1115): stop update clock
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/TetherSettings( 4839): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4839): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4839): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4839): Cust_ConnectToPC   : spcsc>false
,D/        ( 4839): Cust_ConnectToPC   : IPT>true
,D/        ( 4839): Cust_ConnectToPC   : Singel_USB>false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
W/Settings( 4839): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
E/SmartNS_Utility( 4839): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4839): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4839): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4839): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): SET_SCREEN_ON:On
I/wpa_supplicant( 1171): htc_wext_set_keepalive +
I/wpa_supplicant( 1171): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1171): getPrivFuncNum +	
I/wpa_supplicant( 1171): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,W/ContextImpl( 4839): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 4839): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4839): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4839):  defaultType:0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  906): updateScreenOn: false
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4981 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(4319b850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1453 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1767): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): onScreenOn: 1449056492382
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1767): onScreenOn: 1449056492382
D/PMS     (  906): releaseWL(4319b850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fe5830
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fe5830, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@4283db70
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43c899d8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
,I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b13f18
I/SocialFeedProvider( 1268): +onPause
,I/SocialFeedProvider( 1268): -onPause
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19929 mDataStallAlarmIntent=PendingIntent{41f32328: PendingIntentRecord{42514f38 android broadcastIntent}}
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
W/ContextImpl( 4981): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): SET_SCREEN_ON:Off
I/wpa_supplicant( 1171): htc_wext_set_keepalive +
I/wpa_supplicant( 1171): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1171): getPrivFuncNum +	
I/wpa_supplicant( 1171): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1171): get_ip_address source addr = c0a8016c
I/wpa_supplicant( 1171): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1171): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43949258): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43c899d8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  906): acquireWL(43c0c0d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4981 1000 null
V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4981): isEpsOn(), nState = 0
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): releaseWL(43949258): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(43c0c0d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4981): getMobilePolicyEnabled, result = true
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4981): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4981): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4981): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4981): getMobilePolicyEnabled, result = true
D/WifiService(  906): New client listening to asynchronous messages
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] getTotalRam: 1873 Mb
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4283db70
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4283db70, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4283db70, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1767): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1767): onScreenOff
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4283db70
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  906): acquireWL(4403f0d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1453 10028 null
D/PMS     (  906): releaseWL(4403f0d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1416): service - mHandler: cancel location update
,D/AutoSetting( 1416): service -           changes count: 0
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42402dc8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42402dc8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1513): service - handleMessage() stop self
,D/AutoSetting( 1513): service - onDestroy() END
,D/AutoSetting( 1513): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4748
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4748:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4748
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4342
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4342:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4342
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43bd2ca8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(434aa780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(434aa780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43870650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=138582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43870650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1416): service - handleMessage() stop self
,D/AutoSetting( 1416): service - handleMessage() quit looper
,D/AutoSetting( 1416): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4682
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4682:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4682
,D/PMS     (  906): acquireWL(43851b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{43875f60: PendingIntentRecord{423a3358 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141142, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42456c70: PendingIntentRecord{42502470 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141406, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  906): acquireWL(43020508): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): acquireWL(440ba980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  906): releaseWL(43851b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): releaseWL(440ba980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7df5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 41
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(43020508): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,W/GA-SERVICE( 2225): Thread[Thread-183,5,main]: hit:_gmsv=1-5089038&ul=en-gb&sr=720x1184&ht=1449056414828&a=2094579130&sc=start&AppUID=10151&aid=com.google.android.apps.magazines&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&cd16=Ignoring+sync+request+for+non-current+account&v=1&t=appview&an=Google+Play+Newsstand&cd11=false&tid=UA-32428711-6&_u=.nOQKSTB&_v=ma1b6&cd=Debug&qt=124951&z=67
,W/GA-SERVICE( 2225): Thread[Thread-183,5,main]: hit:_gmsv=1-5089038&ev=0&ul=en-gb&sr=720x1184&ht=1449056414829&a=494272528&AppUID=10151&aid=com.google.android.apps.magazines&ea=Sync+Skipped&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&ec=Debug&v=1&t=event&el=&an=Google+Play+Newsstand&tid=UA-32428711-6&_u=.C&_v=ma1b6&cd=Debug&qt=124950&z=68
D/libc    ( 2225): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
D/libc    ( 2225): [NET] getaddrinfo-,err=8
D/libc    ( 2225): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    ( 2225): [NET] getaddrinfo-, 1
,D/libc    ( 2225): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a3f0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 114
D/libc    (  364): [NET]res_nsend:resplen=102
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2225): [NET] getaddrinfo_proxy-, success
I/global  ( 2225): call createSocket() return a new socket.
D/libc    ( 2225): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2225): [NET] getaddrinfo-, SUCCESS
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43850430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43850430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4391ccb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43768008: PendingIntentRecord{438170c8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174895, Int=0
,D/PMS     (  906): releaseWL(4391ccb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(4405fa38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(4405fa38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(44073b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=198583, Int=0,
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44073b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c1cf78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42c1cf78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4346d288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4346d288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(437a3158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=258583, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437a3158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426dd1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426dd1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43853d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(43853d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42c176c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=318582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c176c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43c3cd50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  906): releaseWL(43c3cd50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1115): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,W/GLSActivity( 1371): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1371): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1371): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1371): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1371): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1371): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1371): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1371): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1552): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 4390): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4390): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4390): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4390): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4390): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4390): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4390): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4390): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e30c30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 13 3 12
,D/libc    ( 4390): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4390): [NET] getaddrinfo-,err=8
D/libc    ( 4390): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4390): [NET] getaddrinfo-, 1
,D/libc    ( 4390): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =98af +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4390): [NET] getaddrinfo_proxy-, success
I/global  ( 4390): call createSocket() return a new socket.
D/libc    ( 4390): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4390): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4390): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4390): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(4376cf78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4376cf78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(436dcf70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=378582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(436dcf70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(44067f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44067f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42c29178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c29178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42ca9978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=438583, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ca9978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(436db3b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(436db3b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(438c21f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=498582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438c21f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42cd2438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  906): releaseWL(42cd2438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43752290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43752290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4261ebb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=558582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4261ebb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43211f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43211f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42ec3cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=618583, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ec3cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1242): sku_id=99
,D/ContactMessageStore( 1242): start background delete task...
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/PMS     (  906): acquireWL(43727640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43727640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  906): killProcessQuiet, pid=4780
,I/ActivityManager(  906): Killing 4780:com.htc.backup/1000 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4780
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4428cf40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=678582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4428cf40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4418ed70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4418ed70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b16550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b16550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43ac52b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=738582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ac52b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4386ee50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4386ee50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(431da720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(431da720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42c2ab60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=798582, Int=0
,D/PMS     (  906): releaseWL(42c2ab60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c25048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c25048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426a83a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=858583, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426a83a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4266c3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4266c3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42665190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=918583, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42665190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4265f160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/BatteryService(  906): n_update end
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4265f160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425fd8c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PMS     (  906): releaseWL(425fd8c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42363810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=978582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42363810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41b6eff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41dea218: PendingIntentRecord{42468640 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=793380, Int=0
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds,
,I/ActivityManager(  906): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=5031 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  906): sending alarm PendingIntent{44104338: PendingIntentRecord{43966cb0 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{4200f320: PendingIntentRecord{41c67bd8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928010, Int=0
,D/PMS     (  906): acquireWL(425f2e88): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1371 10028 null
,D/PMS     (  906): releaseWL(425f2e88): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5043 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{425d3640: PendingIntentRecord{4241a8a8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449056602334, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{43732640: PendingIntentRecord{4249c2a0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449057084328, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{4257c038: PendingIntentRecord{42573360 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449057322514, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{41ebcab8: PendingIntentRecord{434bc9e0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449057392532, Int=0
,D/PMS     (  906): acquireWL(42ca6da8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  906): acquireWL(425e7790): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2225 10028 null
,D/PMS     (  906): releaseWL(42ca6da8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(42627d90): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2225 10028 null
,I/EventLogService( 2225): Aggregate from 1449056435943 (log), 1449055284263 (data)
D/PMS     (  906): releaseWL(425e7790): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
W/ContextImpl( 4981): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4981): call getInstance()
,D/SmartSyncUtils( 4981): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4981): MY_DEBUG = false
D/PMS     (  906): releaseWL(41b6eff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(4259f250): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4981 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4981): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4981): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 20, nEnd = 0, bNormalRange = true
I/ImageRamCache( 5031): create image Cache, size: 31457280.
I/ImageRamCache( 5031): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 5031): create image Cache, size: 12582912.
,I/FeedSettings( 5031): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5031): GroupBudget 0.500000 0.380000
,I/FeedSettings( 5031): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5031): changeLocale(): en_GB
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (5043/10047)
W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/Prism.AllAppsOptionsMa_( 5031): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 5031): loadGridSize() with Alternative
,D/PMS     (  906): releaseWL(42627d90): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/SmartSyncScreenOnOffTimeReceiver( 4981): [updateNmRange] new USERNIGHT_TIMESTART = 20, new USERNIGHT_TIMEEND = 0
,D/SmartSyncScreenOnOffTimeReceiver( 4981): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4981): SettingOnTime = 1449097200000, randomSettingOnTime = 1449096965000
D/SmartSyncScreenOnOffTimeReceiver( 4981): SettingOffTime = 1449082800000, randomSettingOffTime = 1449089117000
,I/FeedHostManager( 1268): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,I/FeedHostManager( 1268): NightMode begin at 0, end at 7
,D/SmartSyncScreenOnOffTimeReceiver( 4981): bDayMode = false
W/ContextImpl( 4981): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,D/PMS     (  906): acquireWL(4362e370): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1268 10075 null
D/SmartSyncScreenOnOffTimeReceiver( 4981): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4981): bNightModeTurnOffOnce = false
,I/FeedHostManager( 1268): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1449057392754, BeginTime: 1449097200000, EndTime: 1449122400000
D/PMS     (  906): releaseWL(4259f250): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  906): releaseWL(4362e370): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/libc    ( 5031): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 5031): [NET] getaddrinfo-,err=8
D/libc    ( 5031): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 5031): [NET] getaddrinfo-, 1
,D/libc    ( 5031): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6feb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=4767
,I/ActivityManager(  906): Killing 4767:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4767
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4428cf40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4428cf40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=206
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 5031): [NET] getaddrinfo_proxy-, success
D/PMS     (  906): acquireWL(44021348): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
,D/GCM     ( 1371): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1371/10028)
,D/PMS     (  906): acquireWL(44012d30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  906): releaseWL(44021348): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): releaseWL(44012d30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (5031/10075)
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (5031/10075)
,D/Process (  906): killProcessQuiet, pid=4800
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4800:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4800
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43cc2f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(43cc2f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b61590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1038582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b61590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b4d0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(43b4d0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4386aa50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4386aa50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4386a2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1098582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4386a2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43869d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43869d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(438690e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1158583, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438690e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(438686e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(438686e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43866fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1218583, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43866fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43865b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43865b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(436c8ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436c8ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43642cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1278582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43642cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(436427c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436427c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43633460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1338582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43633460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4360ab78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4360ab78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(436087f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1398583, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(436087f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426f46a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/PMS     (  906): releaseWL(426f46a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42513aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42513aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42187ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1458582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42187ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4253bb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4253bb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4243bc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1518583, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4243bc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42380148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42380148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424c0ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424c0ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4220ceb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1578582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4220ceb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4263ff60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4263ff60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42007018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42007018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(423f9bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1638582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423f9bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44077df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(44077df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4200e4c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1698582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4200e4c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425914f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425914f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42454200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42454200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425b4b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1758583, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425b4b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42404278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(42404278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(42560ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42560ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(4258ba40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1818582, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  906): Prepared write state in 40ms
,D/PMS     (  906): releaseWL(4258ba40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-16-08.bin
,I/ProcessStatsService(  906): Prepared write state in 42ms
,I/ProcessStatsService(  906): Prepared write state in 19ms
,D/PMS     (  906): acquireWL(425c83c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425c83c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(423936a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423936a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4263b008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4237e428: PendingIntentRecord{42123288 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1878583, Int=0
,D/Process (  906): killProcessQuiet, pid=4559
,I/ActivityManager(  906): Killing 4559:com.google.android.gm/u0a107 (adj 15): empty for 1800s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  906): killProcessQuiet, pid=4312
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  906): killProcessQuiet, pid=3961
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4312:com.htc.mediamanager/u0a32 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 3961:com.htc.task/u0a70 (adj 15): empty for 1801s
,D/Process (  906): killProcessQuiet, pid=4815
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
I/ActivityManager(  906): Killing 4815:com.google.android.apps.plus/u0a160 (adj 15): empty for 1801s
,I/ActivityManager(  906): Recipient 4559
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4312
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(4263b008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  906): Recipient 4815
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3961
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5082): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5082): ====startRecUseTime====
D/htc.customization.log.level( 5082):  is 
W/CustomizationLogLevel( 5082): Level value is invalid, use default level 2
D/CustomizationManager( 5082):  Read ACC file spent 0.056 (s)
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5082): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5082): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5082): Parsing tag category name = system
I/CustomizationCIDLoader( 5082): Parsing tag category name = application
I/CustomizationCIDLoader( 5082): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5082): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5082): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5082): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5082): Parsing tag category name = Settings
D/CustomizationManager( 5082):  Read CID file spent 0.094 (s)
D/CustomizationManager( 5082):  All configurations done spent 0.095 (s)
W/HtcNativeFlag( 5082): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5082): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5082): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5082): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=5082, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4912
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 4912:com.test.thalitest/u0a348 (adj 15): stop com.test.thalitest
D/Process (  906): killProcessQuiet, pid=4878
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4864
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4878:com.android.settings:remote/1000 (adj 15): empty for 1828s
I/ActivityManager(  906): Killing 4864:com.htc.calendar/u0a13 (adj 15): empty for 1828s
W/asset   (  906): Copying FileAsset 0x631c8ad0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Recipient 4864
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4878
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{4228c110 com.example.hello/10355} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1552): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1552): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1552): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1453): Ignoring removeGeofence because network location is disabled.
I/acms    ( 1861): Unregistering com.test.thalitest
E/acms    ( 1861): Could not unregister removed application com.test.thalitest
D/PMS     (  906): acquireWL(426e1628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1453 10028 null
D/PMS     (  906): releaseWL(426e1628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Prism.ItemManager( 5031): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5031): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/Launcher( 1268): Deferring update until onResume
D/Launcher( 1268): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
D/PackageBroadcastService( 2225): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=5097 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 5097): install
I/MultiDex( 5097): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5097): loading existing secondary dex files
I/MultiDex( 5097): load found 1 secondary dex files
I/MultiDex( 5097): install done
I/PeopleContactsSync( 2225): CP2 sync disabled
I/ActivityManager(  906): Delaying start of: ServiceRecord{44184e78 u0 com.google.android.gms/.wearable.service.WearableControlService}
D/PMS     (  906): acquireWL(43cd0d40): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2225, uid=10028, userID:0
I/Icing   ( 2225): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 5097): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  906): releaseWL(43cd0d40): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5115 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 5115): install
I/MultiDex( 5115): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5115): loading existing secondary dex files
I/MultiDex( 5115): load found 1 secondary dex files
I/MultiDex( 5115): install done
I/ActivityManager(  906): Resuming delayed broadcast
I/ProviderInstaller( 5115): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1416): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1416): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
D/Process (  906): killProcessQuiet, pid=4957
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  906): Killing 4957:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
I/IcingCorporaProvider( 3257): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Recipient 4957
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5134 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  906): acquireWL(435c01f0): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
W/PackageManager(  906): Unable to load service info ResolveInfo{424f72a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteLog( 5097): (3850) statement aborts at 134: [DELETE FROM FileContent24 WHERE hash IN WipeoutFileContentHashView] disk I/O error
E/SQLiteDBG( 5097): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca497a0
E/DocListDatabase( 5097): Failed to delete from FileContent24
E/DocListDatabase( 5097): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 5097): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 5097): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 5097): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 5097): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 5097): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 5097): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 5097): 	at cva.j(SourceFile:1094)
E/DocListDatabase( 5097): 	at chh.run(SourceFile:272)
E/DocListDatabase( 5097): 	at crv.run(SourceFile:48)
E/DocListDatabase( 5097): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 5097): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 5097): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 5097): threadid=12: thread exiting with uncaught exception (group=0x416e1e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 5097): FATAL EXCEPTION: pool-4-thread-1
E/AndroidRuntime( 5097): Process: com.google.android.gms.drive, PID: 5097
E/AndroidRuntime( 5097): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5097): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5097): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 5097): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5097): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5097): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 5097): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 5097): 	at cva.j(SourceFile:1094)
E/AndroidRuntime( 5097): 	at chh.run(SourceFile:272)
E/AndroidRuntime( 5097): 	at crv.run(SourceFile:48)
E/AndroidRuntime( 5097): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5097): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5097): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 5097): killProcess, pid=5097
E/SQLiteLog( 5097): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 5097): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca497a0
D/Process ( 5097): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/IcingCorporaProvider( 3257): UpdateCorporaTask done [took 201 ms] updated apps [took 201 ms] 
W/BroadcastQueue(  906): Skipping deliver [background] BroadcastRecord{43a96070 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{42468eb0 5097 com.google.android.gms.drive/10028/u0 remote:425612a8}: process crashing
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 5097
E/SQLiteDatabase( 5134): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5134): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5134): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5134): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5134): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5134): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5134): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5134): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5134): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5134): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5134): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5134): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5134): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5134): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5134): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5134): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5134): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5134): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5134): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5134): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5134): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5134): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5134): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5134): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5134): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5134): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5134): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5134): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5134): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5134): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5134): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5134): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5134): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5134): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5134): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5134): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5134): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5134): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5134): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5134): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5134): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5134): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5134): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5134): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5134): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5134): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5134): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5134): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5134): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5134): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5134): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5134): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5134): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5134): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5134): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5134): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 5097) has died.
W/SQLiteOpenHelper( 5134): Opened ClientFlag.db in read-only mode
W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
F/ProcessStats(  906): Starting service ServiceState{426ae200 com.google.android.gms.drive.api.ApiService pkg=com.google.android.gms proc=426ae200} without owner
E/SQLiteDatabase( 5134): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5134): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5134): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5134): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5134): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5134): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5134): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5134): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5134): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5134): threadid=11: thread exiting with uncaught exception (group=0x416e1e30)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/AndroidRuntime( 5134): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5134): Process: com.google.android.apps.docs, PID: 5134
E/AndroidRuntime( 5134): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5134): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5134): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5134): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5134): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5134): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5134): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5134): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1449058293121.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  906): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  906): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  906): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  906): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  906): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4131)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
E/ErrorReport(  906): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
E/ErrorReport(  906): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 18 more
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
I/TrimMemoryManager( 1268): [trimMemory] 5
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 5134): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5134): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5134): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5134): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5134): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5134): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5134): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5134): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5134): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5134): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5134): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5134): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5134): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5134): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5134): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5134): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5134): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5134): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5134): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5134): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5134): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5134): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5134): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5134): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5134): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5134): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5134): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5134): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5134): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5134): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5134): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5134): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5134): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5134): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5134): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5134): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5134): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5134): Opened ClientFlag.db in read-only mode
D/Process ( 5134): killProcess, pid=5134
D/Process ( 5134): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5160 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 5134
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 5134) has died.
W/ContextImpl( 5160): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5174 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5160): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5160): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5160): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5160): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5160): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5160): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5160): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5160): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5160): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5160): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5160): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5160): threadid=10: thread exiting with uncaught exception (group=0x416e1e30)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5160): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5160): Process: com.android.keychain, PID: 5160
E/AndroidRuntime( 5160): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5160): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5160): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5160): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5160): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5160): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5160): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5160): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5160): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5160): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5160): killProcess, pid=5160
D/Process ( 5160): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449058293346.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 5160
D/AppTag  ( 5174): getInstance(Context context)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 5160) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10744ms
D/AppTag  ( 5174): getInstance(Context context)
D/AppTag  ( 5174): onCreate()
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5189 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
F/ProcessStats(  906): Starting service ServiceState{426ae200 com.google.android.gms.drive.api.ApiService pkg=com.google.android.gms proc=426ae200} without owner
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1449058293404.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  906): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  906): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  906): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  906): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  906): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16827)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16804)
E/ErrorReport(  906): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1897)
E/ErrorReport(  906): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1846)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.serviceDoneExecuting(ActivityManagerService.java:13937)
E/ErrorReport(  906): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:919)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
E/ErrorReport(  906): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  906): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 23 more
D/PMS     (  906): acquireWL(44115988): PARTIAL_WAKE_LOCK  AsyncService 0x1 5189 10160 null
E/SQLiteDatabase( 5189): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 5189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5189): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 5189): 	at del.a(PG:264)
E/SQLiteDatabase( 5189): 	at eeq.run(PG:187)
E/SQLiteDatabase( 5189): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5210 uid=10098 gids={50098, 3003, 5012}
D/PMS     (  906): releaseWL(44115988): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/SQLiteDatabase( 5189): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 5189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5189): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 5189): 	at del.a(PG:264)
E/SQLiteDatabase( 5189): 	at eeq.run(PG:187)
E/SQLiteDatabase( 5189): 	at java.lang.Thread.run(Thread.java:864)
D/Process (  906): killProcessQuiet, pid=1513
E/EsApplication( 5189): Failed app initialization
E/EsApplication( 5189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 5189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 5189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 5189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 5189): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 5189): 	at del.a(PG:264)
E/EsApplication( 5189): 	at eeq.run(PG:187)
E/EsApplication( 5189): 	at java.lang.Thread.run(Thread.java:864)
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 1513:com.htc.bgp/u0a14 (adj 15): empty for 1801s
I/DeviceManagement( 5210): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5210 dbg=false s=true
I/DeviceManagement( 5210): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5210): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5210): WorkflowService: Starting workflow service
I/DeviceManagement( 5210): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b47210] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5210): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5210): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5210): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5210): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 5210): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5210): SessionStateController: Checking invariants...
I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5224 uid=10099 gids={50099, 3003, 5012}
D/Documents( 5224): Loading roots for com.android.providers.downloads.documents
D/Documents( 5224): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5224): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5224): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5224): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5224): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5224): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5224): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5224): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5224): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5224): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5224): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5224): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5224): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5224): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5224): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5224): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5224): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5224): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5224): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5224): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5224): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5224): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5224): threadid=1: thread exiting with uncaught exception (group=0x416e1e30)
E/AndroidRuntime( 5224): FATAL EXCEPTION: main
E/AndroidRuntime( 5224): Process: com.android.documentsui, PID: 5224
E/AndroidRuntime( 5224): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5224): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5224): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5224): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5224): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5224): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5224): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5224): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5224): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5224): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5224): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5224): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5224): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteConnection.nativeOpen,(Native Method)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5224): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5224): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5224): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5224): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5224): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5224): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5224): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5224): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5224): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5224): 	... 10 more
E/ActivityManager(  906): App crashed! Process: com.android.documentsui
I/ActivityManager(  906): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5238 uid=10023 gids={50023, 1028, 1015, 1023}
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449058293687.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 1513
D/Process ( 5224): killProcess, pid=5224
D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/Process ( 5224): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 5224
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.documentsui (pid 5224) has died.
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
E/SQLiteDatabase( 5210): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5210): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5210): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5210): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5210): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5210): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5210): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5210): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5210): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5210): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5210): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5210): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5210): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5210): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel
```
