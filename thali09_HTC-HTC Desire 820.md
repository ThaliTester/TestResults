#### Test 568182548138a64_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system,
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
--------- beginning of /dev/log/main
E/cutils-trace( 4551): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4551): ====startRecUseTime====
D/htc.customization.log.level( 4551):  is 
W/CustomizationLogLevel( 4551): Level value is invalid, use default level 2
D/CustomizationManager( 4551):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4551): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4551): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4551): Parsing tag category name = system
I/CustomizationCIDLoader( 4551): Parsing tag category name = application
I/CustomizationCIDLoader( 4551): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4551): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4551): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4551): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4551): Parsing tag category name = Settings
D/CustomizationManager( 4551):  Read CID file spent 0.103 (s)
D/CustomizationManager( 4551):  All configurations done spent 0.103 (s)
W/HtcNativeFlag( 4551): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4551): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4551): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4551): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  913): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  913): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  913): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  913): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  913): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  913): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  913): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4551
D/PMS     (  913): acquireHCC(4354fed8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 913 1000 null
D/PMS     (  913): acquireHCC(44314978): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 913 1000 null
I/Intent  (  913): @test_code: getHtcIntentFlag: 0 obj: 1138945144
D/PMS     (  913): acquireWL(426b72a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 913 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c55d70
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  913): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4562 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4562): Binding Chromium to main looper Looper (main, tid 1) {41b0d490}
I/LibraryLoader( 4562): Expected native library version number "",actual native library version number ""
I/chromium( 4562): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4562): Initializing chromium process, renderers=0
W/System.err(  913): java.lang.Throwable: stack dump
W/System.err(  913): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  913): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  913): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  913): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  913): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  913): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  913): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ece400:true
D/PMS     (  913): acquireWL(443c0a08): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): acquireWL(443a80d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): releaseWL(443a80d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4562): 1102196424: getState(). Returning 12
I/Adreno-EGL( 4562): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4562): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4562): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4562): Local Branch: 
I/Adreno-EGL( 4562): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4562): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4562):                  aa63bbd948f41d15fc72f585e
W/chromium( 4562): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4562): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4562): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4562): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4562): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4562): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4562): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4562): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4562): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4562): CordovaWebView is running on device made by: HTC
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/AwContents( 4562): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  913): Disable input method client, pid=1273
I/ActivityManager(  913): Displayed com.test.thalitest/.MainActivity: +389ms
I/InputMethodManagerService(  913): Enable input method client, pid=4562
W/ResourceType( 4562): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4562): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b54578, mServedView=org.apache.cordova.engine.SystemWebView{41b1a1e0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4562): nativeOnDraw failed; clearing to background color.
D/PMS     (  913): releaseWL(426b72a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4562): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4562): JniHelper::setJavaVM(0x415e2048), pthread_self() = 1663971760
I/chromium( 4562): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 11.995MB for 42652-byte allocation
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 12.072MB for 95956-byte allocation
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 12.152MB for 143930-byte allocation
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 12.266MB for 215890-byte allocation
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 12.442MB for 323830-byte allocation
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 12.712MB for 485740-byte allocation
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 13.693MB for 1092904-byte allocation
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 14.625MB for 1639352-byte allocation
,I/ActivityManager(  913): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4606 uid=10078 gids={50078}
,D/PMS     (  913): acquireWL(442bd160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10078}
,V/AlarmManager(  913): sending alarm PendingIntent{424b6a40: PendingIntentRecord{424b6a08 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453415991256, Int=60000
,D/PMS     (  913): releaseWL(442bd160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4606): SMSBackupAgentService started
,D/SMSBackup( 4606): Checking restore status
D/SMSBackup( 4606): Restore complete
,D/SMSBackup( 4606): cancelCheckAlarm
,D/SMSBackup( 4606): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/Process (  913): killProcessQuiet, pid=4298
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4298:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4298
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 150
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 15.881MB for 2459024-byte allocation
,D/WifiDataStallTracker(  913): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  913): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  913): acquireWL(4381e080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
D/WifiDataStallTracker(  913): updateDataStallInfo: mDataStallTxRxSum={txSum=116 rxSum=109} preTxRxSum={txSum=61 rxSum=47}
D/WifiDataStallTracker(  913): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  913): onDataStallAlarm: tag=22617 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=22618 delay=15s
V/AlarmManager(  913): sending alarm PendingIntent{423aa620: PendingIntentRecord{4262c0d0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104599, Int=0
D/PMS     (  913): releaseWL(4381e080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/CpuWake (  913): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  913): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  913): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  913): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  913): >>release mCpuPerf_Freq wakelock
W/CpuWake (  913): <<release mCpuPerf_Freq wakelock
D/PMS     (  913): releaseHCC(4354fed8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  913): releaseHCC(44314978): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4562): Grow heap (frag case) to 18.065MB for 3688532-byte allocation
,W/jxcore-log( 4562): Initializing JXcore engine
,W/jxcore-log( 4562): JXcore engine is ready
,W/jxcore-log( 4562): Starting JXcore engine
,W/jxcore-log( 4562): Platform android
W/jxcore-log( 4562): 
,W/jxcore-log( 4562): Process ARCH arm
W/jxcore-log( 4562): 
,I/jxcore-log( 4562): JXcore Cordova bridge is ready!
I/jxcore-log( 4562): 
,W/jxcore-log( 4562): JXcore engine is started
,E/jxcore  ( 4562): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4562): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4562): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  913): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4562): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  913): acquireWL(4381b220): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 913 1000 null
,I/FeedHostManager( 1273): [onResume]
,I/FeedProviderManager( 1273): onResume
,I/SocialFeedProvider( 1273): +onResume
I/SocialFeedProvider( 1273): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1273): -onResume
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.launcher (1273/10076)
,I/InputMethodManagerService(  913): Disable input method client, pid=4562
,W/IInputConnectionWrapper( 4562): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  913): Enable input method client, pid=1273
,D/PMS     (  913): releaseWL(443c0a08): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  913): acquireWL(4380c580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10074}
,V/AlarmManager(  913): sending alarm PendingIntent{4240f740: PendingIntentRecord{43d054c0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453415992842, Int=0
,D/PMS     (  913): releaseWL(4381b220): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/PMS     (  913): releaseWL(4380c580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,E/libEGL  ( 4562): call to OpenGL ES API with no current context (logged once per thread)
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/Finsky  ( 4249): [446] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4249): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  913): killProcessQuiet, pid=4332
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4332:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4332
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(41e59df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41b6b320: PendingIntentRecord{42502938 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=106670, Int=0
,D/PMS     (  913): acquireWL(41be6e20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 913 1000 null
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): releaseWL(41e59df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(423b5e10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(41be6e20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  913): releaseWL(423b5e10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 189
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  913):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  913): mEventCount = 1050
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{432b9bf8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 228
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true,
D/WifiStateMachine(  913): [ScoreAP] + current TXpacket:157, mTXpacketCount:157, avgLinkspeed:45,mAvgTxRate54,
,D/WifiStateMachine(  913): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB,
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/LightsService(  913): setLight #0: color=#24
,V/LightsService(  913): setLight #0: color=#21
,V/LightsService(  913): setLight #0: color=#17
,V/LightsService(  913): setLight #0: color=#14
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  913): acquireWL(4246ed80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=113096, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/ClockThread( 1117): now=1453416000055 next=59945
D/PMS     (  913): releaseWL(4246ed80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 39
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97",
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true,
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 78
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  913): Going to sleep due to screen timeout...
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421a20e0
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  913): disable: get sensor name = CM36282 Light sensor
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421a20e0, eanble = 0, strlen(mName) = 59
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  913): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ec76d0
W/SensorService(  913): Listener[1] = com.htc.smartdim.sensor_eye@42f9ee80
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  913): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  913): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  913): mWirelessDisplayManager is null
W/BatSI   (  913): Couldn't get kernel wake lock stats
V/LightsService(  913): setLight #2: color=#0
D/qdlights(  913): set_light_buttons_func: on=0 brightness=0
V/LightsService(  913): setLight #0: color=#0
,D/SurfaceControl(  913): Excessive delay in blankDisplay() while turning screen off: 327ms
,D/PMS     (  913): nativeSetInteractive:false
D/PMS     (  913): nativeSetInteractive:false done
D/PMS     (  913): nativeSetAutoSuspend:true
,D/PMS     (  913): nativeSetAutoSuspend:true done
D/HABCtrl (  913): TPE algorithm. remove timeout.
,D/PMS     (  913): OOBE c monitor 11
,I/InputManager(  913): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  913): screenObserver, isScreenOn=false
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  913): Disable input method client, pid=1273
D/PMS     (  913): acquireWL(42d8e6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,V/KeyguardServiceDelegate(  913): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@443bfd18)
,D/NfcService( 1254): applyRouting -2
D/PMN     (  913): wakingUp
D/PMS     (  913): acquireWL(43de1798): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  913): releaseWL(42d8e6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/KeyguardServiceDelegate(  913): **** SHOWN CALLED ****
,D/PMS     (  913): releaseWL(43de1798): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  913): No lock screen! windowToken=null
D/PMN     (  913): onScreenOn
,D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  913): ACTION_SCREEN_ON
I/AlarmManager(  913): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  913): [AlarmQueuing] done recovering
I/AlarmManager(  913): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  913): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 2375): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2375): [MTP][onReceive]-
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): applyRouting -2
D/PMS     (  913): runPSCheck
D/PMS     (  913): acquireWL(438e9e40): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/ClockThread( 1117): stop update clock
D/WirelessDisplayService(  913): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  913): releaseWL(438e9e40): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  913): startDataStallAlarm: tag=22619 delay=15s
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/ActivityManager(  913): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4630 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): SET_SCREEN_ON:On
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1134): BG scan when screen On
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1134): wpa_supplicant_scan enter
I/wpa_supplicant( 1134): Match BG scan, scan!
I/wpa_supplicant( 1134): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1134): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1134): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=on,
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  913): updateScreenOn: false
,W/ContextImpl( 4630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/SmartSyncUtils( 4630): isEpsOn(), nState = 0
D/PMS     (  913): acquireWL(425b4b28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4630 1000 null
D/PMS     (  913): acquireWL(4357ea48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(4357ea48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(439b1718): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1739): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1739): onScreenOn: 1453416005964
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1739): onScreenOn: 1453416005964
D/PMS     (  913): releaseWL(439b1718): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(425b4b28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ec76d0
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ec76d0, eanble = 0, strlen(mName) = 91
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  913): Listener[0] = com.htc.smartdim.sensor_eye@42f9ee80
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  913): goingToSleep
,I/FeedHostManager( 1273): [onPause]
,I/FeedProviderManager( 1273): onPause
,D/PMS     (  913): acquireWL(43cd4e28): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 913 1000 null
I/SocialFeedProvider( 1273): +onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c55d70
I/SocialFeedProvider( 1273): -onPause
,D/SmartSyncUtils( 4630): getMobilePolicyEnabled, result = true
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  913): releaseWL(43cd4e28): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/Process (  913): killProcessQuiet, pid=4348
,D/AutoSetting( 1346): receiver - intent: android.intent.action.USER_PRESENT
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4348:com.htc.backup/1000 (adj 15): empty #17
D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  913): stopDataStallAlarm: current tag=22619 mDataStallAlarmIntent=PendingIntent{42f91c08: PendingIntentRecord{4262c0d0 android broadcastIntent}}
,D/AutoSetting( 1346): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 4193): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4193): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4193): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4193): Cust_ConnectToPC   : spcsc>false
D/        ( 4193): Cust_ConnectToPC   : IPT>true
D/        ( 4193): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4193): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4193): hasRemovableStorageSlot: true
D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 0
,D/SmartNS_Utility( 4193): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4193): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AlarmManager(  913): ACTION_SCREEN_OFF
I/AlarmManager(  913): [AlarmQueuing] screen off now: 
I/AlarmManager(  913): [AlarmQueuing] data connection: true
I/AlarmManager(  913): [AlarmQueuing] wifi connection: true
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
D/PMS     (  913): acquireWL(443bb6c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 913 1000 null
,I/PSReceiver( 4193): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4193): onReceive:android.intent.action.USER_PRESENT
I/ActivityManager(  913): Recipient 4348
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4193): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4193):  defaultType:0
,W/ContextImpl( 4630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4630): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4630): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4630): getMobilePolicyEnabled, result = true
D/WifiService(  913): New client listening to asynchronous messages
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 39
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): SET_SCREEN_ON:Off
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1134): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  913):    returned true
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 117
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97,
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f9ee80
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 1
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f9ee80, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 0
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f9ee80, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f9ee80
,V/SRS_Proc(  371): ParamSet string: screen_state=off
E/ActivityThread(  913): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@432cb590 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@432cb590 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  913): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  913): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  913): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  913): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  913): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  913): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  913): 	at dalvik.system.NativeStart.main(Native Method)
D/NetworkPolicy(  913): updateScreenOn: false
,D/ContactMessageStore( 1239): start background delete task...
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/AutoSetting( 1346): service - mHandler: cancel location update
,D/AutoSetting( 1346): service -           changes count: 0
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] getTotalRam: 1873 Mb
D/PMS     (  913): acquireWL(4433bda8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(4433bda8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(43d9ecd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1739): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1739): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1739): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1739): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1739): onScreenOff
D/PMS     (  913): releaseWL(43d9ecd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(443bb6c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1134): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1134): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1134): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1134): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1134): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): Selecting BSS from priority group 1
I/wpa_supplicant( 1134): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1134): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1134): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1134): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1134):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1134):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1134): Start print parameters
I/wpa_supplicant( 1134): wpa_s->wpa_state is 9
I/wpa_supplicant( 1134): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1134): isConcurrentMode() is 0
I/wpa_supplicant( 1134): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1134): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1134): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1134): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1134): wpa_s->reassociate is 0
I/wpa_supplicant( 1134): wpa_s->is_screen_on 0
I/wpa_supplicant( 1134): wpa_s->ifname wlan0
I/wpa_supplicant( 1134): End print parameters
I/wpa_supplicant( 1134): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1134): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1134): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1134): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): W,PS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1134): State: DISCONNECTED -> INACTIVE
,D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  913): doString: LIST_DONGLES
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  913): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1134): reply (238) for get BSS: id=0,
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1134): freq=5220
I/wpa_supplicant( 1134): level=-46
I/wpa_supplicant( 1134): tsf=0000000121095793,
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG7005g
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=1
,I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-57
I/wpa_supplicant( 1134): tsf=0000000121095818
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1134): ssid=NG700
I/wpa_supplicant( 1134): ####
D/WifiStateMachine(  913): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiP2pService(  913): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  913): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4267c6e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4267c6e0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  913): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4267c6e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  913): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 121095793, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/WifiStateMachine(  913): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 121095818, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  913): add 2 to mScanResults
,D/WirelessDisplayService(  913): getDiscoveryDongleList
V/ScoreHelper(  913): Only print Top 10 in ApScanList
V/ScoreHelper(  913):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  913):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  913):  + computeScore(NG700): 1
D/WifiStateMachine(  913): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (2) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
,D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (2) end of scan result ==
,D/WirelessDisplayService(  913): getDiscoveryDongleList,
D/WifiNotificationController(  913): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/AutoSetting( 1508): service - handleMessage() stop self
,D/AutoSetting( 1508): service - onDestroy() END
,D/AutoSetting( 1508): service - handleMessage() quit looper
,D/Process (  913): killProcessQuiet, pid=4319
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4319:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4319
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  913): killProcessQuiet, pid=4000
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4000:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 4000
,D/PMS     (  913): acquireWL(43cd6e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): releaseWL(43cd6e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1134): wpa_supplicant_scan enter
I/wpa_supplicant( 1134): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1134): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1134): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1134): nl80211: Event message available
,D/wpa_supplicant( 1134): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1134): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1134): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1134): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1134): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=9 entropy=4
D/wpa_supplicant( 1134): Add randomness: count=10 entropy=5
D/wpa_supplicant( 1134): Add randomness: count=11 entropy=6
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): Selecting BSS from priority group 1
I/wpa_supplicant( 1134): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1134): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1134): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1134): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1134):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1134):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1134): Start print parameters
I/wpa_supplicant( 1134): wpa_s->wpa_state is 9
I/wpa_supplicant( 1134): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1134): isConcurrentMode() is 0
I/wpa_supplicant( 1134): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1134): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1134): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1134): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1134): wpa_s->reassociate is 0
I/wpa_supplicant( 1134): wpa_s->is_screen_on 0
I/wpa_supplicant( 1134): wpa_s->ifname wlan0
I/wpa_supplicant( 1134): End print parameters
I/wpa_supplicant( 1134): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1134): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1134): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1134): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=12 entropy=7
D/wpa_supplicant( 1134): Add randomness: count=13 entropy=8
D/wpa_supplicant( 1134): Add randomness: count=14 entropy=9
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1134): WPS: WF,A subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  913): doString: LIST_DONGLES
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1134): State: INACTIVE -> INACTIVE
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  913): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  913): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1134): reply (376) for get BSS: id=0
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1134): freq=5220
,I/wpa_supplicant( 1134): level=-47
I/wpa_supplicant( 1134): tsf=0000000138493287
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG7005g
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=1
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-57
I/wpa_supplicant( 1134): tsf=0000000138493312
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG700
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=2
I/wpa_supplicant( 1134): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-79
I/wpa_supplicant( 1134): tsf=0000000138493322
I/wpa_supplicant( 1134): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1134): ssid=Gonzos
I/wpa_supplicant( 1134): ####
D/WifiStateMachine(  913): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WirelessDisplayService(  913): getDiscoveryDongleList
D/WifiStateMachine(  913): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 138493287, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 138493312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 138493322, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): add 3 to mScanResults
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
V/ScoreHelper(  913): Only print Top 10 in ApScanList
V/ScoreHelper(  913):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  913):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  913):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  913):  + computeScore(NG700): 1
D/WifiStateMachine(  913): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (3) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  913): == begin of scan result ==
D/WirelessDisplayService(  913): getDiscoveryDongleList
D/WifiStateMachine(  913): == (3) end of scan result ==
D/WifiNotificationController(  913): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): acquireWL(434fac80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{43851530: PendingIntentRecord{435b6ac8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=136071, Int=0,
,V/AlarmManager(  913): sending alarm PendingIntent{4254ac48: PendingIntentRecord{4202ed38 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=144145, Int=0
,D/PMS     (  913): acquireWL(434aa330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/PMS     (  913): acquireWL(43b18bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43b18bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(434aa330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(437d5400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(437d5400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426adee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1134): Change stage from stage3 to stage1
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/PMS     (  913): acquireWL(42469320): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(43ad2860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1453416031342 tag=VacuumService
,D/PMS     (  913): releaseWL(426adee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  913): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  913): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  913): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  913): acquireWL(43e48508): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
D/PMS     (  913): releaseWL(434fac80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  913): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-,err=8
D/libc    (  913): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  913): [NET] getaddrinfo-, 1
,D/libc    (  913): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4961 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  913): releaseWL(43ad2860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42469320): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(43e7fd78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(43e7fd78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4380a080): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(4380a080): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(43dafe20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(43dafe20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  913): [NET] getaddrinfo_proxy-, success
I/global  (  913): call createSocket() return a new socket.
D/libc    (  913): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  913): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  913): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  913): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  913):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  913): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  913): releaseWL(43e48508): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  913): acquireWL(43806148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{42050fa8: PendingIntentRecord{43ea1d38 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=149858, Int=0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  913): releaseWL(43806148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(436b12c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=10 [30][3][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/AutoSetting( 1346): service - handleMessage() stop self
,D/AutoSetting( 1346): service - handleMessage() quit looper
,D/AutoSetting( 1346): service - onDestroy() END
,D/Process (  913): killProcessQuiet, pid=4373
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4373:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/PMS     (  913): acquireWL(4434e558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Recipient 4373
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): releaseWL(4434e558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(43b6f3b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(436b12c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4438fd60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(4438fd60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1134): Change stage from stage1 to stage3
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 1307 seconds from now (1453416037370)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  913): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1134): Change stage from stage3 to stage1
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9d51 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/PMS     (  913): releaseWL(43b6f3b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(44346c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(44346c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(43e6f1a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(43e6f1a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1134): wpa_supplicant_scan enter
I/wpa_supplicant( 1134): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1134): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1134): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1134): nl80211: Event message available
,D/wpa_supplicant( 1134): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1134): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1134): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1134): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1134): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=15 entropy=10
D/wpa_supplicant( 1134): Add randomness: count=16 entropy=11
D/wpa_supplicant( 1134): Add randomness: count=17 entropy=12
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): Selecting BSS from priority group 1
I/wpa_supplicant( 1134): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1134): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1134): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1134): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1134):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1134):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1134): Start print parameters
I/wpa_supplicant( 1134): wpa_s->wpa_state is 9
I/wpa_supplicant( 1134): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1134): isConcurrentMode() is 0
I/wpa_supplicant( 1134): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1134): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1134): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1134): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1134): wpa_s->reassociate is 0
I/wpa_supplicant( 1134): wpa_s->is_screen_on 0
I/wpa_supplicant( 1134): wpa_s->ifname wlan0
I/wpa_supplicant( 1134): End print parameters
I/wpa_supplicant( 1134): selected network = 1
D/wpa_supplicant( 1134): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (3 BSSes)
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): Sorted scan results
D/WifiNative-wlan0(  913): doString: LIST_DONGLES
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1134): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=18 entropy=13
D/wpa_supplicant( 1134): Add randomness: count=19 entropy=14
D/wpa_supplicant( 1134): Add randomness: count=20 entropy=15
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/w,pa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1134): State: INACTIVE -> INACTIVE
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  913): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1134): reply (376) for get BSS: id=0
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1134): freq=5220
I/wpa_supplicant( 1134): level=-47
I/wpa_supplicant( 1134): tsf=0000000155572286
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG7005g
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=1
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-54
I/wpa_supplicant( 1134): tsf=0000000155572312
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG700
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=2
I/wpa_supplicant( 1134): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-79
I/wpa_supplicant( 1134): tsf=0000000155572324
I/wpa_supplicant( 1134): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1134): ssid=Gonzos
I/wpa_supplicant( 1134): ####
,D/WirelessDisplayService(  913): getDiscoveryDongleList
,D/WifiStateMachine(  913): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
D/WifiP2pService(  913): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  913): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/WifiStateMachine(  913): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 155572286, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 155572312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 155572324, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): add 3 to mScanResults
,V/ScoreHelper(  913): Only print Top 10 in ApScanList
,V/ScoreHelper(  913):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  913):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  913):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  913):  + computeScore(NG700): 1
,D/WifiStateMachine(  913): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (3) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (3) end of scan result ==
,D/WirelessDisplayService(  913): getDiscoveryDongleList
D/WifiNotificationController(  913): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(442bd8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=173095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(442bd8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4439b190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(4439b190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(443eb3f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{423a8db0: PendingIntentRecord{43c0a3b8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=185915, Int=0
,D/PMS     (  913): releaseWL(443eb3f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  913): acquireWL(443cc898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(443cc898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  913): acquireWL(4437af70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4437af70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(4434f870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=233095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4434f870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(44318fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44318fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(44314978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=293095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(44314978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(44312f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44312f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(442b4d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=353095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(442b4d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(43f19588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
,D/PMS     (  913): releaseWL(43f19588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(43e003d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43e003d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=1 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1134): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1134): nl80211: Disconnect event
I/wpa_supplicant( 1134): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1134): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
I/wpa_supplicant( 1134): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1134): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1134): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1134): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1134): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1134): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb703cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1134):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1134): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1134): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1134): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1134): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/HTCRequest(  913): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  913): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonito,r:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  913): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  913): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  913): Enter handleNetworkDisconnect
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1134): Power_Mode_Type mode = 0
I/wpa_supplicant( 1134): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  913): interfaceLinkStateChanged wlan0, false
,D/Tethering(  913): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  913):    returned true
,D/Tethering(  913): [isWifi] getHotspotEnabled: false
,D/WifiP2pService(  913): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  913): interfaceLinkStateChanged wlan0, false
D/Tethering(  913): interfaceStatusChanged wlan0, false
,D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  913): [RunningState] Stop DHCP
D/libc    (  913): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  913): Exit handleNetworkDisconnect
D/libc    (  913): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiPerfLock(  913): release()
D/WifiDataStallTracker(  913): stopDataStallAlarm: current tag=22620 mDataStallAlarmIntent=null
,D/WifiStateMachine(  913): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 0
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): Power_Mode_Type mode = 0
I/wpa_supplicant( 1134): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  913): isAvailable+-
D/UsbnetStateTracker(  913): reconnect
,D/UsbnetStateTracker(  913): isAvailable+-
D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  913): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/ConnectivityService(  913): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  913): Provision feature enable=false
D/PMS     (  913): acquireWL(4380d778): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 913 1000 null
D/ConnectivityService(  913): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  913): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  913): default: reconnect()
D/MDST    (  913): default: setTeardownRequested(false)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/MDST    (  913): default: setEnableApn apnType =default , enable=true
,D/WifiNative-wlan0(  913):    returned true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4193): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiP2pService(  913): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  913): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  913): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  913): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  913): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  913): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  913): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiNative-wlan0(  913): doBoolean: SET pno 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): CTRL_IFACE SET 'pno'='1'
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 4193): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  913): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  913): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiService(  913): New client listening to asynchronous messages
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1134): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  913): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WISPrService( 4193): >>>>>WISPrService start isConnected = false<<<<<
,V/NativeCrypto( 1361): Read error: ssl=0x661f3970: I/O error during system call, Connection timed out
,D/WifiStateMachine(  913): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4193): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x661f3970: I/O error during system call, Broken pipe
D/libc    (  364): [NET] entry_id:3   entry:0xb6f4c590  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb6f50e40  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb6f50d90  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb6f4c100  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb6f50f70  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb6f4c960  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb6f4c458  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb6f4cb08  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
W/ConnectivityService(  913): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  913): handleConnectivityChange: resetting
D/ConnectivityService(  913): resetConnections(wlan0, 3)
D/PMS     (  913): acquireWL(425ee2f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  913): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  913): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
D/ConnectivityService(  913): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
D/PMS     (  913): acquireWL(4218a1e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  913): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
D/PMS     (  913): acquireWL(41f058e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 913 1000 null
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
,D/WirelessDisplayService(  913): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  913): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I//system/bin/ip(  364): RTNETLINK answers: No such process,
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  913): reportInetCondition for net -1, percentage: 0 by  (1361/10029)
D/WifiStateMachine(  913): startScan Pid: 913 Uid 1000
D/WifiNative-wlan0(  913): doBoolean: SET pno 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1134): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1134): nl80211: Event message available
,D/wpa_supplicant( 1134): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doBoolean: SCAN
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): wpa_supplicant_scan enter
I/wpa_supplicant( 1134): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1134): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1134): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1134): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  913):    returned true
,D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  913): releaseWL(425ee2f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BatSI   (  913): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  913): mActiveDefaultNetwork: -1
D/ConnectivityService(  913): handleInetConditionChange: no active default network - ignore
D/PMS     (  913): releaseWL(4218a1e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  913): releaseWL(41f058e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  913): [AlarmQueuing] connectivity wifi: false
,V/Tethering(  913): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  913): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  913): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  913): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  913): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/PMS     (  913): acquireWL(43e1d880): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
D/PMS     (  913): releaseWL(43e1d880): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  913): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  913): NoActiveNetworkState
D/Tethering(  913): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  913): bSetPropertyMultiRAB:false
D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/Tethering(  913): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  913): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.backuptransport (1568/10029)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
I/Tethering(  913): ipv4Default null
I/Tethering(  913): No IPv4 upstream interface, giving up.
D/Tethering(  913): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4421): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.google.android.music (4421/10154)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981,
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (2375/10021)
,I/ActivityManager(  913): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4686 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4686): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4686): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4686): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4686): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4686): Preparing secondary program dexes.
V/DexLibLoader( 4686): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4686): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4686): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4686): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4686): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4686): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock,
V/DexLibLoader( 4686): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar,
,V/DexLibLoader( 4686): Dex already copied
D/OdexVerifier( 4686): Odex verification is skipped.
V/DexLibLoader( 4686): Creating class loader
V/DexLibLoader( 4686): Finished creating class loader
V/DexLibLoader( 4686): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4686): Dex already copied
D/OdexVerifier( 4686): Odex verification is skipped.
V/DexLibLoader( 4686): Creating class loader
V/DexLibLoader( 4686): Finished creating class loader
V/DexLibLoader( 4686): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4686): Dex already copied
D/OdexVerifier( 4686): Odex verification is skipped.
V/DexLibLoader( 4686): Creating class loader
V/DexLibLoader( 4686): Finished creating class loader
V/DexLibLoader( 4686): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4686): Dex already copied
D/OdexVerifier( 4686): Odex verification is skipped.
V/DexLibLoader( 4686): Creating class loader
V/DexLibLoader( 4686): Finished creating class loader
V/DexLibLoader( 4686): Verifying classes from secondary dexes.
,D/DexLibLoader( 4686): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4686): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4686): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4686): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4686): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4686): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4686): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4686): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4686): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4686): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1134): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1134): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=21 entropy=16
D/wpa_supplicant( 1134): Add randomness: count=22 entropy=17
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1134): Selecting BSS from priority group 1
I/wpa_supplicant( 1134): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1134): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1134): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1134): No APs found - clear blacklist and try again
E/wpa_supplicant( 1134): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1134): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1134): Selecting BSS from priority group 1
I/wpa_supplicant( 1134): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1134): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1134): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1134): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1134): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=23 entropy=18
D/wpa_supplicant( 1134): Add randomness: count=24 entropy=19
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  913): doBoolean: SET pno 1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1134): State: INACTIVE -> INACTIVE
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiMonitor(  913): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): CTRL_IFACE SET 'pno'='1',
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1134): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1134): nl80211: Event message available
,D/wpa_supplicant( 1134): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  913): doString: LIST_DONGLES
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  913): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  913): doString: BSS RANGE=0- MASK=0x21987
,D/WirelessDisplayService(  913): getDiscoveryDongleList
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1134): reply (376) for get BSS: id=1
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-54
I/wpa_supplicant( 1134): tsf=0000000155572312
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG700
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=3
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1134): freq=5220
I/wpa_supplicant( 1134): level=-46
I/wpa_supplicant( 1134): tsf=0000000407141383
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG7005g
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=4
I/wpa_supplicant( 1134): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-79
I/wpa_supplicant( 1134): tsf=0000000407141403
I/wpa_supplicant( 1134): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1134): ssid=Gonzos
I/wpa_supplicant( 1134): ####
,D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (3) end of scan result ==
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/WifiStateMachine(  913): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 155572312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 407141383, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 407141403, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): add 3 to mScanResults
D/BatSI   (  913): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  913): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  913): getDiscoveryDongleList
D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (3) end of scan result ==
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,E/FbInjectorInitializer( 4686): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4686): Verify
,D/WifiService(  913): New client listening to asynchronous messages
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4686): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4686): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4686): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  913): killProcessQuiet, pid=3494
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  913): Killing 3494:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3494
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1346): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  913): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4704 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1346/10055)
,D/AutoSetting( 1346): Util - no network available!
,D/AutoSetting( 1346): service - onCreate()
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1346/10055)
,D/AutoSetting( 1346): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  913): request 4248e298 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/AutoSetting( 1346): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  913): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1346): service - mHandler: cancel location update
,D/AutoSetting( 1346): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4686): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4686): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4704): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4704): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4704): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4704): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4686): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  913): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4720 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10079)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10079)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10079)
,I/ActivityManager(  913): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4734 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/Process (  913): killProcessQuiet, pid=4447
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Killing 4447:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/dalvikvm-heap( 4686): Grow heap (frag case) to 9.951MB for 84664-byte allocation
,E/dalvikvm( 4686): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4686): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4686): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4686): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4686): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4686): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4686): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4686): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4686): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4686): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4686): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4734): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/dalvikvm( 4686): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4686): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4686): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4686): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4686): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4686): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4686): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4734): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4734): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4734): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4686): Grow heap (frag case) to 10.047MB for 39954-byte allocation
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4734): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  913): Recipient 4447
,I/dalvikvm-heap( 4686): Grow heap (frag case) to 10.124MB for 79892-byte allocation
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4734/10151)
,V/WebViewChromiumFactoryProvider( 4734): Binding Chromium to main looper Looper (main, tid 1) {41b07ee0}
,I/LibraryLoader( 4734): Expected native library version number "",actual native library version number ""
,I/chromium( 4734): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4734): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4734): BLUETOOTH permission is missing!
D/PMS     (  913): acquireWL(426e9ef8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): acquireWL(430bb598): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): releaseWL(426e9ef8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4734): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4734): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4734): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4734): Local Branch: 
I/Adreno-EGL( 4734): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4734): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4734):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4686): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,I/NSApplication( 4734): Starting up...
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{434d3b10 u0 ReceiverList{434d39f0 4686 com.facebook.katana/10027/u0 remote:43f24b48}}
W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{434d3b10 u0 ReceiverList{434d39f0 4686 com.facebook.katana/10027/u0 remote:43f24b48}}
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4734/10151)
W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{435ec440 u0 ReceiverList{42ef0b28 4686 com.facebook.katana/10027/u0 remote:4439af38}}
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4734/10151)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4223/10160)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4223/10160)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/Process (  913): killProcessQuiet, pid=4469
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  913): Killing 4469:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
I/ActivityManager(  913): Recipient 4469
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/iu.Environment( 2179): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,I/iu.UploadsManager( 2179): num queued entries: 0
,I/iu.UploadsManager( 2179): num updated entries: 0
,I/iu.SyncManager( 2179): NEXT; no task
D/WifiService(  913): Client connection lost with reason: 4
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  913): getAllNetworkInfo called by com.test.thalitest (4562/10389)
,D/PMS     (  913): acquireWL(4434bd88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4434bd88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4686): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4686): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4686): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1134): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1134): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1134): Add randomness: count=25 entropy=20
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): Selecting BSS from priority group 1
I/wpa_supplicant( 1134): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1134): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1134): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1134):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1134):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1134): Start print parameters
I/wpa_supplicant( 1134): wpa_s->wpa_state is 3
I/wpa_supplicant( 1134): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1134): isConcurrentMode() is 0
I/wpa_supplicant( 1134): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1134): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1134): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1134): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1134): wpa_s->reassociate is 0
I/wpa_supplicant( 1134): wpa_s->is_screen_on 0
I/wpa_supplicant( 1134): wpa_s->ifname wlan0
I/wpa_supplicant( 1134): End print parameters
I/wpa_supplicant( 1134): selected network = 1
D/wpa_supplicant( 1134): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb703e4e8  current_ssid=0x0
D/wpa_supplicant( 1134): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1134): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1134): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1134): check if in concurrent case
,I/wpa_supplicant( 1134): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1134): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1134): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1134): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1134): RSN: PMKSA cache search - network_ctx=0xb703e4e8 try_opportunistic=0
D/wpa_supplicant( 1134): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1134): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1134): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1134): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1134): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 1134): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1134): nl80211: Unsubscribe mgmt frames handle 0xb703d718 (mode change)
D/wpa_supplicant( 1134): nl80211: Subscribe to mgmt frames with non-AP handle 0xb703d718
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Register frame type=0xd0 nl_handle=0xb703d718
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1134): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1134):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1134):   * freq=2412
D/wpa_supplicant( 1134):   * Auth Type 0
D/wpa_supplicant( 1134):   * WPA Versions 0x2
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1134): nl80211: Connect request send successfully
D/wpa_supplicant( 1134): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  913): doString: LIST_DONGLES
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  913): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1134): reply (376) for get BSS: id=1
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-56
I/wpa_supplicant( 1134): tsf=0000000409104461
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG700
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=3
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1134): freq=5220
I/wpa_supplicant( 1134): level=-46
,I/wpa_supplicant( 1134): tsf=0000000407141383
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG7005g
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=4
I/wpa_supplicant( 1134): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-79
I/wpa_supplicant( 1134): tsf=0000000407141403
I/wpa_supplicant( 1134): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1134): ssid=Gonzos
I/wpa_supplicant( 1134): ####
,D/WirelessDisplayService(  913): getDiscoveryDongleList
,D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (3) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  913): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 409104461, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 407141383, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 407141403, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): add 3 to mScanResults
,D/WifiNotificationController(  913): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (3) end of scan result ==
,D/WirelessDisplayService(  913): getDiscoveryDongleList
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1134): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/Tethering(  913): interfaceLinkStateChanged wlan0, false
D/Tethering(  913): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1134): nl80211: Connect event
D/wpa_supplicant( 1134): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1134): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1134): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1134): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1134): Add randomness: count=26 entropy=21
I/wpa_supplicant( 1134): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1134): TDLS: Remove peers on association
D/wpa_supplicant( 1134): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1134): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1134): EAPOL: enable timer tick
D/wpa_supplicant( 1134): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1134): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1134): Get randomness: len=32 entropy=22
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  913): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  913): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  913): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  913): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  913): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  913): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiStateMachine(  913): Enter handleAssociatedWithEvent
I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  913): As,sociated
D/Tethering(  913): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  913): interfaceStatusChanged wlan0, true
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  913): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  913): Exit handleAssociatedWithEvent
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 1134): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb703d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1134):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1134): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1134): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f50b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1134):    broadcast key
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1134): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1134): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1134): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1134): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1134): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1134): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1134): netlink: Operstate: linkmode=-1, operstate=6
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1134): set send_ind_to_ndc = 0
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1134): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1134): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1134): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1134): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1134): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1134): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1134): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1134): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1134): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1134): EAPOL authentication completed successfully
I/wpa_supplicant( 1134): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1134): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1134): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1134): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  913): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  913): interfaceLinkStateChanged wlan0, true
D/Tethering(  913): interfaceStatusChanged wlan0, true
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  913): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  913): updateConnectedAP...
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  913): updateConnectedAP...
D/WifiStateMachine(  913): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  913): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  913): This record is existed, only update it...
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  913): updateConnectedAP...
,D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  913): updateConnectedAP...
D/WifiStateMachine(  913): fetchFrequency(), freq = 2412
D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  913): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  913): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  913): Provision feature enable=false
D/ConnectivityService(  913): mActiveDefaultNetwork: -1
D/WifiApDatabaseHandler(  913): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  913): This record is existed, only update it...
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,D/WISPrService( 4193): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4193): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,D/WifiNative-wlan0(  913): doBoolean: SET pno 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1134): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1134): nl80211: Event message available
,D/wpa_supplicant( 1134): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  913):    returned true
,D/DhcpStateMachine(  913): [StoppedState] Start DHCP
,D/WifiStateMachine(  913): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
,D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): Power_Mode_Type mode = 1
I/wpa_supplicant( 1134): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doString: DRIVER WLS_BATCHING GET,
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  913):    returned null
E/WifiStateMachine(  913): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  913): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/WifiStateMachine(  913): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  913): acquireWL(43e16030): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 913 1000 null
,D/WifiStateMachine(  913): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  913):    returned null
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1134): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiP2pService(  913): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425ec238 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425ec238 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1,
,D/wpa_supplicant( 1134): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1134): EAPOL: disable timer tick
,D/PMS     (  913): releaseWL(430bb598): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiStateMachine(  913): startScan Pid: 913 Uid 1000
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,W/fb4a(:<default>):UserScope( 4686): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4686): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/libc    (  913): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
,E/fb4a(:<default>):LocalFbBroadcastManager( 4686): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/libc    (  913): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  913): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1134): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  913):    returned true
,D/WifiStateMachine(  913): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  913): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  913): releaseWL(43e16030): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  913): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WifiStateMachine(  913): gateway: /192.168.1.1
,D/WifiNative-wlan0(  913): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1134): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  913): VerifyingLinkState enter
D/WifiStateMachine(  913): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  913): doBoolean: SCAN TYPE=ONLY
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): wpa_supplicant_scan enter
I/wpa_supplicant( 1134): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1134): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1134): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  913): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/BatSI   (  913): WIFI scan started for: 450a0300 uid:1000
V/NetworkPolicy(  913): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  913): WAN detection
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  913): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  913): Provision feature enable=false
D/ConnectivityService(  913): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  913): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  913): default: teardown()
D/MDST    (  913): default: setTeardownRequested(true)
D/MDST    (  913): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  913): default: setTeardownRequested(true)
D/ConnectivityService(  913): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4193): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
E/ConnectivityService(  913): Unexpected mtu value: android.net.wifi.WifiStateTracker@424913e8
D/ConnectivityService(  913): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  913): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:2
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  913): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/NetdConnector(  913): NDC Command {42 interface route add wlan0 default 192.168.1.0 24 0.0.0.0} took too long (796ms)
D/ConnectivityService(  913): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  913): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  913): handleConnectivityChange: resetting
D/Nat464Xlat(  913): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  913): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  913): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  913): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  913): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  913): acquireWL(4433f118): PARTIAL_WAKE_LOCK  NetworkStats 0x1 913 1000 null
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/WirelessDisplayService(  913): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  913):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1134): Change stage from stage0 to stage3
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10079)
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  913): acquireWL(435eb080): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1453415956915 min interval config: 0 actual interval: 342466
D/PMS     (  913): acquireWL(4374de98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(435eb080): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2179): Checking schedule, now: 1453416299388 next: 1453415986708
,I/CheckinService( 2179): active receiver: enabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2179, uid=10029, userID:0
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2179): Preparing to send checkin request
,I/EventLogService( 2179): Accumulating logs since 1453415952505
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  913): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(4433f118): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  913): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  913): releaseWL(4380d778): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  913): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  913): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  913): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4821 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4821): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4821): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4821): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4821): install
,I/GAV2    ( 4734): Thread[GAThread,5,main]: No campaign data found.
,I/MultiDex( 4821): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4821): loading existing secondary dex files
,I/MultiDex( 4821): load found 3 secondary dex files
,I/MultiDex( 4821): install done
,W/dalvikvm( 4821): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4821): VFY: unable to resolve instance field 36
,W/dalvikvm( 4821): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4821): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4821): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,E/MDM     ( 1223): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2179): Restart initialization of location
D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
,W/dalvikvm( 4821): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4821): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 4821): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4821): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4821): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4821): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4821): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  913): acquireWL(43ade1f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
D/PMS     (  913): releaseWL(43ade1f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/PMS     (  913): acquireWL(43727d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=413095, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/NativeLibraryUtils( 4821): Install completed successfully. count=14 extracted=0
D/PMS     (  913): releaseWL(43727d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2201921620
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3628778811
,I/WVCdm   (  371): CdmEngine::CloseSession
,V/Tethering(  913): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  913): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/Tethering(  913): bSetPropertyMultiRAB:false
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  913): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  913): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  913): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
I/Tethering(  913): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
I/Tethering(  913): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  913): Found interface wlan0
,D/Tethering(  913): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  913): NoActiveNetworkState
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/NetworkMonitor( 4421): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/PMS     (  913): acquireWL(43eb48d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.google.android.music (4421/10154)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10079)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.backuptransport (1568/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/CaptivePortalTracker(  913): DelayedCaptiveCheckState
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.backuptransport (1568/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/PMS     (  913): acquireWL(4389bf80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
D/PMS     (  913): acquireWL(44353350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  913): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  913): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
D/GpsLocationProvider(  913): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  913): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/PMS     (  913): releaseWL(4389bf80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  913): releaseWL(43eb48d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (2375/10021)
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4686/10027)
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
D/PMS     (  913): releaseWL(44353350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1346): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/Adreno-EGL( 4821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4821): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4821): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4821): Local Branch: 
I/Adreno-EGL( 4821): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4821): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4821):                  aa63bbd948f41d15fc72f585e
,D/MobileConnectivityChangeReceiver( 4704): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4704): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1346): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1346): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1346/10055)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1346/10055)
,D/AutoSetting( 1346): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1346): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4734/10151)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4223/10160)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4223/10160)
,D/PMS     (  913): acquireWL(439b0dd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1453415956915 min interval config: 0 actual interval: 343558
D/PMS     (  913): releaseWL(439b0dd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4223): Grow heap (frag case) to 13.521MB for 1821008-byte allocation
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2179): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,I/iu.UploadsManager( 2179): num queued entries: 0
,I/iu.UploadsManager( 2179): num updated entries: 0
,I/iu.SyncManager( 2179): NEXT; no task
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  913): getAllNetworkInfo called by com.test.thalitest (4562/10389)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  913): acquireWL(43b4fb10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ba60 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1134): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1134): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1134): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1134): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=27 entropy=0
D/wpa_supplicant( 1134): Add randomness: count=28 entropy=1
D/wpa_supplicant( 1134): Add randomness: count=29 entropy=2
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  913): doString: LIST_DONGLES
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  913): doString: BSS RANGE=0- MASK=0x21987
,D/WirelessDisplayService(  913): getDiscoveryDongleList
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1134): reply (376) for get BSS: id=1
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-56
I/wpa_supplicant( 1134): tsf=0000000413692438
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG700
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=3
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1134): freq=5220
I/wpa_supplicant( 1134): level=-46
I/wpa_supplicant( 1134): tsf=0000000413692418
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG7005g
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=4
I/wpa_supplicant( 1134): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-83
I/wpa_supplicant( 1134): tsf=0000000413692448
I/wpa_supplicant( 1134): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1134): ssid=Gonzos
I/wpa_supplicant( 1134): ####
,D/WifiStateMachine(  913): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  913): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 413692438, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 413692418, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 413692448, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): add 3 to mScanResults
,V/ScoreHelper(  913): Only print Top 10 in ApScanList
,V/ScoreHelper(  913):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  913):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  913):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  913):  + computeScore(NG700): 1
,D/WifiStateMachine(  913): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (3) end of scan result ==
D/BatSI   (  913): WIFI scan stopped for: 440a0300 uid:1000
,D/WifiNotificationController(  913): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1223): getScanResults enter 
,D/WifiStateMachine(  913): == begin of scan result ==
D/WirelessDisplayService(  913): getDiscoveryDongleList
,D/WifiStateMachine(  913): == (3) end of scan result ==
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 273
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
,W/Settings( 4821): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4821): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4821): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4821): Local Branch: 
I/Adreno-EGL( 4821): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4821): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4821):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4821): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4821): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4821): Local Branch: 
I/Adreno-EGL( 4821): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4821): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4821):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  913): acquireWL(43ea41f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(4446cd00): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  913): releaseWL(43b4fb10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: starting a change hold
D/PMS     (  913): releaseWL(4446cd00): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(443a7358): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): acquireWL(4437ff00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(443a7358): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
D/PMS     (  913): releaseWL(43ea41f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/PMS     (  913): acquireWL(4432c500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(4432c500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =81a4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (4821/10029)
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 7515
D/libc    (  364): [NET]res_nsend:resplen=45
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2179): [NET] getaddrinfo-,err=8
D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2179): [NET] getaddrinfo-, 1
,D/libc    ( 2179): [NET] getaddrinfo_proxy+
V/NativeCrypto( 2179): SSL shutdown failed: ssl=0x65afdc10: I/O error during system call, Connection timed out
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a3c0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 286
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2179): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2179): Sending checkin request (12209 bytes)
,D/ConnectivityService(  913): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=4 [23][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-,err=8
D/libc    (  913): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  913): [NET] getaddrinfo-, 1
,D/libc    (  913): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3339 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  913): Find DNS Address www.htc.com/23.59.123.86
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  913): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,W/PhenotypeConfigurator( 1223): Server returned 404
D/PMS     (  913): releaseWL(4437ff00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(41c28d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(41c28d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=16 [6][1][0]
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,I/CheckinTask( 2179): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2179): Checking schedule, now: 1453416301823 next: 1453939238818
,I/CheckinService( 2179): active receiver: disabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,I/CheckinService( 2179): Checking schedule, now: 1453416301879 next: 1453939238818
,I/CheckinService( 2179): active receiver: disabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
,D/CheckinService( 2179): Recording last checkin time for package unspecified as 1453416301886
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(4374de98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  913): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  913): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{43a31468 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PMS     (  913): acquireWL(424d2120): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4145 10111 null
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsUpdated
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PMS     (  913): releaseWL(424d2120): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/[PluginManager]RegisterService( 1346): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1346): handle notify Blinkfeed plugin client changed
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "sms"
,I/IcingCorporaProvider( 2864): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/dalvikvm-heap( 4223): Grow heap (frag case) to 15.219MB for 1821008-byte allocation
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  913): acquireWL(42583840): PARTIAL_WAKE_LOCK  AsyncService 0x1 4223 10160 null
,I/ActivityManager(  913): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  913): acquireWL(436cd818): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(436cd818): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,I/dalvikvm-heap( 4223): Grow heap (frag case) to 16.949MB for 1821008-byte allocation
D/PMS     (  913): releaseWL(42583840): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  913): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
D/PMS     (  913): acquireWL(43e47ae0): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2179): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  913): Resuming delayed broadcast
,I/Icing   ( 2179): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  913): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2864): UpdateCorporaTask done [took 777 ms] updated apps [took 777 ms] 
,W/PackageManager(  913): Unable to load service info ResolveInfo{434a9f48 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  913): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  913): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(43ed86a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(43ed86a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(43ac3e50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(43ac3e50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(43edaa08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43edaa08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b9db98 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  913): releaseWL(43e47ae0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b9db98 -
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,D/PMS     (  913): acquireWL(442ad3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(442ad3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1346): service - has update message, not stop
,D/AutoSetting( 1346): service - mHandler: update timezone
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1508): service - onCreate()
,W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1552): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1552): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1508): service - mHandler: update timezone
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1508): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1508): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1552): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e2b410 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 3 11
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{43d9eaf8 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(43f2aa30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=473096, Int=0
,D/PMS     (  913): releaseWL(43f2aa30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1346): service - handleMessage() stop self
,D/AutoSetting( 1346): service - onDestroy() END
,D/Process (  913): killProcessQuiet, pid=4501
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1346): service - handleMessage() quit looper
I/ActivityManager(  913): Killing 4501:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4501
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1508): service - handleMessage() stop self
,D/AutoSetting( 1508): service - onDestroy() END
,D/Process (  913): killProcessQuiet, pid=4515
,I/ActivityManager(  913): Killing 4515:com.android.settings:remote/1000 (adj 15): empty #17
D/AutoSetting( 1508): service - handleMessage() quit looper
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  913): Recipient 4515
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(42efd0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42efd0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(443b7210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(443b7210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(443bf430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=533095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(443bf430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(4433b700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4433b700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(43e7b540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=593095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43e7b540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(426e1370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(426e1370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1239): sku_id=99
D/ContactMessageStore( 1239): start background delete task...
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/Process (  913): killProcessQuiet, pid=4118
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4118:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 4118
,D/PMS     (  913): acquireWL(43680148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=653095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43680148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42595198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42595198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(4265f7c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=713095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4265f7c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(43820c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43820c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(443c7bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=773096, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(443c7bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(43e97380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43e97380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(43adc028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=833096, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43adc028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(44340a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44340a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(439f0040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=893095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(439f0040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4438f890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4438f890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(4438ec30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=953096, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4438ec30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(43b6be08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43b6be08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(43ef1420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1013095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43ef1420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(434a6df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,D/ConnectivityService(  913): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  913): sending alarm PendingIntent{41c3bb30: PendingIntentRecord{4249bba0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=795722, Int=0
,D/ConnectivityService(  913): Done.
,D/ConnectivityService(  913): Setting timer for 720seconds
,I/ActivityManager(  913): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4896 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  913): sending alarm PendingIntent{4245f560: PendingIntentRecord{4244a9e0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453416106223, Int=10800000
,V/AlarmManager(  913): sending alarm PendingIntent{43eea5f0: PendingIntentRecord{439ac9a0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453416133002, Int=1800000
,V/AlarmManager(  913): sending alarm PendingIntent{42690ca0: PendingIntentRecord{42691278 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453416827537, Int=900000
,V/AlarmManager(  913): sending alarm PendingIntent{423eea18: PendingIntentRecord{42606738 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453416906080, Int=0
,D/PMS     (  913): acquireWL(433d1f88): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(435570d8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(433d1f88): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4630): call getInstance()
,D/SmartSyncUtils( 4630): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4630): MY_DEBUG = false
D/PMS     (  913): acquireWL(4268e8d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4630 1000 null
,D/PMS     (  913): releaseWL(434a6df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4630): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4630): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
I/EventLogService( 2179): Aggregate from 1453416299434 (log), 1453414332930 (data)
D/SmartSyncScreenOnOffTimeReceiver( 4630): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4630): SettingOnTime = 1453442400000, randomSettingOnTime = 1453441144000
D/SmartSyncScreenOnOffTimeReceiver( 4630): SettingOffTime = 1453428000000, randomSettingOffTime = 1453430967000
D/SmartSyncScreenOnOffTimeReceiver( 4630): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4630): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4630): bNightModeTurnOffOnce = false
D/PMS     (  913): releaseWL(4268e8d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  913): Couldn't get kernel wake lock stats
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.aurora (4896/10049)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
,D/PMS     (  913): releaseWL(435570d8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,D/Process (  913): killProcessQuiet, pid=4606
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4606:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4606
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(42595a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42595a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(4391fe98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1073095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4391fe98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42438020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42438020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(425cba08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1133095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(425cba08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(423363a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(423363a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(43e89f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1193095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43e89f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(430bb2c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(430bb2c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  913): acquireWL(426863c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1253095, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(426863c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(425cf0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(425cf0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(43b3ac18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ff9608: PendingIntentRecord{41fc2ff8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1313095, Int=0
,I/FeedHostManager( 1273): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
V/AlarmManager(  913): sending alarm PendingIntent{4256e808: PendingIntentRecord{4260cf10 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1453417200000, Int=0
D/PMS     (  913): acquireWL(424d9598): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1273 10076 null
V/AlarmManager(  913): sending alarm PendingIntent{43e9d4d0: PendingIntentRecord{43bd6598 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.reminders.REFRESH_NOTIFICATION, t=0, cnt=1, w=1453417200000, Int=0
V/AlarmManager(  913): sending alarm PendingIntent{4237dde0: PendingIntentRecord{4263c268 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_UPDATE_GOLDEN_TABLE, t=0, cnt=1, w=1453417200000, Int=86400000
D/PMS     (  913): releaseWL(424d9598): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): acquireWL(42429cf8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2179 10029 null
,D/PMS     (  913): acquireWL(423dbf60): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(423815a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4630 1000 null
,D/PMS     (  913): releaseWL(42429cf8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  913): releaseWL(423dbf60): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43b3ac18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4915): Error opening trace file: No such file or directory (2)
D/PMS     (  913): acquireWL(443a94d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  913): sending alarm PendingIntent{43f183b0: PendingIntentRecord{42b656a8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1314035, Int=0
V/AlarmManager(  913): sending alarm PendingIntent{44401fd8: PendingIntentRecord{43b7e180 com.htc.task broadcastIntent}}, i=com.htc.task.date.change, t=1, cnt=1, w=1453417200463, Int=0
D/PMS     (  913): acquireWL(432ac4b0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(432ac4b0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  913): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4924 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
D/PMS     (  913): acquireWL(433d1af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: starting a change hold
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026622
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026789
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027650
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027656
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027659
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027662
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029436
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029453
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360033968
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360035981
D/CustomizationManager( 4915): ====startRecUseTime====
D/htc.customization.log.level( 4915):  is 
W/CustomizationLogLevel( 4915): Level value is invalid, use default level 2
D/TodoTaskshortcut( 4924): update TASK shortcut>
D/PMS     (  913): releaseWL(443a94d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10071}
D/PMS     (  913): releaseWL(433d1af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/Process (  913): killProcessQuiet, pid=4421
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4421:com.google.android.music:main/u0a154 (adj 15): empty #17
D/CustomizationManager( 4915):  Read ACC file spent 0.089 (s)
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4915): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4915): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4915): Parsing tag category name = system
I/CustomizationCIDLoader( 4915): Parsing tag category name = application
I/CustomizationCIDLoader( 4915): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4915): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4915): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4915): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4915): Parsing tag category name = Settings
D/CustomizationManager( 4915):  Read CID file spent 0.145 (s)
D/CustomizationManager( 4915):  All configurations done spent 0.145 (s)
W/HtcNativeFlag( 4915): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4915): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4915): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4915): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  913): Recipient 4421
D/MediaRouterService(  913): Client com.google.android.music (pid 4421): Died!
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PackageManager(  913): deletePackageAsUser: pkg=com.test.thalitest, pid=4915, uid=2000 user=0
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  913): killProcessQuiet, pid=4562
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  913): Killing 4562:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
W/PackageSettings(  913): Skipping PackageSetting{421a9038 com.example.hello/10397} due to missing metadata
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/ConnectivityService(  913): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1552): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1552): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1552): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  913): acquireWL(4390ada0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=12 [78][10][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/VoicemailCleanupService( 1287): Cleaning up data for package: com.test.thalitest
D/PMS     (  913): releaseWL(4390ada0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/SQLiteConnectionPool( 2179): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/[PluginManager]RegisterService( 1346): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1346): handle notify Blinkfeed plugin client changed
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/InputMethodManagerService(  913): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
I/IcingCorporaProvider( 2864): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  913): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4942 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  913): acquireWL(43791610): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2864): UpdateCorporaTask done [took 506 ms] updated apps [took 506 ms] 
W/PackageManager(  913): Unable to load service info ResolveInfo{4380d030 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  913): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4961 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.docs (4942/10100)
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4942): (3850) statement aborts at 59: [DELETE FROM CachedSearch111 WHERE timestamp<?] disk I/O error
E/SQLiteDBG( 4942): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.apps.docs/databases/DocList.db, handle = 0x5ca41008
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
W/GAV2    ( 4942): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/AbstractDatabaseInstance( 4942): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 4942): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 4942): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AbstractDatabaseInstance( 4942): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 4942): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 4942): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AbstractDatabaseInstance( 4942): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4942): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4942): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4942): 	at fv.run(DocsApplication.java:288)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.docs (4942/10100)
W/dalvikvm( 4942): threadid=11: thread exiting with uncaught exception (group=0x416dae30)
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/AndroidRuntime( 4942): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4942): Process: com.google.android.apps.docs, PID: 4942
E/AndroidRuntime( 4942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4942): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime( 4942): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime( 4942): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime( 4942): 	at fv.run(DocsApplication.java:288)
D/RemoteDisplayProvider(  913): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  913): start
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement,.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/ActivityManager(  913): App crashed! Process: com.google.android.apps.docs
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
D/Process ( 4942): killProcess, pid=4942
D/Process ( 4942): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
W/AtomicFile(  913): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
W/AppWidgetServiceImpl(  913): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4630): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4630): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.UpdateNewGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:1188)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$1800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:807)
E/SQLiteDatabase( 4630): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncUpdateGoldenAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:707)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4630): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4630): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_fri(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4630): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x62119290
E/SQLiteDatabase( 4630): Error inserting ...
E/SQLiteDatabase( 4630): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
```
