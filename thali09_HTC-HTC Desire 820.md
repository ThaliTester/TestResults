#### Test 56672827b6f75d5_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  907): setLight #0: color=#26
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,V/LightsService(  907): setLight #0: color=#23
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
V/LightsService(  907): setLight #0: color=#1c
V/LightsService(  907): setLight #0: color=#15
V/LightsService(  907): setLight #0: color=#14
E/cutils-trace( 4486): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4486): ====startRecUseTime====
D/htc.customization.log.level( 4486):  is 
W/CustomizationLogLevel( 4486): Level value is invalid, use default level 2
D/CustomizationManager( 4486):  Read ACC file spent 0.069 (s)
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4486): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4486): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4486): Parsing tag category name = system
I/CustomizationCIDLoader( 4486): Parsing tag category name = application
I/CustomizationCIDLoader( 4486): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4486): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4486): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4486): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4486): Parsing tag category name = Settings
D/CustomizationManager( 4486):  Read CID file spent 0.114 (s)
D/CustomizationManager( 4486):  All configurations done spent 0.114 (s)
W/HtcNativeFlag( 4486): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4486): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4486): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4486): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4486
D/PMS     (  907): acquireHCC(4352dd88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(4312eac8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x62daa4d0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1114164896
D/PMS     (  907): acquireWL(4289b7e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41e2a330
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4497 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4497): Copying FileAsset 0x5cae1e28 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4497): Binding Chromium to main looper Looper (main, tid 1) {41d13680}
I/LibraryLoader( 4497): Expected native library version number "",actual native library version number ""
I/chromium( 4497): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4497): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425e4bb0:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4497): 1104322408: getState(). Returning 12
D/PMS     (  907): acquireWL(42077a20): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): acquireWL(4206fb68): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): releaseWL(4206fb68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4497): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4497): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4497): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4497): Local Branch: 
I/Adreno-EGL( 4497): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4497): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4497):                  aa63bbd948f41d15fc72f585e
W/chromium( 4497): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4497): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4497): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4497): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4497): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4497): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4497): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4497): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4497): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4497): CordovaWebView is running on device made by: HTC
,D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/AwContents( 4497): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1271
W/ResourceType( 4497): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4497): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41d5b618, mServedView=org.apache.cordova.engine.SystemWebView{41d21280 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=4497
W/AwContents( 4497): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +278ms
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  907): releaseWL(4289b7e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  907): Waited long enough for: ServiceRecord{428a02b8 u0 com.htc.htclocationservice/.AutoSettingService}
D/JsMessageQueue( 4497): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4497): JniHelper::setJavaVM(0x418d1010), pthread_self() = 1663724472
I/chromium( 4497): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 12.001MB for 42652-byte allocation
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 12.079MB for 95956-byte allocation
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 12.158MB for 143930-byte allocation
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 12.272MB for 215890-byte allocation
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 12.448MB for 323830-byte allocation
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 12.719MB for 485740-byte allocation
,I/SensorManager(  907): mEventCount = 1200
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 13.706MB for 1092904-byte allocation
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 14.640MB for 1639352-byte allocation
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 15.885MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(4352dd88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(4312eac8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 18.074MB for 3688532-byte allocation
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,W/jxcore-log( 4497): Initializing JXcore engine
,W/jxcore-log( 4497): JXcore engine is ready
,W/jxcore-log( 4497): Starting JXcore engine
,W/jxcore-log( 4497): Platform android
W/jxcore-log( 4497): 
,W/jxcore-log( 4497): Process ARCH arm
W/jxcore-log( 4497): 
,I/jxcore-log( 4497): JXcore Cordova bridge is ready!
I/jxcore-log( 4497): 
,W/jxcore-log( 4497): JXcore engine is started
D/PMS     (  907): releaseWL(42077a20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/jxcore  ( 4497): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4497): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4497): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4497): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 27ms. Plugin should use CordovaInterface.getThreadPool().
,D/PMS     (  907): acquireWL(431fc880): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
,I/FeedHostManager( 1271): [onResume]
,I/FeedProviderManager( 1271): onResume
,I/SocialFeedProvider( 1271): +onResume
,I/SocialFeedProvider( 1271): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1271): -onResume
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1271/10076)
,I/InputMethodManagerService(  907): Disable input method client, pid=4497
,W/IInputConnectionWrapper( 4497): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  907): Enable input method client, pid=1271
,D/PMS     (  907): releaseWL(431fc880): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  907): killProcessQuiet, pid=3918
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  907): Killing 3918:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3918
E/libEGL  ( 4497): call to OpenGL ES API with no current context (logged once per thread)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1187): nl80211: survey data missing!
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=123 rxSum=105} preTxRxSum={txSum=123 rxSum=105}
D/WifiDataStallTracker(  907): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20751 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20752 delay=15s
D/PMS     (  907): acquireWL(43204868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{428136a8: PendingIntentRecord{4267d6b0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=107778, Int=0
D/PMS     (  907): releaseWL(43204868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4243fa00
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  907): pid=907, uid=1000
W/PMS     (  907): mWirelessDisplayManager is null
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,W/BatSI   (  907): Couldn't get kernel wake lock stats
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4243fa00, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41dcb388
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@426368e8
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 322ms
,D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
,D/PMS     (  907): nativeSetAutoSuspend:true done
,D/HABCtrl (  907): TPE algorithm. remove timeout.
,D/PMS     (  907): OOBE c monitor 11
,I/InputManager(  907): Cancel all due to getting PMS screen off broadcast,
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43264190)
,D/NfcService( 1258): ScreenObserver: OFF
,D/NfcService( 1258): applyRouting - 0
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=1271
D/PMS     (  907): acquireWL(43263968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43263968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  907): wakingUp
D/NfcService( 1258): applyRouting -2
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMS     (  907): acquireWL(43264f70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  907): releaseWL(43264f70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
,D/NfcService( 1258): applyRouting - 0
D/NfcService( 1258): applyRouting -2
D/MtpService( 2759): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2759): [MTP][onReceive]-
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  907): acquireWL(43268940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
,D/PMS     (  907): releaseWL(43268940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/ClockThread( 1119): stop update clock
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20753 delay=15s
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4552 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): SET_SCREEN_ON:On
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1187): BG scan when screen On
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): Match BG scan, scan!
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/WifiNative-wlan0(  907):    returned true
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3,
I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  907): updateScreenOn: false
,W/ContextImpl( 4552): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4552): isEpsOn(), nState = 0
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(43279738): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4552 1000 null
D/PMS     (  907): acquireWL(4327ae88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4327ae88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4327c758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43279738): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  907): releaseWL(4327c758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1740): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): onScreenOn: 1453394666436
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1740): onScreenOn: 1453394666436
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41dcb388
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41dcb388, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@426368e8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4552): getMobilePolicyEnabled, result = true
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(43281178): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/FeedHostManager( 1271): [onPause]
,I/FeedProviderManager( 1271): onPause
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41e2a330
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
,D/AutoSetting( 1333): receiver - intent: android.intent.action.USER_PRESENT
,D/TetherSettings( 3882): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3882): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3882): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3882): Cust_ConnectToPC   : spcsc>false
D/        ( 3882): Cust_ConnectToPC   : IPT>true
D/        ( 3882): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3882): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3882): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3882): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3882): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20753 mDataStallAlarmIntent=PendingIntent{42187228: PendingIntentRecord{4267d6b0 android broadcastIntent}}
,I/PSReceiver( 3882): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1333): service - onCreate()
,D/AutoSetting( 1333): service - AddressCache: using context: com.htc.Weather
,I/SmartNS_PSService( 3882): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
D/PMS     (  907): releaseWL(43281178): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/Settings( 3882): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3882):  defaultType:0
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
,D/AutoSetting( 1333): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  907): request 427e58c0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/PMS     (  907): acquireWL(4328b2c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,W/ContextImpl( 4552): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4552): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4552): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4552): isEpsOn(), nState = 0
D/WifiService(  907): New client listening to asynchronous messages
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): SET_SCREEN_ON:Off
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true,
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360,
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:164, mTXpacketCount:164, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,I/PhoneStatusBar( 1119): removeHeadsNotification.gc: 58
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  907): acquireWL(43297d18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43297d18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43298a78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1740): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1740): onScreenOff
D/PMS     (  907): releaseWL(43298a78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426368e8
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426368e8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426368e8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426368e8,
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425b4480 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425b4480 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	,at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	,at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	,at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455),
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	,at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): ,	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712),
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4328b2c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1187): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1187): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomn,ess: count=8 entropy=3
D/wpa_supplicant( 1187): Add randomness: count=9 entropy=4
D/wpa_supplicant( 1187): Add randomness: count=10 entropy=5
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: DISCONNECTED -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000110765790
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000110765817
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000110765828
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@432a3658 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@432a3658 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@432a3658 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 110765790, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 110765817, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 110765828, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4285
,I/ActivityManager(  907): Killing 4285:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4285
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/AutoSetting( 1333): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1333): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1333): service - requestNLP() NetworkLocationProvider not enabled
,D/Process (  907): killProcessQuiet, pid=3978
,I/ActivityManager(  907): Killing 3978:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3978
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42795010 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(432b9398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{439472c0: PendingIntentRecord{42913258 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=125788, Int=0
,D/PMS     (  907): acquireWL(432ba1c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(432b9398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(432bf678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(432bf678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(432ba1c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432c4490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): releaseWL(432c4490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432c8318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): acquireWL(432cfd48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432d69e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1225): Vacuum at: now=1453394683720 tag=VacuumService
,D/PMS     (  907): releaseWL(432c8318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(432cfd48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432dfb80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): releaseWL(432dfb80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432e3980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1374/10029)
,D/PMS     (  907): releaseWL(432d69e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): releaseWL(432e3980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432ea118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): releaseWL(432ea118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432edfa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): releaseWL(432edfa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432f3f78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): acquireWL(432fb968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(432fb968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43302180): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(432f3f78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(433068e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): releaseWL(433068e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0],
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029),
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1225): Scheduling Phenotype for one-off execution 14387 seconds from now (1453394684615)
,D/GetConfigurationSnapshotOperation( 1225): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1225): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024,
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a908 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success,
,D/wpa_supplicant( 1187): nl80211: Event message available,
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
,D/wpa_supplicant( 1187): Add randomness: count=11 entropy=6
D/wpa_supplicant( 1187): Add randomness: count=12 entropy=7
D/wpa_supplicant( 1187): Add randomness: count=13 entropy=8
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
,I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
,I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=14 entropy=9
D/wpa_supplicant( 1187): Add randomness: count=15 entropy=10
D/wpa_supplicant( 1187): Add randomness: count=16 entropy=11
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
,W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000128015323
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000128015350
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000128015361
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 128015323, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 128015350, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 128015361, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=14 [7][1][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(43302180): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(433455d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): releaseWL(433455d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  907): acquireWL(4334b688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): releaseWL(4334b688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42ffe978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42ffe978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1333): service - handleMessage() stop self
,D/AutoSetting( 1333): service - handleMessage() quit looper
,D/AutoSetting( 1333): service - onDestroy() END
,I/ActivityManager(  907): Killing 4188:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4188
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4188
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42527c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{420eec50: PendingIntentRecord{4291a338 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=139603, Int=0
,D/PMS     (  907): releaseWL(42527c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1374/10029)
,D/PMS     (  907): acquireWL(444e0fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{426b1f38: PendingIntentRecord{426b1ed8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142197, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(431905a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(444e0fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d00b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  907): acquireWL(43f577f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=142396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43f577f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 12(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=17 entropy=12
D/wpa_supplicant( 1187): Add randomness: count=18 entropy=13
D/wpa_supplicant( 1187): Add randomness: count=19 entropy=14
D/wpa_supplicant( 1187): Add randomness: count=20 entropy=15
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL], c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=21 entropy=16
D/wpa_supplicant( 1187): Add randomness: count=22 entropy=17
D/wpa_supplicant( 1187): Add randomness: count=23 entropy=18
D/wpa_supplicant( 1187): Add randomness: count=24 entropy=19
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000128015323
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000145447150
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-84
I/wpa_supplicant( 1187): tsf=0000000145447163
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=3
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000145447172
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 128015323, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 145447150, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 145447163, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 145447172, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(431905a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=25 entropy=20
D/wpa_supplicant( 1187): Add randomness: count=26 entropy=21
D/wpa_supplicant( 1187): Add randomness: count=27 entropy=22
D/wpa_supplicant( 1187): Add randomness: count=28 entropy=23
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): ,[NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=29 entropy=24
D/wpa_supplicant( 1187): Add randomness: count=30 entropy=25
D/wpa_supplicant( 1187): Add randomness: count=31 entropy=26
D/wpa_supplicant( 1187): Add randomness: count=32 entropy=27
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000162834885
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000162834911
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-84
I/wpa_supplicant( 1187): tsf=0000000162834922
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=3
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000162834931
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 162834885, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 162834911, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 162834922, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 162834931, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43218680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43218680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(420649d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{4403dd28: PendingIntentRecord{43d96418 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=177661, Int=0
,D/PMS     (  907): releaseWL(420649d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=33 entropy=28
D/wpa_supplicant( 1187): Add randomness: count=34 entropy=29
D/wpa_supplicant( 1187): Add randomness: count=35 entropy=30
D/wpa_supplicant( 1187): Add randomness: count=36 entropy=31
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): ,[NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=37 entropy=32
D/wpa_supplicant( 1187): Add randomness: count=38 entropy=33
D/wpa_supplicant( 1187): Add randomness: count=39 entropy=34
D/wpa_supplicant( 1187): Add randomness: count=40 entropy=35
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000180254787
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000180254812
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-80
,I/wpa_supplicant( 1187): tsf=0000000180254823
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=3
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000180254831
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 180254787, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 180254812, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 180254823, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 180254831, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null,
,D/PMS     (  907): acquireWL(4250c468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4250c468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS,
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=41 entropy=36
D/wpa_supplicant( 1187): Add randomness: count=42 entropy=37
D/wpa_supplicant( 1187): Add randomness: count=43 entropy=38
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=44 entropy=39
D/wpa_supplicant( 1187): Add randomness: count=45 entropy=40
D/wpa_supplicant( 1187): Add randomness: count=46 entropy=41
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WP,S: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000197372403
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000197372428
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-76
I/wpa_supplicant( 1187): tsf=0000000197372439
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=3
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000180254831
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 197372403, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 197372428, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 197372439, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 180254831, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42864738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=202396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42864738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=47 entropy=42
D/wpa_supplicant( 1187): Add randomness: count=48 entropy=43
D/wpa_supplicant( 1187): Add randomness: count=49 entropy=44
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=50 entropy=45
D/wpa_supplicant( 1187): Add randomness: count=51 entropy=46
D/wpa_supplicant( 1187): Add randomness: count=52 entropy=47
D/wp,a_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000214754840
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g,
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000214754866
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-83
I/wpa_supplicant( 1187): tsf=0000000197372439
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 214754840, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 214754866, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 197372439, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4286cfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4286cfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=53 entropy=48
D/wpa_supplicant( 1187): Add randomness: count=54 entropy=49
D/wpa_supplicant( 1187): Add randomness: count=55 entropy=50
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=56 entropy=51
D/wpa_supplicant( 1187): Add randomness: count=57 entropy=52
D/wpa_supplicant( 1187): Add randomness: count=58 entropy=53
D/wp,a_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000231832320
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000231832346
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000231832358
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 231832320, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 231832346, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 231832358, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=59 entropy=54
D/wpa_supplicant( 1187): Add randomness: count=60 entropy=55
D/wpa_supplicant( 1187): Add randomness: count=61 entropy=56
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=62 entropy=57
D/wpa_supplicant( 1187): Add randomness: count=63 entropy=58
D/wpa_supplicant( 1187): Add randomness: count=64 entropy=59
D/wp,a_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000248891900
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000248891927
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000248891938
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 248891900, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 248891927, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 248891938, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425d1390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425d1390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(435448b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=262396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(435448b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=65 entropy=60
D/wpa_supplicant( 1187): Add randomness: count=66 entropy=61
D/wpa_supplicant( 1187): Add randomness: count=67 entropy=62
D/wpa_supplicant( 1187): Add randomness: count=68 entropy=63
D/wpa_supplicant( 1187): Add randomness: count=69 entropy=64
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=70 entropy=65
D/wpa_supplicant( 1187): Add randomness: count=71 entropy=66
D/wpa_supplicant( 1187): Add randomness: count=72 entropy=67
D/wpa_supplicant( 1187): Add randomness: count=73 entropy=68
D/wpa_supplicant( 1187): Add randomness: count=74 entropy=69
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (636) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000266335185
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000266335211
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-83
I/wpa_supplicant( 1187): tsf=0000000266335233
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=4
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-56
,I/wpa_supplicant( 1187): tsf=0000000266335222
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=5
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-93
I/wpa_supplicant( 1187): tsf=0000000266335242
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 266335185, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 266335211, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 266335233, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 266335222, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 266335242, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=75 entropy=70
D/wpa_supplicant( 1187): Add randomness: count=76 entropy=71
D/wpa_supplicant( 1187): Add randomness: count=77 entropy=72
D/wpa_supplicant( 1187): Add randomness: count=78 entropy=73
D/wpa_supplicant( 1187): Add randomness: count=79 entropy=74
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=80 entropy=75
D/wpa_supplicant( 1187): Add randomness: count=81 entropy=76
D/wpa_supplicant( 1187): Add randomness: count=82 entropy=77
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): Add randomness: count=83 entropy=78
D/wpa_supplicant( 1187): Add randomness: count=84 entropy=79
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (636) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000283734503
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000283734529
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000283734550
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=4
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-56
I/wpa_supplicant( 1187): tsf=0000000283734540
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=5
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-93
I/wpa_supplicant( 1187): tsf=0000000283734559
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432,
I/wpa_supplicant( 1187): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 283734503, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 283734529, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 283734550, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 283734540, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 283734559, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1225): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4357c080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4357c080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  907): updateBatteryInfo
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=85 entropy=80
D/wpa_supplicant( 1187): Add randomness: count=86 entropy=81
D/wpa_supplicant( 1187): Add randomness: count=87 entropy=82
D/wpa_supplicant( 1187): Add randomness: count=88 entropy=83
D/wpa_supplicant( 1187): Add randomness: count=89 entropy=84
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=90 entropy=85
D/wpa_supplicant( 1187): Add randomness: count=91 entropy=86
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): Add randomness: count=92 entropy=87
D/wpa_supplicant( 1187): Add randomness: count=93 entropy=88
D/wpa_supplicant( 1187): Add randomness: count=94 entropy=89
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (636) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000283734503
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000301094562
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000301094583
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=4
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-56
I/wpa_supplicant( 1187): tsf=0000000301094573
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=5
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-93
I/wpa_supplicant( 1187): tsf=0000000301094592
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 283734503, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 301094562, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 301094583, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 301094573, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 301094592, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43561bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43561bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1187): nl80211: Event message available,
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
,I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=95 entropy=90
D/wpa_supplicant( 1187): Add randomness: count=96 entropy=91
D/wpa_supplicant( 1187): Add randomness: count=97 entropy=92
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431,
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=98 entropy=93
D/wpa_supplicant( 1187): Add randomness: count=99 entropy=94
D/wpa_supplicant( 1187): Add randomness: count=100 entropy=95
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (636) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000318475025
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000318475052
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
,I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000318475063
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=4
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-56
I/wpa_supplicant( 1187): tsf=0000000301094573
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=5
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-93
I/wpa_supplicant( 1187): tsf=0000000301094592
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 318475025, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 318475052, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 318475063, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 301094573, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 301094592, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44051e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=322396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44051e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=101 entropy=96
D/wpa_supplicant( 1187): Add randomness: count=102 entropy=97
D/wpa_supplicant( 1187): Add randomness: count=103 entropy=98
D/wpa_supplicant( 1187): Add randomness: count=104 entropy=99
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplic,ant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=105 entropy=100
D/wpa_supplicant( 1187): Add randomness: count=106 entropy=101
D/wpa_supplicant( 1187): Add randomness: count=107 entropy=102
D/wpa_supplicant( 1187): Add randomness: count=108 entropy=103
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (489) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000335854970
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000335855007
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-85
I/wpa_supplicant( 1187): tsf=0000000335855017
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=4
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000335854996
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS],
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 335854970, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 335855007, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 335855017, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 335854996, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/Process (  907): killProcessQuiet, pid=4318
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4318:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4318
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(44558388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44558388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=109 entropy=104
D/wpa_supplicant( 1187): Add randomness: count=110 entropy=105
D/wpa_supplicant( 1187): Add randomness: count=111 entropy=106
D/wpa_supplicant( 1187): Add randomness: count=112 entropy=107
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=113 entropy=108
D/wpa_supplicant( 1187): Add randomness: count=114 entropy=109
D/wpa_supplicant( 1187): Add randomness: count=115 entropy=110
D/wpa_supplicant( 1187): Add randomness: count=116 entropy=111
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (489) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000353245513
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000353245552
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
,I/wpa_supplicant( 1187): tsf=0000000353245562
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=4
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000353245541
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 353245513, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 353245552, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 353245562, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 353245541, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=117 entropy=112
D/wpa_supplicant( 1187): Add randomness: count=118 entropy=113
D/wpa_supplicant( 1187): Add randomness: count=119 entropy=114
D/wpa_supplicant( 1187): Add randomness: count=120 entropy=115
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=121 entropy=116
D/wpa_supplicant( 1187): Add randomness: count=122 entropy=117
D/wpa_supplicant( 1187): Add randomness: count=123 entropy=118
D/wpa_supplicant( 1187): Add randomness: count=124 entropy=119
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (489) for get BSS: id=0
,I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000353245513
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
,I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000370624951
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000370624962
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos,
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=4
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000370624941
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 353245513, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 370624951, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 370624962, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 370624941, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(440b86d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(440b86d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(43fad3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=382396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43fad3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=125 entropy=120
D/wpa_supplicant( 1187): Add randomness: count=126 entropy=121
D/wpa_supplicant( 1187): Add randomness: count=127 entropy=122
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=128 entropy=123
D/wpa_supplicant( 1187): Add randomness: count=129 entropy=124
D/wpa_supplicant( 1187): Add randomness: count=130 entro,py=125
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (489) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000387994204
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000387994230
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000387994241
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=4
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000370624941
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 387994204, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 387994230, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 387994241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 370624941, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1187): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=131 entropy=126
D/wpa_supplicant( 1187): Add randomness: count=132 entropy=127
D/wpa_supplicant( 1187): Add randomness: count=133 entropy=128
D/wpa_supplicant( 1187): Add randomness: count=134 entropy=129
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1187): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=135 entropy=130
D/wpa_supplicant( 1187): Add randomness: count=136 entropy=131
,D/wpa_supplicant( 1187): Add randomness: count=137 entropy=132
D/wpa_supplicant( 1187): Add randomness: count=138 entropy=133
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (519) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000405394997
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
,I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000405395022
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000405395033
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=6
I/wpa_supplicant( 1187): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000405395042
I/wpa_supplicant( 1187): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC Wi-Free
I/wpa_supplicant( 1187): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 405394997, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 405395022, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 405395033, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 405395042, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=139 entropy=134
D/wpa_supplicant( 1187): Add randomness: count=140 entropy=135
D/wpa_supplicant( 1187): Add randomness: count=141 entropy=136
D/wpa_supplicant( 1187): Add randomness: count=142 entropy=137
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/,wpa_supplicant( 1187): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=143 entropy=138
D/wpa_supplicant( 1187): Add randomness: count=144 entropy=139
D/wpa_supplicant( 1187): Add randomness: count=145 entropy=140
D/wpa_supplicant( 1187): Add randomness: count=146 entropy=141
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (519) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000422512188
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000422512213
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000422512224
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=6
I/wpa_supplicant( 1187): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000422512233
I/wpa_supplicant( 1187): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC Wi-Free
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 422512188, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 422512213, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 422512224, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 422512233, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43a1ae48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43a1ae48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=147 entropy=142
D/wpa_supplicant( 1187): Add randomness: count=148 entropy=143
D/wpa_supplicant( 1187): Add randomness: count=149 entropy=144
D/wpa_supplicant( 1187): Add randomness: count=150 entropy=145
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/,wpa_supplicant( 1187): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=151 entropy=146
D/wpa_supplicant( 1187): Add randomness: count=152 entropy=147
D/wpa_supplicant( 1187): Add randomness: count=153 entropy=148
D/wpa_supplicant( 1187): Add randomness: count=154 entropy=149
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (519) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000439874976
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000439875002
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000439875013,
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=6
I/wpa_supplicant( 1187): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000439875022
I/wpa_supplicant( 1187): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC Wi-Free
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 439874976, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 439875002, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 439875013, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 439875022, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43fb1028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=442396, Int=0
,D/PMS     (  907): releaseWL(43fb1028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=155 entropy=150
D/wpa_supplicant( 1187): Add randomness: count=156 entropy=151
D/wpa_supplicant( 1187): Add randomness: count=157 entropy=152
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=158 entropy=153
D/wpa_supplicant( 1187): Add randomness: count=159 entropy=154
D/wpa_supplicant( 1187): Add randomness: count=160 entro,py=155
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (519) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000457042497
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000457042524
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000457042535
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=6
I/wpa_supplicant( 1187): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000439875022
I/wpa_supplicant( 1187): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC Wi-Free
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 457042497, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 457042524, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 457042535, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 439875022, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(440b9500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440b9500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=161 entropy=156
D/wpa_supplicant( 1187): Add randomness: count=162 entropy=157
D/wpa_supplicant( 1187): Add randomness: count=163 entropy=158
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=164 entropy=159
D/wpa_supplicant( 1187): Add randomness: count=165 entropy=160
D/wpa_supplicant( 1187): Add randomness: count=166 entro,py=161
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000474407000
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000474407026
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000474407037
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 474407000, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 474407026, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 474407037, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available,
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47,
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=167 entropy=162
D/wpa_supplicant( 1187): Add randomness: count=168 entropy=163
D/wpa_supplicant( 1187): Add randomness: count=169 entropy=164
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
,D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
,I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=170 entropy=165
D/wpa_supplicant( 1187): Add randomness: count=171 entropy=166
D/wpa_supplicant( 1187): Add randomness: count=172 entropy=167
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000491784207
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
,I/wpa_supplicant( 1187): tsf=0000000491784232
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000491784243
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 491784207, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 491784232, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 491784243, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428680e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(428680e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(445173d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=502396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(445173d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=173 entropy=168
D/wpa_supplicant( 1187): Add randomness: count=174 entropy=169
D/wpa_supplicant( 1187): Add randomness: count=175 entropy=170
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=176 entropy=171
D/wpa_supplicant( 1187): Add randomness: count=177 entropy=172
D/wpa_supplicant( 1187): Add randomness: count=178 entro,py=173
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000509155046
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000509155072
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000509155083
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 509155046, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 509155072, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 509155083, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1225): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=179 entropy=174
D/wpa_supplicant( 1187): Add randomness: count=180 entropy=175
D/wpa_supplicant( 1187): Add randomness: count=181 entropy=176
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=182 entropy=177
D/wpa_supplicant( 1187): Add randomness: count=183 entropy=178
D/wpa_supplicant( 1187): Add randomness: count=184 entro,py=179
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000526504447
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000526504473
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000526504484
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
,I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 526504447, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 526504473, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 526504484, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43742f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(43742f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=185 entropy=180
D/wpa_supplicant( 1187): Add randomness: count=186 entropy=181
D/wpa_supplicant( 1187): Add randomness: count=187 entropy=182
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=188 entropy=183
D/wpa_supplicant( 1187): Add randomness: count=189 entropy=184
D/wpa_supplicant( 1187): Add randomness: count=190 entropy=185
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000543895018
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000543895045,
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000543895056
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 543895018, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 543895045, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 543895056, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428ac4f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100,
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(428ac4f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=191 entropy=186
D/wpa_supplicant( 1187): Add randomness: count=192 entropy=187
D/wpa_supplicant( 1187): Add randomness: count=193 entropy=188
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=194 entropy=189
D/wpa_supplicant( 1187): Add randomness: count=195 entropy=190
D/wpa_supplicant( 1187): Add randomness: count=196 entro,py=191
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000561289540
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000561289566
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000561289577
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 561289540, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 561289566, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 561289577, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(440c0f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=562396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(440c0f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available,
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
,D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=197 entropy=192
D/wpa_supplicant( 1187): Add randomness: count=198 entropy=193
D/wpa_supplicant( 1187): Add randomness: count=199 entropy=194
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=200 entropy=195
D/wpa_supplicant( 1187): Add randomness: count=201 entropy=196
D/wpa_supplicant( 1187): Add randomness: count=202 entropy=197
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000561289540
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1,
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000578442129
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
,I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412,
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000578442141
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 561289540, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 578442129, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 578442141, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiManager( 1225): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=203 entropy=198
D/wpa_supplicant( 1187): Add randomness: count=204 entropy=199
D/wpa_supplicant( 1187): Add randomness: count=205 entropy=200
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=206 entropy=201
D/wpa_supplicant( 1187): Add randomness: count=207 entropy=202
D/wpa_supplicant( 1187): Add randomness: count=208 entropy=203
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 l,en=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000561289540
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000595541914
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412,
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000595541925
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 561289540, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 595541914, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 595541925, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(434d3750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(434d3750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=209 entropy=204
D/wpa_supplicant( 1187): Add randomness: count=210 entropy=205
D/wpa_supplicant( 1187): Add randomness: count=211 entropy=206
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=212 entropy=207
D/wpa_supplicant( 1187): Add randomness: count=213 entropy=208
D/wpa_supplicant( 1187): Add randomness: count=214 entropy=209
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000612663820
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000612663845
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000612663856
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 612663820, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 612663845, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 612663856, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(43897c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=622396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43897c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=215 entropy=210
D/wpa_supplicant( 1187): Add randomness: count=216 entropy=211
D/wpa_supplicant( 1187): Add randomness: count=217 entropy=212
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=218 entropy=213
D/wpa_supplicant( 1187): Add randomness: count=219 entropy=214
D/wpa_supplicant( 1187): Add randomness: count=220 entro,py=215
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000630044749
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000630044775
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000630044786
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 630044749, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 630044775, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 630044786, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=221 entropy=216
D/wpa_supplicant( 1187): Add randomness: count=222 entropy=217
D/wpa_supplicant( 1187): Add randomness: count=223 entropy=218
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=224 entropy=219
D/wpa_supplicant( 1187): Add randomness: count=225 entropy=220
D/wpa_supplicant( 1187): Add randomness: count=226 entro,py=221
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
,I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000647424934
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000647424960
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700,
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000647424970
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 647424934, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 647424960, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 647424970, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43564ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43564ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=227 entropy=222
D/wpa_supplicant( 1187): Add randomness: count=228 entropy=223
D/wpa_supplicant( 1187): Add randomness: count=229 entropy=224
D/wpa_supplicant( 1187): Add randomness: count=230 entropy=225
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=231 entropy=226
D/wpa_supplicant( 1187): Add randomness: count=232 entropy=227
D/wpa_supplicant( 1187): Add randomness: count=233 entropy=228
D/wpa_supplicant( 1187): Add randomness: count=234 entropy=229
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
,I/wpa_supplicant( 1187): tsf=0000000664864599
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000664864624
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000664864635
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
,I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000664864644
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 664864599, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 664864624, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 664864635, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 664864644, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(432474d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(432474d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=235 entropy=230
D/wpa_supplicant( 1187): Add randomness: count=236 entropy=231
D/wpa_supplicant( 1187): Add randomness: count=237 entropy=232
D/wpa_supplicant( 1187): Add randomness: count=238 entropy=233
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=239 entropy=234
D/wpa_supplicant( 1187): Add randomness: count=240 entropy=235
D/wpa_supplicant( 1187): Add randomness: count=241 entropy=236
D/wpa_supplicant( 1187): Add randomness: count=242 entropy=237
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000682264840
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000682264867
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000682264878
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000682264886
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 682264840, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 682264867, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 682264878, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 682264886, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425ecae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=682396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425ecae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=243 entropy=238
D/wpa_supplicant( 1187): Add randomness: count=244 entropy=239
D/wpa_supplicant( 1187): Add randomness: count=245 entropy=240
D/wpa_supplicant( 1187): Add randomness: count=246 entropy=241
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=247 entropy=242
D/wpa_supplicant( 1187): Add randomness: count=248 entropy=243
D/wpa_supplicant( 1187): Add randomness: count=249 entropy=244
D/wpa_supplicant( 1187): Add randomness: count=250 entropy=245
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000699706239
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000699706265
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-77
I/wpa_supplicant( 1187): tsf=0000000699706276
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000699706285
,I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 699706239, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 699706265, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 699706276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 699706285, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=251 entropy=246
D/wpa_supplicant( 1187): Add randomness: count=252 entropy=247
D/wpa_supplicant( 1187): Add randomness: count=253 entropy=248
D/wpa_supplicant( 1187): Add randomness: count=254 entropy=249
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=255 entropy=250
D/wpa_supplicant( 1187): Add randomness: count=256 entropy=251
D/wpa_supplicant( 1187): Add randomness: count=257 entropy=252
D/wpa_supplicant( 1187): Add randomness: count=258 entropy=253
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000717124985
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1,
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000717125010
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-77
I/wpa_supplicant( 1187): tsf=0000000717125021
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000717125030
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 717124985, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 717125010, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 717125021, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 717125030, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): acquireWL(41ee1668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41ee1668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=259 entropy=254
D/wpa_supplicant( 1187): Add randomness: count=260 entropy=255
D/wpa_supplicant( 1187): Add randomness: count=261 entropy=256
D/wpa_supplicant( 1187): Add randomness: count=262 entropy=257
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=263 entropy=258
D/wpa_supplicant( 1187): Add randomness: count=264 entropy=259
D/wpa_supplicant( 1187): Add randomness: count=265 entropy=260
D/wpa_supplicant( 1187): Add randomness: count=266 entropy=261
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000734504265
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
,I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000734504291
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000734504302
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000734504311
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 734504265, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 734504291, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 734504302, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 734504311, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42709808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=742396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42709808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=267 entropy=262
D/wpa_supplicant( 1187): Add randomness: count=268 entropy=263
D/wpa_supplicant( 1187): Add randomness: count=269 entropy=264
D/wpa_supplicant( 1187): Add randomness: count=270 entropy=265
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=271 entropy=266
,D/wpa_supplicant( 1187): Add randomness: count=272 entropy=267
D/wpa_supplicant( 1187): Add randomness: count=273 entropy=268
D/wpa_supplicant( 1187): Add randomness: count=274 entropy=269
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
,I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (523) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000751914830
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412,
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000751914855
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000751914866
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000751914875
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 751914830, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 751914855, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 751914866, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 751914875, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=275 entropy=270
D/wpa_supplicant( 1187): Add randomness: count=276 entropy=271
D/wpa_supplicant( 1187): Add randomness: count=277 entropy=272
D/wpa_supplicant( 1187): Add randomness: count=278 entropy=273
D/wpa_supplicant( 1187): Add randomness: count=279 entropy=274
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplican,t( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=280 entropy=275
D/wpa_supplicant( 1187): Add randomness: count=281 entropy=276
D/wpa_supplicant( 1187): Add randomness: count=282 entropy=277
D/wpa_supplicant( 1187): Add randomness: count=283 entropy=278
D/wpa_supplicant( 1187): Add randomness: count=284 entropy=279
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (636) for get BSS: id=0,
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000769314759
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
,I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000769314797
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000769314807
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000769314816
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=8
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000769314786
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS],
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 769314759, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 769314797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 769314807, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 769314816, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 769314786, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4329d198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4329d198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=285 entropy=280
D/wpa_supplicant( 1187): Add randomness: count=286 entropy=281
D/wpa_supplicant( 1187): Add randomness: count=287 entropy=282
D/wpa_supplicant( 1187): Add randomness: count=288 entropy=283
D/wpa_supplicant( 1187): Add randomness: count=289 entropy=284
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplican,t( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=5/32 last_scan_full=0
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): Add randomness: count=290 entropy=285
D/wpa_supplicant( 1187): Add randomness: count=291 entropy=286
D/wpa_supplicant( 1187): Add randomness: count=292 entropy=287
D/wpa_supplicant( 1187): Add randomness: count=293 entropy=288
D/wpa_supplicant( 1187): Add randomness: count=294 entropy=289
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
,W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (636) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000786704982
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000786705019
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000786705029
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000786705038
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=8
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000786705008
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 786704982, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 786705019, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 786705029, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 786705038, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 786705008, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1,
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(440e1960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(440e1960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(43549dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=802396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43549dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=295 entropy=290
D/wpa_supplicant( 1187): Add randomness: count=296 entropy=291
D/wpa_supplicant( 1187): Add randomness: count=297 entropy=292
D/wpa_supplicant( 1187): Add randomness: count=298 entropy=293
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=299 entropy=294
D/wpa_supplicant( 1187): Add randomness: count=300 entropy=295
D/wpa_supplicant( 1187): Add randomness: count=301 entropy=296
D/wpa_supplicant( 1187): Add randomness: count=302 entropy=297
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (636) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000804064675
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
,I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000804064713
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000804064724
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000000786705038
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=8
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000804064701
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 804064675, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 804064713, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 804064724, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 786705038, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 804064701, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=303 entropy=298
D/wpa_supplicant( 1187): Add randomness: count=304 entropy=299
D/wpa_supplicant( 1187): Add randomness: count=305 entropy=300
D/wpa_supplicant( 1187): Add randomness: count=306 entropy=301
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=307 entropy=302
D/wpa_supplicant( 1187): Add randomness: count=308 entropy=303
D/wpa_supplicant( 1187): Add randomness: count=309 entropy=304
D/wpa_supplicant( 1187): Add randomness: count=310 entropy=305
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (489) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000821444867
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000821444904
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000821444914
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=8
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000821444893
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 821444867, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 821444904, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 821444914, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 821444893, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1225): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/PMS     (  907): acquireWL(427ad8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(427ad8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=311 entropy=306
D/wpa_supplicant( 1187): Add randomness: count=312 entropy=307
D/wpa_supplicant( 1187): Add randomness: count=313 entropy=308
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
,I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=314 entropy=309
D/wpa_supplicant( 1187): Add randomness: count=315 entropy=310
,D/wpa_supplicant( 1187): Add randomness: count=316 entropy=311
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
,I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (489) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-46
I/wpa_supplicant( 1187): tsf=0000000838824435
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
,I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000838824461
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000838824472
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=8
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000821444893
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 838824435, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 838824461, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 838824472, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 821444893, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43fca690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43fca690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=317 entropy=312
D/wpa_supplicant( 1187): Add randomness: count=318 entropy=313
D/wpa_supplicant( 1187): Add randomness: count=319 entropy=314
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=320 entropy=315
D/wpa_supplicant( 1187): Add randomness: count=321 entropy=316
D/wpa_supplicant( 1187): Add randomness: count=322 entro,py=317
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000855892557
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412,
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000855892583
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000855892594,
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 855892557, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 855892583, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 855892594, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4283afd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=862396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4283afd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available,
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47,
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=323 entropy=318
D/wpa_supplicant( 1187): Add randomness: count=324 entropy=319
D/wpa_supplicant( 1187): Add randomness: count=325 entropy=320
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
,I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
,D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=326 entropy=321
D/wpa_supplicant( 1187): Add randomness: count=327 entropy=322
D/wpa_supplicant( 1187): Add randomness: count=328 entropy=323
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000873274731
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000873274759
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
,I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000873274770
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 873274731, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 873274759, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 873274770, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(43894088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(43894088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=329 entropy=324
D/wpa_supplicant( 1187): Add randomness: count=330 entropy=325
D/wpa_supplicant( 1187): Add randomness: count=331 entropy=326
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=332 entropy=327
D/wpa_supplicant( 1187): Add randomness: count=333 entropy=328
D/wpa_supplicant( 1187): Add randomness: count=334 entro,py=329
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000890654991
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000890655019
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000890655031
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 890654991, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 890655019, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 890655031, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=335 entropy=330
D/wpa_supplicant( 1187): Add randomness: count=336 entropy=331
D/wpa_supplicant( 1187): Add randomness: count=337 entropy=332
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=338 entropy=333
D/wpa_supplicant( 1187): Add randomness: count=339 entropy=334
D/wpa_supplicant( 1187): Add randomness: count=340 entro,py=335
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000908004760
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000908004785
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000908004796
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 908004760, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 908004785, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 908004796, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426468d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(426468d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(44551258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=922396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44551258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=341 entropy=336
D/wpa_supplicant( 1187): Add randomness: count=342 entropy=337
D/wpa_supplicant( 1187): Add randomness: count=343 entropy=338
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=344 entropy=339
D/wpa_supplicant( 1187): Add randomness: count=345 entropy=340
D/wpa_supplicant( 1187): Add randomness: count=346 entro,py=341
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000925364399
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
,I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000925364425
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000925364436
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList,
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 925364399, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 925364425, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 925364436, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1187): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=347 entropy=342
D/wpa_supplicant( 1187): Add randomness: count=348 entropy=343
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1187): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=349 entropy=344
,D/wpa_supplicant( 1187): Add randomness: count=350 entropy=345
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
,W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000942724031
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1,
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000942724058
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000925364436
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 942724031, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 942724058, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 925364436, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43552280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(43552280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43fbe690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41fa4aa8: PendingIntentRecord{426abbb8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785766, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42b92498: PendingIntentRecord{42a16788 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=951428, Int=0
,D/PMS     (  907): acquireWL(4407af78): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4407af78): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4619 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42695f40: PendingIntentRecord{425b39c8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453394772060, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{425c2228: PendingIntentRecord{425ec5c8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453395492401, Int=900000
,W/ContextImpl( 4552): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): releaseWL(43fbe690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageService( 4552): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4552): MY_DEBUG = false
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4619/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/Process (  907): killProcessQuiet, pid=4349
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4349:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4349
,D/PMS     (  907): acquireWL(425e2058): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1374/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1374/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025201
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025206
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025213
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025217
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026733
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026760
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029678
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032924
,D/PMS     (  907): releaseWL(425e2058): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=351 entropy=346
D/wpa_supplicant( 1187): Add randomness: count=352 entropy=347
D/wpa_supplicant( 1187): Add randomness: count=353 entropy=348
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=354 entropy=349
D/wpa_supplicant( 1187): Add randomness: count=355 entropy=350
D/wpa_supplicant( 1187): Add randomness: count=356 entro,py=351
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000960114787
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000960114813
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000000960114823
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 960114787, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 960114813, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 960114823, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42603950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(42603950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=357 entropy=352
D/wpa_supplicant( 1187): Add randomness: count=358 entropy=353
D/wpa_supplicant( 1187): Add randomness: count=359 entropy=354
D/wpa_supplicant( 1187): Add randomness: count=360 entropy=355
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=361 entropy=356
D/wpa_supplicant( 1187): Add randomness: count=362 entropy=357
D/wpa_supplicant( 1187): Add randomness: count=363 entropy=358
D/wpa_supplicant( 1187): Add randomness: count=364 entropy=359
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (489) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000960114787
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000977192323
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000977192333
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=9
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000977192310
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 960114787, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 977192323, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 977192333, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 977192310, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4282f250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=982396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4282f250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=365 entropy=360
D/wpa_supplicant( 1187): Add randomness: count=366 entropy=361
D/wpa_supplicant( 1187): Add randomness: count=367 entropy=362
D/wpa_supplicant( 1187): Add randomness: count=368 entropy=363
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=369 entropy=364
D/wpa_supplicant( 1187): Add randomness: count=370 entropy=365
D/wpa_supplicant( 1187): Add randomness: count=371 entropy=366
D/wpa_supplicant( 1187): Add randomness: count=372 entropy=367
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000000994555089
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000994555136
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000000994555147
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====,
I/wpa_supplicant( 1187): id=9
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000000994555125
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 994555089, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 994555136, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 994555147, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 994555125, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43576488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/SmartSyncUtils( 4552): isEpsOn(), nState = 0
V/AlarmManager(  907): sending alarm PendingIntent{421244a8: PendingIntentRecord{4327cd70 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453395566663, Int=0
,D/PMS     (  907): acquireWL(440620e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4552 1000 null
,D/PMS     (  907): releaseWL(43576488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4552): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4552): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4552): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4552): SettingOnTime = 1453442400000, randomSettingOnTime = 1453441636000
,D/SmartSyncScreenOnOffTimeReceiver( 4552): SettingOffTime = 1453428000000, randomSettingOffTime = 1453432746000
,D/SmartSyncScreenOnOffTimeReceiver( 4552): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4552): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4552): bNightModeTurnOffOnce = false
,D/PMS     (  907): releaseWL(440620e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(428e7b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(428e7b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=373 entropy=368
D/wpa_supplicant( 1187): Add randomness: count=374 entropy=369
D/wpa_supplicant( 1187): Add randomness: count=375 entropy=370
D/wpa_supplicant( 1187): Add randomness: count=376 entropy=371
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplican,t( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=377 entropy=372
D/wpa_supplicant( 1187): Add randomness: count=378 entropy=373
D/wpa_supplicant( 1187): Add randomness: count=379 entropy=374
D/wpa_supplicant( 1187): Add randomness: count=380 entropy=375
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (489) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001011942282
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001011942319
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001011942330
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=9
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001011942308
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1011942282, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1011942319, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1011942330, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1011942308, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=381 entropy=376
D/wpa_supplicant( 1187): Add randomness: count=382 entropy=377
D/wpa_supplicant( 1187): Add randomness: count=383 entropy=378
D/wpa_supplicant( 1187): Add randomness: count=384 entropy=379
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=385 entropy=380
D/wpa_supplicant( 1187): Add randomness: count=386 entropy=381
D/wpa_supplicant( 1187): Add randomness: count=387 entropy=382
D/wpa_supplicant( 1187): Add randomness: count=388 entropy=383
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (637) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001029322552
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001029322579
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001029322591
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=9
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
,I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001011942308
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=10
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000001029322599
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1029322552, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1029322579, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1029322591, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1011942308, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 1029322599, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(435589e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(435589e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4356d450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1042396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.759MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(4356d450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=389 entropy=384
D/wpa_supplicant( 1187): Add randomness: count=390 entropy=385
D/wpa_supplicant( 1187): Add randomness: count=391 entropy=386
D/wpa_supplicant( 1187): Add randomness: count=392 entropy=387
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=393 entropy=388
D/wpa_supplicant( 1187): Add randomness: count=394 entropy=389
D/wpa_supplicant( 1187): Add randomness: count=395 entropy=390
D/wpa_supplicant( 1187): Add randomness: count=396 entropy=391
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (524) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001046694786
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001046694812
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
,I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001046694824
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=10
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000001046694832
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1046694786, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1046694812, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1046694824, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 1046694832, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=397 entropy=392
D/wpa_supplicant( 1187): Add randomness: count=398 entropy=393
D/wpa_supplicant( 1187): Add randomness: count=399 entropy=394
D/wpa_supplicant( 1187): Add randomness: count=400 entropy=395
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1187): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=401 entropy=396
D/wpa_supplicant( 1187): Add randomness: count=402 entropy=397
D/wpa_supplicant( 1187): Add randomness: count=403 entropy=398
D/wpa_supplicant( 1187): Add randomness: count=404 entropy=399
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (524) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
,I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001064044799
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001064044825
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001064044836
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=10
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000001064044845
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1064044799, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1064044825, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1064044836, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 1064044845, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43a4fae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43a4fae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=405 entropy=400
D/wpa_supplicant( 1187): Add randomness: count=406 entropy=401
D/wpa_supplicant( 1187): Add randomness: count=407 entropy=402
D/wpa_supplicant( 1187): Add randomness: count=408 entropy=403
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=409 entropy=404
D/wpa_supplicant( 1187): Add randomness: count=410 entropy=405
D/wpa_supplicant( 1187): Add randomness: count=411 entropy=406
D/wpa_supplicant( 1187): Add randomness: count=412 entropy=407
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (638) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001081464980
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
,I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001081465018
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001081465028
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=10
I/wpa_supplicant( 1187): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1187): freq=2437
I/wpa_supplicant( 1187): level=-91
I/wpa_supplicant( 1187): tsf=0000001064044845
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=UPC4688432
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001081465006
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1081464980, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1081465018, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1081465028, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 1064044845, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1081465006, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43f62728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43f62728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=413 entropy=408
D/wpa_supplicant( 1187): Add randomness: count=414 entropy=409
D/wpa_supplicant( 1187): Add randomness: count=415 entropy=410
D/wpa_supplicant( 1187): Add randomness: count=416 entropy=411
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=417 entropy=412
D/wpa_supplicant( 1187): Add randomness: count=418 entropy=413
D/wpa_supplicant( 1187): Add randomness: count=419 entropy=414
D/wpa_supplicant( 1187): Add randomness: count=420 entropy=415
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (490) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001098854685
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001098854722
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001098854734
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001098854711
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1098854685, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1098854722, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1098854734, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1098854711, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43552668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1102396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43552668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=421 entropy=416
D/wpa_supplicant( 1187): Add randomness: count=422 entropy=417
D/wpa_supplicant( 1187): Add randomness: count=423 entropy=418
D/wpa_supplicant( 1187): Add randomness: count=424 entropy=419
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=425 entropy=420
D/wpa_supplicant( 1187): Add randomness: count=426 entropy=421
D/wpa_supplicant( 1187): Add randomness: count=427 entropy=422
D/wpa_supplicant( 1187): Add randomness: count=428 entropy=423
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (490) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47,
I/wpa_supplicant( 1187): tsf=0000001116265369
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001116265406
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78,
I/wpa_supplicant( 1187): tsf=0000001116265416
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001116265395
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1116265369, distance: ?(cm), distanceSd: ?(cm),
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1116265406, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1116265416, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1116265395, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==,
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4395d4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4395d4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=429 entropy=424
D/wpa_supplicant( 1187): Add randomness: count=430 entropy=425
D/wpa_supplicant( 1187): Add randomness: count=431 entropy=426
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
,D/wpa_supplicant( 1187): Add randomness: count=432 entropy=427
D/wpa_supplicant( 1187): Add randomness: count=433 entropy=428
D/wpa_supplicant( 1187): Add randomness: count=434 entropy=429
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (490) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47,
I/wpa_supplicant( 1187): tsf=0000001133644946
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001133644973
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000001133644983
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001116265395
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1133644946, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1133644973, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 1133644983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1116265395, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=435 entropy=430
D/wpa_supplicant( 1187): Add randomness: count=436 entropy=431
D/wpa_supplicant( 1187): Add randomness: count=437 entropy=432
D/wpa_supplicant( 1187): Add randomness: count=438 entropy=433
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=439 entropy=434
D/wpa_supplicant( 1187): Add randomness: count=440 entropy=435
D/wpa_supplicant( 1187): Add randomness: count=441 entropy=436
D/wpa_supplicant( 1187): Add randomness: count=442 entropy=437
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (490) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001151025012
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001151025038
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-77
I/wpa_supplicant( 1187): tsf=0000001151025060
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-56
I/wpa_supplicant( 1187): tsf=0000001151025049
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1151025012, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1151025038, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1151025060, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1151025049, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42856b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42856b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4302cd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1162396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4302cd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=443 entropy=438
D/wpa_supplicant( 1187): Add randomness: count=444 entropy=439
D/wpa_supplicant( 1187): Add randomness: count=445 entropy=440
D/wpa_supplicant( 1187): Add randomness: count=446 entropy=441
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=447 entropy=442
D/wpa_supplicant( 1187): Add randomness: count=448 entropy=443
D/wpa_supplicant( 1187): Add randomness: count=449 entropy=444
D/wpa_supplicant( 1187): Add randomness: count=450 entropy=445
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (490) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001168414834
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001168414860
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001168414880
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-56
I/wpa_supplicant( 1187): tsf=0000001168414870
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1168414834, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1168414860, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1168414880, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1168414870, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=451 entropy=446
D/wpa_supplicant( 1187): Add randomness: count=452 entropy=447
D/wpa_supplicant( 1187): Add randomness: count=453 entropy=448
D/wpa_supplicant( 1187): Add randomness: count=454 entropy=449
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=455 entropy=450
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): Add randomness: count=456 entropy=451
D/wpa_supplicant( 1187): Add randomness: count=457 entropy=452
D/wpa_supplicant( 1187): Add randomness: count=458 entropy=453
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (490) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001185794893
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
,I/wpa_supplicant( 1187): tsf=0000001185794920
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001185794940
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-56
I/wpa_supplicant( 1187): tsf=0000001185794930
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1185794893, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1185794920, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1185794940, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1185794930, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(433160c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/PowerUI ( 1119): closing low battery warning: level=100
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(433160c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=459 entropy=454
D/wpa_supplicant( 1187): Add randomness: count=460 entropy=455
D/wpa_supplicant( 1187): Add randomness: count=461 entropy=456
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=462 entropy=457
D/wpa_supplicant( 1187): Add randomness: count=463 entropy=458
D/wpa_supplicant( 1187): Add randomness: count=464 entro,py=459
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (490) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001203214866
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001203214892
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001203214902
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-56
I/wpa_supplicant( 1187): tsf=0000001185794930
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1203214866, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1203214892, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1203214902, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1185794930, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43868318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43868318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=465 entropy=460
D/wpa_supplicant( 1187): Add randomness: count=466 entropy=461
D/wpa_supplicant( 1187): Add randomness: count=467 entropy=462
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=468 entropy=463
D/wpa_supplicant( 1187): Add randomness: count=469 entropy=464
D/wpa_supplicant( 1187): Add randomness: count=470 entro,py=465
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001220604762
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001220604788
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001220604799
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1220604762, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1220604788, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1220604799, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4301ab80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1222396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4301ab80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=471 entropy=466
D/wpa_supplicant( 1187): Add randomness: count=472 entropy=467
D/wpa_supplicant( 1187): Add randomness: count=473 entropy=468
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=474 entropy=469
D/wpa_supplicant( 1187): Add randomness: count=475 entropy=470
D/wpa_supplicant( 1187): Add randomness: count=476 entro,py=471
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0,
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001238015466
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001238015492
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-77
,I/wpa_supplicant( 1187): tsf=0000001238015503
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1238015466, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1238015492, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1238015503, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4311db40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4311db40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
,D/HtcPowerSaver(  907): Checking...
D/PowerUI ( 1119): closing low battery warning: level=100
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=477 entropy=472
D/wpa_supplicant( 1187): Add randomness: count=478 entropy=473
D/wpa_supplicant( 1187): Add randomness: count=479 entropy=474
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=480 entropy=475
D/wpa_supplicant( 1187): Add randomness: count=481 entropy=476
D/wpa_supplicant( 1187): Add randomness: count=482 entro,py=477
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001255395141
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1,
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001255395168
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
,I/wpa_supplicant( 1187): level=-77
I/wpa_supplicant( 1187): tsf=0000001255395179
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1255395141, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1255395168, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1255395179, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(43004ce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43004ce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=483 entropy=478
D/wpa_supplicant( 1187): Add randomness: count=484 entropy=479
D/wpa_supplicant( 1187): Add randomness: count=485 entropy=480
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=486 entropy=481
D/wpa_supplicant( 1187): Add randomness: count=487 entropy=482
D/wpa_supplicant( 1187): Add randomness: count=488 entro,py=483
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (376) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001272804241
,I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001272804268
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-77
I/wpa_supplicant( 1187): tsf=0000001272804279
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1272804241, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1272804268, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1272804279, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(433a4b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420c3f38: PendingIntentRecord{420a7500 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1282396, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(433a4b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=489 entropy=484
D/wpa_supplicant( 1187): Add randomness: count=490 entropy=485
D/wpa_supplicant( 1187): Add randomness: count=491 entropy=486
D/wpa_supplicant( 1187): Add randomness: count=492 entropy=487
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=493 entropy=488
D/wpa_supplicant( 1187): Add randomness: count=494 entropy=489
D/wpa_supplicant( 1187): Add randomness: count=495 entropy=490
D/wpa_supplicant( 1187): Add randomness: count=496 entropy=491
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (490) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001290194329
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001290194367
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-78
I/wpa_supplicant( 1187): tsf=0000001290194377
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=12
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001290194355
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1290194329, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1290194367, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1290194377, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1290194355, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults,
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=497 entropy=492
D/wpa_supplicant( 1187): Add randomness: count=498 entropy=493
D/wpa_supplicant( 1187): Add randomness: count=499 entropy=494
D/wpa_supplicant( 1187): Add randomness: count=500 entropy=495
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 9
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1187): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=501 entropy=496
D/wpa_supplicant( 1187): Add randomness: count=502 entropy=497
D/wpa_supplicant( 1187): Add randomness: count=503 entropy=498
D/wpa_supplicant( 1187): Add randomness: count=504 entropy=499
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (490) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-47
I/wpa_supplicant( 1187): tsf=0000001290194329
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001307584939
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000001307584948
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=12
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-55
I/wpa_supplicant( 1187): tsf=0000001307584928
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1290194329, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1307584939, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 1307584948, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1307584928, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43cb74e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43cb74e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4646): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4646): ====startRecUseTime====
D/htc.customization.log.level( 4646):  is 
W/CustomizationLogLevel( 4646): Level value is invalid, use default level 2
D/CustomizationManager( 4646):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4646): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4646): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4646): Parsing tag category name = system
I/CustomizationCIDLoader( 4646): Parsing tag category name = application
I/CustomizationCIDLoader( 4646): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4646): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4646): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4646): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4646): Parsing tag category name = Settings
D/CustomizationManager( 4646):  Read CID file spent 0.113 (s)
D/CustomizationManager( 4646):  All configurations done spent 0.114 (s)
W/HtcNativeFlag( 4646): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4646): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4646): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4646): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4646, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=4497
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 4497:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
W/asset   (  907): Copying FileAsset 0x66d89498 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  907): Skipping PackageSetting{423f9cd8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(43f65c98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43f65c98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1333): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1333): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/IcingCorporaProvider( 2894): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4660 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1345): Unsupported attribute readOnly
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  907): acquireWL(423331e8): PARTIAL_WAKE_LOCK  Icing 0x1 2194 10029 WorkSource{10029 com.google.android.gms}
E/SQLiteLog( 2894): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2894): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x643be7d0
E/IcingCorporaProvider( 2894): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2894): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2894): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2894): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2894): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2894): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2894): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2894): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2894): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2894): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2894): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2894): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2894): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2894): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2894): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2894): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2894): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2894): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2894): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2894): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2894): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2894): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2894): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2894): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2894): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2894): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2894): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2894): 	... 15 more
W/IcingCorporaProvider( 2894): notifyTableChanged failed.
W/IcingCorporaProvider( 2894): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2894): UpdateCorporaTask done [took 273 ms] updated apps [took 273 ms] 
D/PMS     (  907): releaseWL(423331e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4660): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4660): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4660): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4660): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4660): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4660): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4660): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4660): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4660): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4660): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4660): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4660): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4660): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4660): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4660): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4660): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4660): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4660): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4660): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4660): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4660): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4660): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4660): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4660): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4660): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4660): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4660): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4660): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4660): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4660): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4660): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4660): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4660): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4660): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4660): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4660): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4660): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4660): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4660): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4660): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4660): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4660): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4660): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4660): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4660): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4660): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4660): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4660): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4660): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4660): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4660): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4660): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4660): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4660): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4660): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4660): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4660): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4660): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4660): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4660): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4660): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4660): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4660): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4660): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4660): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4660): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4660): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4660): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4660): threadid=11: thread exiting with uncaught exception (group=0x418e2e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4660): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4660): Process: com.google.android.apps.docs, PID: 4660
E/AndroidRuntime( 4660): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4660): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4660): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4660): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4660): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4660): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4660): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4660): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4660): 	at aho.run(AbstractDatabaseInstance.java:455)
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
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4679 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4660): killProcess, pid=4660
D/Process ( 4660): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Recipient 4660
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4660) has died.
W/ContextImpl( 4679): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4692 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4679): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4679): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4679): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4679): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4679): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4679): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4679): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4679): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4679): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4679): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4679): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4679): threadid=10: thread exiting with uncaught exception (group=0x418e2e30)
E/AndroidRuntime( 4679): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4679): Process: com.android.keychain, PID: 4679
E/AndroidRuntime( 4679): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4679): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4679): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4679): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4679): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4679): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4679): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4679): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4679): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4679): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4692): getInstance(Context context)
D/AppTag  ( 4692): getInstance(Context context)
D/AppTag  ( 4692): onCreate()
D/Process ( 4679): killProcess, pid=4679
D/Process ( 4679): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453395872914.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41da7cb0 +
I/Prism.WidgetManager( 1271): onLoadItems() +
I/ActivityManager(  907): Recipient 4679
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4679) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  907): acquireWL(43546428): PARTIAL_WAKE_LOCK  AsyncService 0x1 3700 10160 null
W/dalvikvm( 4145): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PMS     (  907): releaseWL(43546428): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PackageBroadcastService( 2194): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2194): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2194): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2194): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2194): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2194): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 2194): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2194): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e881440
E/SQLiteLog( 1374): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1374): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fd6710
W/dalvikvm( 2194): threadid=40: thread exiting with uncaught exception (group=0x418e2e30)
W/dalvikvm( 1374): threadid=1: thread exiting with uncaught exception (group=0x418e2e30)
I/LocationSettingsChecker( 2194): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2194): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2194): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65c71850
I/ActivityManager(  907): Delay finish: com.google.android.gms/.gcm.GcmPackageTracker$GcmPackageChangeReceiver
E/DriveAsyncService( 2194): disk I/O error (code 3850)
E/DriveAsyncService( 2194): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2194): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2194): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2194): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2194): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2194): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2194): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2194): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2194): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2194): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2194): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2194): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2194): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2194): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 1374): FATAL EXCEPTION: main
E/AndroidRuntime( 1374): Process: com.google.process.gapps, PID: 1374
E/AndroidRuntime( 1374): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1374): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1374): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1374): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1374): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1374): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1374): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1374): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1374): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1374): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1374): 	... 10 more
E/AndroidRuntime( 2194): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2194): Process: com.google.android.gms, PID: 2194
E/AndroidRuntime( 2194): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2194): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2194): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2194): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2194): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2194): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2194): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2194): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2194): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2194): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2194): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1374): killProcess, pid=1374
D/Process ( 1374): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
D/Process ( 2194): killProcess, pid=2194
D/Process ( 2194): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/PackageManager(  907): Unable to load service info ResolveInfo{4289bb60 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  907): Recipient 2194
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms (pid 2194) has died.
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 1374
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
W/BroadcastQueue(  907): Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.gcm.nts.SchedulerReceiver}
W/BroadcastQueue(  907): android.os.DeadObjectException
W/BroadcastQueue(  907): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  907): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue.backgroundServicesFinishedLocked(BroadcastQueue.java:442)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService.backgroundServicesFinishedLocked(ActivityManagerService.java:15042)
W/BroadcastQueue(  907): 	at com.android.server.am.ActiveServices$ServiceMap.rescheduleDelayedStarts(ActiveServices.java:237)
W/BroadcastQueue(  907): 	at com.android.server.am.ActiveServices$ServiceMap.ensureNotStartingBackground(ActiveServices.java:191)
W/BroadcastQueue(  907): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1711)
W/BroadcastQueue(  907): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2185)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:13536)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:3943)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4128)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
W/BroadcastQueue(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/BroadcastQueue(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms

```
