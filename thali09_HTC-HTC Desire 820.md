#### Test 558973767bac5c9_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,--------- beginning of /dev/log/system
D/PMS     (  906): acquireWL(4406d658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
V/AlarmManager(  906): sending alarm PendingIntent{41cd1a70: PendingIntentRecord{42533c68 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452693153973, Int=0
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4470 uid=10078 gids={50078}
V/AlarmManager(  906): sending alarm PendingIntent{425335a0: PendingIntentRecord{4251ea60 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452693155812, Int=60000
D/PMS     (  906): releaseWL(4406d658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
D/SMSBackup( 4470): SMSBackupAgentService started
D/SMSBackup( 4470): Checking restore status
D/SMSBackup( 4470): Restore complete
D/SMSBackup( 4470): cancelCheckAlarm
D/SMSBackup( 4470): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/cutils-trace( 4482): Error opening trace file: No such file or directory (2)
D/Finsky  ( 4092): [428] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4092): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  906): killProcessQuiet, pid=3463
I/ActivityManager(  906): Killing 3463:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/CustomizationManager( 4482): ====startRecUseTime====
D/htc.customization.log.level( 4482):  is 
W/CustomizationLogLevel( 4482): Level value is invalid, use default level 2
I/ActivityManager(  906): Recipient 3463
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 4482):  Read ACC file spent 0.061 (s)
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
D/CustomizationManager( 4482):  Read CID file spent 0.109 (s)
D/CustomizationManager( 4482):  All configurations done spent 0.109 (s)
W/HtcNativeFlag( 4482): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4482): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4482): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4482): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4482
D/PMS     (  906): acquireHCC(4374a538): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(440503a0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6274b6f0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1128527688
D/PMS     (  906): acquireWL(432a94f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c300f8
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4494 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4494): Copying FileAsset 0x5c85b428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4494): Binding Chromium to main looper Looper (main, tid 1) {41ae3c78}
I/LibraryLoader( 4494): Expected native library version number "",actual native library version number ""
I/chromium( 4494): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4494): Initializing chromium process, renderers=0
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/PMS     (  906): acquireWL(43638b40): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): acquireWL(438167e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): releaseWL(43638b40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4393e7d0:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4494): 1102028504: getState(). Returning 12
I/Adreno-EGL( 4494): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4494): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4494): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4494): Local Branch: 
I/Adreno-EGL( 4494): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4494): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4494):                  aa63bbd948f41d15fc72f585e
W/chromium( 4494): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4494): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4494): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4494): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4494): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4494): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4494): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4494): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4494): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4494): CordovaWebView is running on device made by: HTC
,W/AwContents( 4494): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1270
,I/InputMethodManagerService(  906): Enable input method client, pid=4494
W/ResourceType( 4494): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4494): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b2b588, mServedView=org.apache.cordova.engine.SystemWebView{41af11f0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4494): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +286ms
,D/PMS     (  906): releaseWL(432a94f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4494): Set native->JS mode to OnlineEventsBridgeMode
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/jxcore_app_log( 4494): JniHelper::setJavaVM(0x415bc048), pthread_self() = 1663363488
,I/chromium( 4494): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.539MB for 63974-byte allocation,
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.595MB for 95956-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.672MB for 143930-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.784MB for 215890-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.957MB for 323830-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 12.629MB for 728606-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 13.219MB for 1092904-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 14.097MB for 1639352-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 15.447MB for 2459024-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(4374a538): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(440503a0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/SensorManager(  906): mEventCount = 1200
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 17.570MB for 3688532-byte allocation
,W/jxcore-log( 4494): Initializing JXcore engine
,W/jxcore-log( 4494): JXcore engine is ready
,W/jxcore-log( 4494): Starting JXcore engine
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 4494): Platform android
W/jxcore-log( 4494): 
,W/jxcore-log( 4494): Process ARCH arm
W/jxcore-log( 4494): 
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43956558 u0 com.htc.htclocationservice/.AutoSettingService}
,V/LightsService(  906): setLight #0: color=#24
,V/LightsService(  906): setLight #0: color=#1d
,V/LightsService(  906): setLight #0: color=#17
,V/LightsService(  906): setLight #0: color=#14
,D/PMS     (  906): releaseWL(438167e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4494): JXcore Cordova bridge is ready!
I/jxcore-log( 4494): 
,W/jxcore-log( 4494): JXcore engine is started
,E/jxcore  ( 4494): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4494): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4494): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4494): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 36ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  906): acquireWL(4394de00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
,I/FeedHostManager( 1270): [onResume]
,I/FeedProviderManager( 1270): onResume
,I/SocialFeedProvider( 1270): +onResume
I/SocialFeedProvider( 1270): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1270): -onResume
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1270/10076)
,I/InputMethodManagerService(  906): Disable input method client, pid=4494
,W/IInputConnectionWrapper( 4494): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  906): Enable input method client, pid=1270
,D/PMS     (  906): releaseWL(4394de00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  906): Killing 4165:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4165
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,E/libEGL  ( 4494): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  906): Recipient 4165
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  906): mEventCount = 1350
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420649e0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420649e0, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d71738
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@41ccc7f8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  906): mWirelessDisplayManager is null
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #0: color=#0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 330ms
,D/PMS     (  906): nativeSetInteractive:false
,D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
,D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  906): Disable input method client, pid=1270
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@441827e8)
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,D/PMN     (  906): wakingUp
D/NfcService( 1248): ScreenObserver: OFF
D/NfcService( 1248): applyRouting - 0
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  906): acquireWL(4269c698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/NfcService( 1248): applyRouting -2
I/BatteryService(  906): n_update end
D/PMS     (  906): acquireWL(42656968): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1248 1027 null
D/PMS     (  906): releaseWL(4269c698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,D/MtpService( 2694): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1248): applyRouting - 0
,D/MtpService( 2694): [MTP][onReceive]-
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(42656968): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): onScreenOn
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): >> updateStatus
D/AutoSetting( 1328): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1248): applyRouting -2
D/AutoSetting( 1328): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PMS     (  906): acquireWL(43af9ec0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1248 1027 null
D/PMS     (  906): releaseWL(43af9ec0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PMS     (  906): acquireWL(4268cb08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{43b1f008: PendingIntentRecord{42531118 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=107510, Int=0
D/TetherSettings( 3826): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3826): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3826): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3826): Cust_ConnectToPC   : spcsc>false
,D/        ( 3826): Cust_ConnectToPC   : IPT>true
D/        ( 3826): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3826): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3826): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3826): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3826): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 3826): onReceive:android.intent.action.USER_PRESENT
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/ContextImpl( 3826): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20730 delay=15s
I/ClockThread( 1115): stop update clock
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:On
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/SmartNS_PSService( 3826): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3826): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3826):  defaultType:0
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:134, mTXpacketCount:134, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onDataStallAlarm: ignore, tag=20729 expecting 20730
D/NetworkPolicy(  906): updateScreenOn: false
,D/PMS     (  906): releaseWL(4268cb08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4549 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(4421fd30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4421fd30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(441c70d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4549): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1753): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1753): onScreenOn: 1452693167173
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1753): onScreenOn: 1452693167173
D/PMS     (  906): releaseWL(441c70d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d71738
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d71738, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@41ccc7f8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(4414fbb8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4549 1000 null
D/PMS     (  906): acquireWL(4414fa40): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4414fbb8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c300f8
,I/SocialFeedProvider( 1270): +onPause
D/SmartSyncUtils( 4549): isEpsOn(), nState = 0
,I/SocialFeedProvider( 1270): -onPause
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20730 mDataStallAlarmIntent=PendingIntent{41ff9000: PendingIntentRecord{42531118 android broadcastIntent}}
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:Off
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1182): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
D/PMS     (  906): acquireWL(441435f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(4414fa40): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1237): start background delete task...
D/ContactMessageStore( 1237): size: 0 , 0
,D/ContactMessageStore( 1237): Background delete complete
,D/SmartSyncUtils( 4549): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(441435f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  906): killProcessQuiet, pid=4264
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4264:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Recipient 4264
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4549): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/PhoneStatusBar( 1115): removeHeadsNotification.gc: 51
,D/SmartSyncUtils( 4549): isEpsOn(), nState = 0
D/SmartSyncUtils( 4549): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4549): isEpsOn(), nState = 0
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ccc7f8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ccc7f8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ccc7f8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ccc7f8
,E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42664f98 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42664f98 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/AutoSetting( 1328): service - mHandler: cancel location update
D/AutoSetting( 1328): service -           changes count: 0
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(43945230): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43945230): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43941dc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43941dc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1753): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1753): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1753): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1753): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1753): onScreenOff
,D/ContactMessageStore( 1237): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1237): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4295
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4295:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4295
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3940
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3940:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3940
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43560880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120725, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43560880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(433d5d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(433d5d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1328): service - handleMessage() stop self
D/PMS     (  906): acquireWL(424189b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  906): sending alarm PendingIntent{42301790: PendingIntentRecord{43f31bf8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126085, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{4255f6a8: PendingIntentRecord{43e7f398 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138127, Int=0
D/PMS     (  906): acquireWL(41fb7218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1328): service - handleMessage() quit looper
,D/AutoSetting( 1328): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4311
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Killing 4311:com.htc.backup/1000 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/PMS     (  906): acquireWL(425b2fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4311
,D/PMS     (  906): releaseWL(425b2fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(41fb7218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
,D/PMS     (  906): releaseWL(424189b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42578d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(42578d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43c8d568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): acquireWL(425f8880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4254d068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1220): Vacuum at: now=1452693197642 tag=VacuumService
,D/PMS     (  906): releaseWL(43c8d568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425f8880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42558940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(42558940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4310c0e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
,D/PMS     (  906): releaseWL(4254d068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(4310c0e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425f0fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(425f0fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43bf90c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(43bf90c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426ab030): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): acquireWL(42630040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42630040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(441ecff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426ab030): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(44071798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(44071798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 4933 seconds from now (1452693198371)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
,D/libc    ( 1220): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a1fc +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(441ecff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4268fb88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(4268fb88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4416ae70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(4416ae70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
D/PMS     (  906): acquireWL(4383cac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{423c2ea8: PendingIntentRecord{41e510a0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142174, Int=0
D/PMS     (  906): acquireWL(4422c8a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4383cac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f3d0 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
,I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(4422c8a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(436b5ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(436b5ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(4350ec28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{43c6fd88: PendingIntentRecord{430ff668 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175392, Int=0
,D/PMS     (  906): releaseWL(4350ec28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1237): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(440d6428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180725, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440d6428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(439454f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(439454f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43b1c800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b1c800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(434f7028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434f7028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(44163c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(44163c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43ed05a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(43ed05a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43603ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=300724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43603ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4394b8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/BatteryService(  906): n_update end
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4394b8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43c79480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/PMS     (  906): releaseWL(43c79480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4266fb60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=360724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4266fb60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44053130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(44053130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(4270c2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4270c2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4321da48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=420724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4321da48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4347f0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4347f0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(44159290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(44159290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(432d1fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=480724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(432d1fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c18948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43c18948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43161300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43161300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(425f8378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=540724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425f8378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(439593a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(439593a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42c13320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(42c13320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b1c698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=600724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b1c698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(434c50e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  906): n_update end
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(434c50e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1237): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1237): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1237): sku_id=99
,D/ContactMessageStore( 1237): start background delete task...
,D/ContactMessageStore( 1237): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1237): size: 0 , 0
,D/ContactMessageStore( 1237): Background delete complete
,D/Process (  906): killProcessQuiet, pid=4282
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4282:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4282
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43543b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43543b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4257c6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=660724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4257c6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4313c858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4313c858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4370f8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4370f8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43b5c5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=720724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b5c5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(435c9c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(435c9c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(434be298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=780724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434be298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43144e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43144e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4315bb08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4315bb08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43cca730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=840725, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43cca730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426c1bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426c1bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(437df6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=900724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437df6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440fd030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(440fd030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4381ca28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c58b40: PendingIntentRecord{42474e08 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786239, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{43813160: PendingIntentRecord{43edaa28 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=949266, Int=0
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(4378e138): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4378e138): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4615 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{425e5650: PendingIntentRecord{42644520 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452693271545, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{424c3d10: PendingIntentRecord{41eaebb8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452693991888, Int=900000
,W/ContextImpl( 4549): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4549): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4549): MY_DEBUG = false
D/PMS     (  906): releaseWL(4381ca28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4615/10049)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(4421fd30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4421fd30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=4335
,I/ActivityManager(  906): Killing 4335:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4335
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4257b9a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(4257b9a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(421c68a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=960724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(421c68a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41ff67d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/BatteryService(  906): n_update end
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(41ff67d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42007b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/SmartSyncUtils( 4549): isEpsOn(), nState = 0
V/AlarmManager(  906): sending alarm PendingIntent{4228eb58: PendingIntentRecord{42693e98 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452694067321, Int=0
D/PMS     (  906): releaseWL(42007b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(42486c10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4549 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4549): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4549): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4549): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4549): SettingOnTime = 1452751200000, randomSettingOnTime = 1452749786000
,D/SmartSyncScreenOnOffTimeReceiver( 4549): SettingOffTime = 1452736800000, randomSettingOffTime = 1452737015000
,D/SmartSyncScreenOnOffTimeReceiver( 4549): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4549): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4549): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(42486c10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(423eb310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(423eb310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41d397e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1020725, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41d397e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(422f3f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(422f3f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41e36a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1080724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41e36a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4266c3d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4266c3d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(422ef108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1140724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(422ef108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437e7690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437e7690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42387698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42387698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(424358b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1200724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(424358b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425db9c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425db9c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42487cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42487cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43290890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1260724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43290890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c43380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c43380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425e0d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1320725, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425e0d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(431f6ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431f6ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
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
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43c7d060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43c7d060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41e4bcb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1380724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41e4bcb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426bd6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(426bd6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42630f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42630f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43bf9080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1440724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bf9080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4244c820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4244c820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4270b5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4270b5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42489240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1500724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42489240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437646a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437646a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(44154fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1560724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44154fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4395d480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4395d480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(436b8b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(436b8b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4268b418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1620724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4268b418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4250f930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4250f930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4308ccb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4308ccb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(441a4a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1680724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441a4a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440753a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440753a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42688a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1740724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42688a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43951ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(43951ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43111620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43111620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(4394b790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1800724, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4394b790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(422ad148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(422ad148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(432592b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(432592b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
I/ProcessStatsService(  906): Prepared write state in 33ms
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2016-01-12-16-48-20.bin
,D/PMS     (  906): acquireWL(43544d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41c58b40: PendingIntentRecord{42474e08 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1669293, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41e83260: PendingIntentRecord{425c8f20 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821698, Int=1800000
D/PMS     (  906): acquireWL(436b0528): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{43938638: PendingIntentRecord{439389a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1849426, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41d034d8: PendingIntentRecord{43edaa28 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1853358, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4377f788: PendingIntentRecord{43e50730 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452694358751, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{424c3d10: PendingIntentRecord{41eaebb8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452694891888, Int=900000
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): releaseWL(436b0528): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(439e9528): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(439e9528): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/LocationManagerService(  906): getAllProviders()=[passive, gps, network]
,D/PMS     (  906): acquireWL(44107de8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4549): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  906): acquireWL(440aac78): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PMS     (  906): releaseWL(44107de8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/EventLogService( 2185): Aggregate from 1452693114359 (log), 1452692558711 (data)
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(43544d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(440aac78): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(440cb168): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024942
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025100
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025301
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025310
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025320
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029653
,D/PMS     (  906): releaseWL(440cb168): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(44099458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420d0270: PendingIntentRecord{41dee880 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1860724, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44099458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44099140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(44099140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4661): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4661): ====startRecUseTime====
D/htc.customization.log.level( 4661):  is 
W/CustomizationLogLevel( 4661): Level value is invalid, use default level 2
D/CustomizationManager( 4661):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4661): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4661): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4661): Parsing tag category name = system
I/CustomizationCIDLoader( 4661): Parsing tag category name = application
I/CustomizationCIDLoader( 4661): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4661): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4661): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4661): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4661): Parsing tag category name = Settings
D/CustomizationManager( 4661):  Read CID file spent 0.091 (s)
D/CustomizationManager( 4661):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 4661): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4661): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4661): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4661): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4661, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4494
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
D/Process (  906): killProcessQuiet, pid=4142
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4494:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
I/ActivityManager(  906): Killing 4142:com.google.android.gm/u0a107 (adj 15): empty for 1830s
D/Process (  906): killProcessQuiet, pid=4432
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4418
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4393
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3861
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4067
I/ActivityManager(  906): Killing 4432:com.android.settings:remote/1000 (adj 15): empty for 1830s
I/ActivityManager(  906): Killing 4418:com.htc.calendar/u0a13 (adj 15): empty for 1830s
I/ActivityManager(  906): Killing 4393:com.nero.android.htc.sync/u0a8 (adj 15): empty for 1831s
I/ActivityManager(  906): Killing 3861:com.htc.mediamanager/u0a34 (adj 15): empty for 1831s
I/ActivityManager(  906): Killing 4067:com.google.android.apps.plus/u0a160 (adj 15): empty for 1832s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
W/asset   (  906): Copying FileAsset 0x62f3b1d8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Recipient 4432
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4142
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4393
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Recipient 3861
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4067
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4418
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{42180578 com.example.hello/10397} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1555): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1555): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1555): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
W/SQLiteConnectionPool( 2185): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
D/PMS     (  906): acquireWL(42691190): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(42691190): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
W/SystemReader( 1248): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/[PluginManager]RegisterService( 1328): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1328): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/IcingCorporaProvider( 2833): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
D/PhoneApp( 1237): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4675 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  906): acquireWL(4395af30): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4395af30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4383f650): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2833): UpdateCorporaTask done [took 180 ms] updated apps [took 180 ms] 
W/PackageManager(  906): Unable to load service info ResolveInfo{423f2a58 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4675): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4675): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4675): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4675): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4675): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4675): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4675): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4675): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4675): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4675): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4675): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4675): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4675): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4675): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4675): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4675): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4675): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4675): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4675): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4675): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4675): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4675): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4675): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4675): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4675): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4675): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4675): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4675): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4675): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4675): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4675): Opened ClientFlag.db in read-only mode
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4675/10100)
E/SQLiteLog( 4675): (3850) statement aborts at 59: [DELETE FROM CachedSearch111 WHERE timestamp<?] disk I/O error
E/SQLiteDBG( 4675): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.apps.docs/databases/DocList.db, handle = 0x5ca19008
E/AbstractDatabaseInstance( 4675): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4675): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 4675): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 4675): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AbstractDatabaseInstance( 4675): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 4675): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 4675): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AbstractDatabaseInstance( 4675): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4675): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4675): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4675): 	at fv.run(DocsApplication.java:288)
W/dalvikvm( 4675): threadid=11: thread exiting with uncaught exception (group=0x416b4e30)
E/AndroidRuntime( 4675): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4675): Process: com.google.android.apps.docs, PID: 4675
E/AndroidRuntime( 4675): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4675): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4675): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4675): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4675): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4675): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4675): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime( 4675): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime( 4675): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime( 4675): 	at fv.run(DocsApplication.java:288)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
W/GAV2    ( 4675): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4697 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4675/10100)
D/Process ( 4675): killProcess, pid=4675
D/Process ( 4675): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4697): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  906): Recipient 4675
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4675) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
F/ProcessStats(  906): Starting service ServiceState{42384550 com.google.android.apps.docs.sync.syncadapter.ContentSyncService pkg=com.google.android.apps.docs proc=42384550} without owner
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/SQLiteDatabase( 4697): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4697): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4697): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4697): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4697): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4697): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4697): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4697): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4697): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4697): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4697): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4697): threadid=10: thread exiting with uncaught exception (group=0x416b4e30)
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1452694968368.dbox_tmp: open failed: EROFS (Read-only file system)
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
E/AndroidRuntime( 4697): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4697): Process: com.android.keychain, PID: 4697
E/AndroidRuntime( 4697): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4697): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4697): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4697): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4697): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4697): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4697): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4697): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4697): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4697): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
I/TrimMemoryManager( 1270): [trimMemory] 5
D/Process ( 4697): killProcess, pid=4697
D/Process ( 4697): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452694968390.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 4697
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4697) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10953ms
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4717 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 4717): getInstance(Context context)
D/AppTag  ( 4717): getInstance(Context context)
D/AppTag  ( 4717): onCreate()
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4731 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
F/ProcessStats(  906): Starting service ServiceState{42384550 com.google.android.apps.docs.sync.syncadapter.ContentSyncService pkg=com.google.android.apps.docs proc=42384550} without owner
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1452694968537.dbox_tmp: open failed: EROFS (Read-only file system)
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
E/ErrorReport(  906): 	at com.android.server.am.ActiveServices.publishServiceLocked(ActiveServices.java:868)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.publishService(ActivityManagerService.java:13917)
E/ErrorReport(  906): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:898)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
E/ErrorReport(  906): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  906): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 23 more
I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  906): acquireWL(432a6af8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4731 10160 null
D/PMS     (  906): releaseWL(432a6af8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/SQLiteDatabase( 4731): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4731): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4731): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4731): 	at del.a(PG:264)
E/SQLiteDatabase( 4731): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4731): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  906): Resuming delayed broadcast
E/SQLiteDatabase( 4731): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4731): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4731): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4731): 	at del.a(PG:264)
E/SQLiteDatabase( 4731): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4731): 	at java.lang.Thread.run(Thread.java:864)
E/EsApplication( 4731): Failed app initialization
E/EsApplication( 4731): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4731): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4731): 	at del.a(PG:264)
E/EsApplication( 4731): 	at eeq.run(PG:187)
E/EsApplication( 4731): 	at java.lang.Thread.run(Thread.java:864)
D/Process (  906): killProcessQuiet, pid=4367
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4367:com.google.android.music:main/u0a154 (adj 15): empty for 1827s
D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2185): Clearing selected account for com.test.thalitest
W/dalvikvm( 4092): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  906): Recipient 4367
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 4367): Died!
I/LocationSettingsChecker( 2185): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2185): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2185): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x656419d0
E/DriveAsyncService( 2185): disk I/O error (code 3850)
E/DriveAsyncService( 2185): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2185): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2185): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2185): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2185): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2185): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 2185): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2185): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2185): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2185): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2185): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2185): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2185): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2185): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2185): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2185): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2185): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2185): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2185): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2185): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2185): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2185): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2185): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2185): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2185): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2185): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2185): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 2185): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2185): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 2185): threadid=48: thread exiting with uncaught exception (group=0x416b4e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 2185): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2185): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2185): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2185): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2185): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2185): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2185): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2185): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2185): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2185): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2185): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2185): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2185): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2185): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2185): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2185): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2185): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 2185): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 2185): Process: com.google.android.gms, PID: 2185
E/AndroidRuntime( 2185): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2185): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 2185): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 2185): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2185): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2185): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2185): killProcess, pid=2185
D/Process ( 2185): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 2185
I/ActivityManager(  906): Process com.google.android.gms (pid 2185) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10560ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20560ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30560ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30560ms
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30560ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30560ms
I/ActivityManager(  906): Resuming delayed broadcast
D/WifiService(  906): Client connection lost with reason: 4
D/PMS     (  906): handleWLDeath(4383f650): PARTIAL_WAKE_LOCK  Icing 0x1
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b77c70 +
I/Prism.WidgetManager( 1270): onLoadItems() +

```
