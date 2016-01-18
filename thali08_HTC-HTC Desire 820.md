#### Test 563583788793eb6_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1114): WifiActivity: 0
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
--------- beginning of /dev/log/main
E/cutils-trace( 4452): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4452): ====startRecUseTime====
D/htc.customization.log.level( 4452):  is 
W/CustomizationLogLevel( 4452): Level value is invalid, use default level 2
D/CustomizationManager( 4452):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4452): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4452): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4452): Parsing tag category name = system
I/CustomizationCIDLoader( 4452): Parsing tag category name = application
I/CustomizationCIDLoader( 4452): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4452): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4452): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4452): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4452): Parsing tag category name = Settings
D/CustomizationManager( 4452):  Read CID file spent 0.098 (s)
D/CustomizationManager( 4452):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4452): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4452): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4452): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4452): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4452
D/PMS     (  904): acquireHCC(441f1ce0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(441f0290): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x64294e10 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1138520712
D/PMS     (  904): acquireWL(441ed3d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42014010
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4463 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4463): Copying FileAsset 0x5c887428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4463): Binding Chromium to main looper Looper (main, tid 1) {41b47160}
I/LibraryLoader( 4463): Expected native library version number "",actual native library version number ""
I/chromium( 4463): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4463): Initializing chromium process, renderers=0
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d46c90:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4463): 1102433176: getState(). Returning 12
D/PMS     (  904): acquireWL(441e5eb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): acquireWL(441e4e08): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(441e5eb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4463): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4463): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4463): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4463): Local Branch: 
I/Adreno-EGL( 4463): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4463): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4463):                  aa63bbd948f41d15fc72f585e
W/chromium( 4463): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4463): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4463): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4463): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4463): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4463): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4463): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4463): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4463): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4463): CordovaWebView is running on device made by: HTC
,W/AwContents( 4463): nativeOnDraw failed; clearing to background color.
,D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  904): acquireWL(441dd3d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
I/InputMethodManagerService(  904): Disable input method client, pid=1271
V/AlarmManager(  904): sending alarm PendingIntent{425c9728: PendingIntentRecord{425925d0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=106827, Int=0
I/InputMethodManagerService(  904): Enable input method client, pid=4463
W/ResourceType( 4463): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4463): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b8e248, mServedView=org.apache.cordova.engine.SystemWebView{41b53eb0 VFEDH.C. .F....I. 0,0-720,1134 #64}
D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=80 rxSum=63} preTxRxSum={txSum=80 rxSum=63}
D/WifiDataStallTracker(  904): updateDataStallInfo: NONE
D/WifiDataStallTracker(  904): onDataStallAlarm: tag=20075 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20076 delay=15s
,I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +298ms
,W/AwContents( 4463): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  904): releaseWL(441dd3d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): releaseWL(441ed3d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4463): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4463): JniHelper::setJavaVM(0x4161c048), pthread_self() = 1663376256
,I/chromium( 4463): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:110, mTXpacketCount:110, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 12.040MB for 63974-byte allocation
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 12.092MB for 95956-byte allocation
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 12.153MB for 143930-byte allocation
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 12.268MB for 215890-byte allocation
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 12.445MB for 323830-byte allocation
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 13.120MB for 728606-byte allocation
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 13.719MB for 1092904-byte allocation
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 14.634MB for 1639352-byte allocation
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 15.883MB for 2459024-byte allocation
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
,D/PMS     (  904): releaseHCC(441f1ce0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(441f0290): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 18.069MB for 3688532-byte allocation
,W/jxcore-log( 4463): Initializing JXcore engine
,W/jxcore-log( 4463): JXcore engine is ready
,I/SensorManager(  904): mEventCount = 900
,W/jxcore-log( 4463): Starting JXcore engine
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 4463): Platform android
W/jxcore-log( 4463): 
,W/jxcore-log( 4463): Process ARCH arm
W/jxcore-log( 4463): 
,D/PMS     (  904): releaseWL(441e4e08): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4463): JXcore Cordova bridge is ready!
I/jxcore-log( 4463): 
,W/jxcore-log( 4463): JXcore engine is started
,E/jxcore  ( 4463): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 4463): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4463): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  904): acquireWL(441d9998): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
W/PluginManager( 4463): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 38ms. Plugin should use CordovaInterface.getThreadPool().
,I/FeedHostManager( 1271): [onResume]
,I/FeedProviderManager( 1271): onResume
I/SocialFeedProvider( 1271): +onResume
I/SocialFeedProvider( 1271): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1271): -onResume
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (1271/10075)
,I/InputMethodManagerService(  904): Disable input method client, pid=4463
,I/InputMethodManagerService(  904): Enable input method client, pid=1271
W/IInputConnectionWrapper( 4463): reportFullscreenMode on inactive InputConnection
,D/PMS     (  904): releaseWL(441d9998): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  904): killProcessQuiet, pid=3906
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  904): Killing 3906:com.google.android.music:main/u0a154 (adj 15): empty #17
,E/libEGL  ( 4463): call to OpenGL ES API with no current context (logged once per thread)
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  904): Client com.google.android.music (pid 3906): Died!
,I/ActivityManager(  904): Recipient 3906
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421507d0
,W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  904): pid=904, uid=1000
W/PMS     (  904): mWirelessDisplayManager is null
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  904): setLight #0: color=#0
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421507d0, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c8b40
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@420f1ac8
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 380ms
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@444aade8)
,D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
D/PMS     (  904): OOBE c monitor 11
D/PMN     (  904): wakingUp
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=1271
D/PMS     (  904): acquireWL(43cfe618): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
D/PMS     (  904): releaseWL(43cfe618): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  904): No lock screen! windowToken=null
D/PMN     (  904): onScreenOn
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
D/PMS     (  904): acquireWL(43cf2ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/MtpService( 2457): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2457): [MTP][onReceive]-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1255): applyRouting - 0
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(43cf2ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1255): applyRouting -2
,D/AutoSetting( 1396): receiver - intent: android.intent.action.USER_PRESENT
,D/PMS     (  904): acquireWL(43cdb290): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  904): releaseWL(43cdb290): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/AutoSetting( 1396): service - onCreate()
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/TetherSettings( 4182): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4182): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4182): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4182): Cust_ConnectToPC   : spcsc>false
D/        ( 4182): Cust_ConnectToPC   : IPT>true
,D/        ( 4182): Cust_ConnectToPC   : Singel_USB>false
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20077 delay=15s
,D/AutoSetting( 1396): service - AddressCache: using context: com.htc.Weather
,W/Settings( 4182): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
E/SmartNS_Utility( 4182): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4182): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4182): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/LocationManagerService(  904): request 42575940 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/PSReceiver( 4182): onReceive:android.intent.action.USER_PRESENT
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): SET_SCREEN_ON:On
I/wpa_supplicant( 1174): htc_wext_set_keepalive +
I/wpa_supplicant( 1174): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1174): getPrivFuncNum +	
I/wpa_supplicant( 1174): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1174): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1174): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1114): WifiActivity: 0
,I/SmartNS_PSService( 4182): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4182): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4182):  defaultType:0
,V/SRS_Proc(  370): ParamSet string: screen_state=on
W/ContextImpl( 4182): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
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
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/ClockThread( 1114): stop update clock
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/NetworkPolicy(  904): updateScreenOn: false
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4523 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1830): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1830): onScreenOn: 1453134248175
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1830): onScreenOn: 1453134248175
D/PMS     (  904): acquireWL(438dc6d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
D/PMS     (  904): releaseWL(438dc6d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ContextImpl( 4523): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c8b40
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c8b40, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@420f1ac8
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
D/PMS     (  904): acquireWL(438ca8f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
,I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42014010
I/SocialFeedProvider( 1271): +onPause
,I/SocialFeedProvider( 1271): -onPause
,D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20077 mDataStallAlarmIntent=PendingIntent{43ca5748: PendingIntentRecord{425925d0 android broadcastIntent}}
,D/SmartSyncUtils( 4523): isEpsOn(), nState = 0
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
D/PMS     (  904): acquireWL(4389a4e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4523 1000 null
,D/PMS     (  904): acquireWL(43852540): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  904): releaseWL(438ca8f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): SET_SCREEN_ON:Off
I/wpa_supplicant( 1174): htc_wext_set_keepalive +
I/wpa_supplicant( 1174): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1174): getPrivFuncNum +	
I/wpa_supplicant( 1174): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1174): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1174): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1174): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1174): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  904):    returned true
D/PMS     (  904): releaseWL(43852540): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  904): releaseWL(4389a4e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4523): getMobilePolicyEnabled, result = true
D/NetworkPolicy(  904): updateScreenOn: false
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4523): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4523): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4523): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4523): isEpsOn(), nState = 0
D/WifiService(  904): New client listening to asynchronous messages
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@420f1ac8
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@420f1ac8, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@420f1ac8, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@420f1ac8
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42599d78 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42599d78 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
D/ContactMessageStore( 1242): Background delete complete
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1830): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1830): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1830): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1830): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1830): onScreenOff
D/PMS     (  904): acquireWL(42a43970): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
D/PMS     (  904): releaseWL(42a43970): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1396): service - mHandler: cancel location update
D/AutoSetting( 1396): service -           changes count: 0
,D/AutoSetting( 1505): service - handleMessage() stop self
,D/AutoSetting( 1505): service - onDestroy() END
,D/AutoSetting( 1505): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=3888
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3888:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3888
,D/Process (  904): killProcessQuiet, pid=3928
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3928:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3928
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{43045410 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  904): acquireWL(433f84d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(433f84d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4333ae40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{41ce42b0: PendingIntentRecord{424e6850 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=133466, Int=0
,D/PMS     (  904): acquireWL(43337080): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): releaseWL(4333ae40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(433187e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  904): acquireWL(42e90210): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 904 1000 WorkSource{10106}
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  904): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4547 uid=10106 gids={50106, 3003, 5012}
,D/PMS     (  904): releaseWL(43337080): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(433187e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4547): LocationClient connecting
,D/PMS     (  904): acquireWL(426d7bb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
,D/PMS     (  904): releaseWL(426d7bb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4547): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4547): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4547): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4547): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 4547): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4547): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ProviderInstaller( 4547): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43b264b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,I/NewsWeather( 4547): onConnected null
I/NewsWeather( 4547): Last usage 0, idle 1453134270s, sync interval 2592000s
,I/NewsWeather( 4547): setPeriodicSync in seconds 2592000
D/PMS     (  904): releaseWL(43b264b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  904): acquireWL(43ad3210): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
W/GCoreFlp( 1420): No location to return for getLastLocation()
,I/NewsWeather( 4547): LocationClient onConnected: location null
D/PMS     (  904): acquireWL(43ad0480): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
,D/PMS     (  904): releaseWL(43ad3210): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4547): Skip sync for lookup editions
,I/NewsWeather( 4547): syncNewsAppData traffic type BACKGROUND_POLL
D/PMS     (  904): releaseWL(43ad0480): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4547): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4547): Unrecoverable authentication exception
E/NewsWeather( 4547): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ca1318 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 16 6 12
,D/libc    ( 4547): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4547): [NET] getaddrinfo-,err=8
D/libc    ( 4547): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4547): [NET] getaddrinfo-, 1
D/libc    ( 4547): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =688e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4547): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4547): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4547): [NET] getaddrinfo-,err=8
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(43a13220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  904): releaseWL(43a13220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4547): Failed to syncNewsAppData
,E/NewsWeather( 4547): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43a0f528): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/SyncManager(  904): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 68617, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  904): releaseWL(42e90210): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  904): killProcessQuiet, pid=4266
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4266:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1420/10028)
D/PMS     (  904): releaseWL(43a0f528): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(439c8e68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  904): releaseWL(439c8e68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  904): Recipient 4266
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  904): Client connection lost with reason: 4
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,I/GAV4    ( 4547): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  904): acquireWL(43970398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41d8f5e0: PendingIntentRecord{4251e6c0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141549, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(43969810): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(43970398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ceff +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  904): acquireWL(438dc740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{42725f98: PendingIntentRecord{4258f650 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142209, Int=0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  904): releaseWL(438dc740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  904): acquireWL(438cd2b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  904): releaseWL(438cd2b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1396): service - handleMessage() stop self
,D/AutoSetting( 1396): service - onDestroy() END
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4292
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4292:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4292
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): releaseWL(43969810): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1227/10028)
,D/PMS     (  904): acquireWL(4387ff28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41ce42b0: PendingIntentRecord{424e6850 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=163554, Int=0
,D/PMS     (  904): acquireWL(4387e3e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(4387a0f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(4387ff28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): releaseWL(4387e3e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(4387a0f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  904): acquireWL(43847598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=163862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43847598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43830020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43830020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43828320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{429cf4c0: PendingIntentRecord{42c5bfc8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=176426, Int=0
,D/PMS     (  904): releaseWL(43828320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(43810d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43810d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(437fed70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=223863, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(437fed70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(437e6e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437e6e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(437d1108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41ce42b0: PendingIntentRecord{424e6850 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=264316, Int=0
,D/PMS     (  904): acquireWL(4311def0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/PMS     (  904): releaseWL(437d1108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(437c57f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=6 [45][3][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0,
,D/PMS     (  904): acquireWL(43781858): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 904 1000 WorkSource{10106}
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): releaseWL(4311def0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(437c57f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43760f60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43760f60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4547): Last usage 0, idle 1453134400s, sync interval 2592000s
,I/NewsWeather( 4547): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4547): Skip sync for lookup editions
,I/NewsWeather( 4547): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4547): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4547): Unrecoverable authentication exception
E/NewsWeather( 4547): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ef1138 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 9 4 12
,D/PMS     (  904): acquireWL(4365a9e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  904): releaseWL(4365a9e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4547): Failed to syncNewsAppData
,E/NewsWeather( 4547): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43653bf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/SyncManager(  904): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 134616, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  904): releaseWL(43781858): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): releaseWL(43653bf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1420/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(43609b48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/PMS     (  904): releaseWL(43609b48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(4359b870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=283863, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4359b870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43575558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41ce42b0: PendingIntentRecord{424e6850 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=294373, Int=0
,D/PMS     (  904): acquireWL(43572f08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43575558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(4356b308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43572f08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(4356b308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(43529750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(43529750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(434da250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=343862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(434da250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41f34728 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4124): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4124): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4124): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4124): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4124): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4124): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4124): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4124): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 12 4 12
,D/libc    ( 4124): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4124): [NET] getaddrinfo-,err=8
D/libc    ( 4124): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4124): [NET] getaddrinfo-, 1
,D/libc    ( 4124): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9908 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4124): [NET] getaddrinfo_proxy-, success
I/global  ( 4124): call createSocket() return a new socket.
D/libc    ( 4124): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4124): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4124): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4124): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(43884f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43884f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(4384d160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=403862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4384d160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43823588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43823588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(437f9890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437f9890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4371d408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=463862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4371d408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(436df078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(436df078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(43028a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43028a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43022f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=523862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43022f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42fcadc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41ce42b0: PendingIntentRecord{424e6850 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=524269, Int=0
,D/PMS     (  904): acquireWL(42fcad78): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/PMS     (  904): releaseWL(42fcadc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(42fae4b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=4 [48][2][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(42eac258): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 904 1000 WorkSource{10106}
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(42ea6cd8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 904 1000 WorkSource{10160}
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/PMS     (  904): releaseWL(42fcad78): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  904): releaseWL(42fae4b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(42ea18a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(42ea18a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(42e81820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(42e81820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
I/NewsWeather( 4547): Last usage 0, idle 1453134660s, sync interval 2592000s
,I/NewsWeather( 4547): setPeriodicSync in seconds 2592000
D/PMS     (  904): acquireWL(4268e558): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(4268e558): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4547): Skip sync for lookup editions
,I/NewsWeather( 4547): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4547): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(420dede8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(42ea6cd8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
D/PMS     (  904): releaseWL(420dede8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4547): Unrecoverable authentication exception
E/NewsWeather( 4547): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41d03228 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4547): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4547): [NET] getaddrinfo-,err=8
D/libc    ( 4547): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4547): [NET] getaddrinfo-, 1
D/libc    ( 4547): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4d98 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
I/RemoteViews.Performance( 1114): com.google.android.gms 1 11 4 12
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4547): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4547): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4547): [NET] getaddrinfo-,err=8
,E/NewsWeather( 4547): Failed to syncNewsAppData
,E/NewsWeather( 4547): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  904): acquireWL(424d16b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  904): releaseWL(424d16b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(42213d50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/SyncManager(  904): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 264870, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  904): releaseWL(42eac258): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  904): releaseWL(42213d50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1420/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(41b44a00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(41b44a00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(41ccf028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(41ccf028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43e83030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41ce42b0: PendingIntentRecord{424e6850 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=554372, Int=0
,D/PMS     (  904): acquireWL(43c8aa50): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
D/PMS     (  904): releaseWL(43e83030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(42e8a838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43c8aa50): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(42e8a838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  904): acquireWL(424d7df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=583862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(424d7df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42f5e800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42f5e800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1242): sku_id=99
,D/ContactMessageStore( 1242): start background delete task...
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/PMS     (  904): acquireWL(425917b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=643862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425917b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42177f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(42177f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43035370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43035370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4593 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  904): acquireWL(4245caa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10047}
,V/AlarmManager(  904): sending alarm PendingIntent{424fd460: PendingIntentRecord{422a7bd0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453134356673, Int=10800000
,V/AlarmManager(  904): sending alarm PendingIntent{437cf2e0: PendingIntentRecord{42655630 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453134610781, Int=1800000
,V/AlarmManager(  904): sending alarm PendingIntent{4372c748: PendingIntentRecord{41d9d8f8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453134812074, Int=0
,D/PMS     (  904): acquireWL(4305b5f8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1227 10028 null
,D/PMS     (  904): releaseWL(4245caa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  904): acquireWL(42591690): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1227 10028 null
,D/PMS     (  904): releaseWL(4305b5f8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 1227): Aggregate from 1453134192159 (log), 1453132810731 (data)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4593/10047)
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  904): releaseWL(42591690): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4124): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4124): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4124): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4124): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4124): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/Process (  904): killProcessQuiet, pid=4306
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4306:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4306
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(4301c380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{43020000: PendingIntentRecord{433d0100 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453134827257, Int=0
,D/PMS     (  904): releaseWL(4301c380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4124): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  904): acquireWL(42640438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=703862, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42640438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4418c488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4418c488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42b29e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b29e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  904): killProcessQuiet, pid=4331
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4331:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4331
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(43103b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=763864, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43103b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43d42b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41df4800: PendingIntentRecord{4247e770 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786141, Int=0
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/PMS     (  904): releaseWL(43d42b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PMS     (  904): acquireWL(42b30280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(42b30280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43e8ad40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=823862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43e8ad40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4367d750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(4367d750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4269bd58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=883862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4269bd58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43d627e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43d627e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/ContextImpl( 4523): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,D/TetherSettings( 4182): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4182): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4182): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4182): Cust_ConnectToPC   : spcsc>false
D/        ( 4182): Cust_ConnectToPC   : IPT>true
,D/        ( 4182): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4182): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4182): Index of the first 1 = 3
,W/Settings( 4182): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
W/ContextImpl( 4182): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4182): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 4182): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4182): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4182): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4182): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(437c41d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(437c41d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43e98c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=943862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43e98c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4271e090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(4271e090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4269bc88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(4269bc88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42433928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1003863, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42433928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(432033c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(432033c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(438d26b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{425390f0: PendingIntentRecord{42591bd8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928057, Int=0
D/PMS     (  904): acquireWL(43dec2c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
,V/AlarmManager(  904): sending alarm PendingIntent{425801a8: PendingIntentRecord{426bbda8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453135076861, Int=900000
,D/PMS     (  904): releaseWL(43dec2c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,V/AlarmManager(  904): sending alarm PendingIntent{435d43f0: PendingIntentRecord{43c95c58 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453135148292, Int=0
,D/PMS     (  904): acquireWL(44272828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,W/ContextImpl( 4523): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): releaseWL(44272828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PowerUsageService( 4523): call getInstance()
D/SmartSyncUtils( 4523): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4523): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4523): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4523): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
D/PMS     (  904): acquireWL(426dd308): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4523 1000 null
,D/PMS     (  904): releaseWL(438d26b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4523): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4523): SettingOnTime = 1453165200000, randomSettingOnTime = 1453162870000
,D/SmartSyncScreenOnOffTimeReceiver( 4523): SettingOffTime = 1453161600000, randomSettingOffTime = 1453162570000
,D/SmartSyncScreenOnOffTimeReceiver( 4523): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4523): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4523): bNightModeTurnOffOnce = false
D/PMS     (  904): acquireWL(43267260): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/PMS     (  904): releaseWL(426dd308): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  904): releaseWL(43267260): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  904): acquireWL(43e364f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  904): releaseWL(43e364f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(42494930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41ce42b0: PendingIntentRecord{424e6850 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1027866, Int=0
,D/PMS     (  904): acquireWL(423a08e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
D/PMS     (  904): releaseWL(42494930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(42331b50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(423a08e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(42331b50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  904): acquireWL(41e6c768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(41e6c768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/PowerUI ( 1114): closing low battery warning: level=100
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(424b8e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/PMS     (  904): acquireWL(42451ca0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,V/AlarmManager(  904): sending alarm PendingIntent{41ce42b0: PendingIntentRecord{424e6850 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1057886, Int=0
,D/PMS     (  904): releaseWL(424b8e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(42408990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=1 [57][1][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(41f91a60): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 904 1000 WorkSource{10106}
D/PMS     (  904): releaseWL(42451ca0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/PMS     (  904): releaseWL(42408990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(41dd08f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(41dd08f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4547): Last usage 0, idle 1453135194s, sync interval 2592000s
I/NewsWeather( 4547): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4547): Skip sync for lookup editions
,I/NewsWeather( 4547): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4547): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41e69200 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4547): Unrecoverable authentication exception
E/NewsWeather( 4547): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4547): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4547): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 11 4 12
,D/libc    ( 4547): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4547): [NET] getaddrinfo-,err=8
D/libc    ( 4547): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4547): [NET] getaddrinfo-, 1
D/libc    ( 4547): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8ee1 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4547): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4547): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4547): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(41fdecf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,E/NewsWeather( 4547): Failed to syncNewsAppData
,E/NewsWeather( 4547): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  904): releaseWL(41fdecf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(42455930): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/SyncManager(  904): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 524893, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  904): releaseWL(41f91a60): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1420/10028)
D/PMS     (  904): releaseWL(42455930): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(41e7ac18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(41e7ac18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/PMS     (  904): acquireWL(43c8e480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1063862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43c8e480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(41e97b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(41e97b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43e5fed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41ce42b0: PendingIntentRecord{424e6850 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1088129, Int=0
,D/PMS     (  904): acquireWL(4238e390): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43e5fed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(426b2950): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(4238e390): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(426b2950): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  904): acquireWL(421fbb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(421fbb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(431fff60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1123862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(431fff60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42672318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(42672318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42500308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(42500308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43053ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1183863, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43053ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42568a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): releaseWL(42568a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4261a440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4261a440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(44248130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1243862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44248130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43e2a090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43e2a090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4240fe60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4240fe60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42a0d910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c032a8: PendingIntentRecord{41ce4c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1303862, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42a0d910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42558380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(42558380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4632): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4632): ====startRecUseTime====
D/htc.customization.log.level( 4632):  is 
W/CustomizationLogLevel( 4632): Level value is invalid, use default level 2
D/CustomizationManager( 4632):  Read ACC file spent 0.096 (s)
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4632): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4632): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4632): Parsing tag category name = system
I/CustomizationCIDLoader( 4632): Parsing tag category name = application
I/CustomizationCIDLoader( 4632): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4632): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4632): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4632): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4632): Parsing tag category name = Settings
D/CustomizationManager( 4632):  Read CID file spent 0.142 (s)
D/CustomizationManager( 4632):  All configurations done spent 0.142 (s)
W/HtcNativeFlag( 4632): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4632): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4632): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4632): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4632, uid=2000 user=0
D/Process (  904): killProcessQuiet, pid=4463
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
I/ActivityManager(  904): Killing 4463:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
W/asset   (  904): Copying FileAsset 0x62fcfad0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1586): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1586): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1888): Unregistering com.test.thalitest
E/acms    ( 1888): Could not unregister removed application com.test.thalitest
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1420): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(4357ec10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
D/PMS     (  904): releaseWL(4357ec10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
D/PackageBroadcastService( 1227): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
E/ExternalAccountType( 1325): Unsupported attribute readOnly
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4646 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/ActivityManager(  904): Delaying start of: ServiceRecord{43d7ede8 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4661 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4646): install
I/MultiDex( 4646): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PeopleContactsSync( 1227): CP2 sync disabled
I/MultiDex( 4646): loading existing secondary dex files
I/MultiDex( 4646): load found 1 secondary dex files
I/MultiDex( 4646): install done
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1227, uid=10028, userID:0
D/PMS     (  904): acquireWL(43edcb48): PARTIAL_WAKE_LOCK  Icing 0x1 1227 10028 null
I/Icing   ( 1227): doRemovePackageData com.test.thalitest
I/MultiDex( 4661): install
D/PMS     (  904): releaseWL(43edcb48): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4646): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4661): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4661): loading existing secondary dex files
I/MultiDex( 4661): load found 1 secondary dex files
I/MultiDex( 4661): install done
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4661): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1396): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1396): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2890): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4682 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/ContextImpl( 4682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): acquireWL(43d260e0): PARTIAL_WAKE_LOCK  Icing 0x1 1227 10028 null
I/ActivityManager(  904): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
I/IcingCorporaProvider( 2890): UpdateCorporaTask done [took 265 ms] updated apps [took 265 ms] 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4702 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 4702): getInstance(Context context)
D/AppTag  ( 4702): getInstance(Context context)
D/AppTag  ( 4702): onCreate()
I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  904): acquireWL(42512778): PARTIAL_WAKE_LOCK  AsyncService 0x1 4160 10160 null
E/SQLiteLog( 4646): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4646): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca7c008
D/PMS     (  904): releaseWL(42512778): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/DriveAsyncService( 4646): disk I/O error (code 3850)
E/DriveAsyncService( 4646): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4646): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4646): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4646): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4646): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4646): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4646): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4646): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4646): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4646): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4646): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4646): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4646): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4646): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4646): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  904): Resuming delayed broadcast
I/DeviceManagement( 4349): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4349): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4349): WorkflowService: Starting workflow service
I/DeviceManagement( 4349): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d16f98] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4349): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4349): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4349): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4349): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4349): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 4349): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4349): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5cabc740
I/ActivityManager(  904): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4722 uid=10099 gids={50099, 3003, 5012}
W/DeviceManagement( 4349): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d16f98]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 4349): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 4349): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 4349): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4349): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4349): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4349): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4349): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4349): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4349): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4349): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4349): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4349): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4349): WorkflowService: Stopping workflow service
D/Process (  904): killProcessQuiet, pid=4385
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4385:com.htc.backup/1000 (adj 15): empty #17
E/SQLiteLog( 4646): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4646): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca7c008
E/DocListDatabase( 4646): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4646): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4646): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4646): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4646): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4646): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4646): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4646): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4646): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4646): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4646): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4646): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4646): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4646): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4646): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4646): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4646): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4646): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4646): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4646): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4646): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4646): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4646): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  904): Recipient 4385
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 4646): threadid=1: thread exiting with uncaught exception (group=0x41714e30)
E/AndroidRuntime( 4646): FATAL EXCEPTION: main
E/AndroidRuntime( 4646): Process: com.google.android.gms.drive, PID: 4646
E/AndroidRuntime( 4646): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4646): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4646): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4646): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4646): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4646): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4646): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4646): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4646): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4646): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4646): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4646): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4646): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4646): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4646): 	... 10 more
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
D/Process ( 4646): killProcess, pid=4646
D/Process ( 4646): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
D/Documents( 4722): Loading roots for com.android.providers.downloads.documents
D/Documents( 4722): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4722): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4722): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4722): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4722): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4722): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4722): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4722): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4722): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4722): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4722): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4722): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4722): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4722): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4722): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4722): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4722): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4722): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4722): threadid=1: thread exiting with uncaught exception (group=0x41714e30)
E/AndroidRuntime( 4722): FATAL EXCEPTION: main
E/AndroidRuntime( 4722): Process: com.android.documentsui, PID: 4722
E/AndroidRuntime( 4722): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4722): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4722): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4722): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4722): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4722): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4722): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4722): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4722): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4722): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4722): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4722): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4722): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4722): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4722): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4722): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4722): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4722): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4722): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4722): 	... 10 more
D/Process (  904): killProcessQuiet, pid=4403
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4738 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  904): Killing 4403:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
E/ActivityManager(  904): App crashed! Process: com.android.documentsui
D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4646
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4646) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
D/Process (  904): killProcessQuiet, pid=4038
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  904): Killing 4038:com.google.android.gm/u0a107 (adj 15): empty #17
D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4038
D/ExternalStorage( 4738): After updating volumes, found 1 active roots
I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4752 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Recipient 4403
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Documents( 4722): Loading roots for com.android.providers.media.documents
D/Documents( 4722): Loading roots for com.google.android.apps.docs.storage
D/Process ( 4722): killProcess, pid=4722
D/Process ( 4722): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453135455317.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  904): Recipient 4722
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.documentsui (pid 4722) has died.
E/SQLiteDatabase( 4752): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4752): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4752): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4752): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4752): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4752): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4752): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4752): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4752): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4752): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4752): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4752): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4752): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4752): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4752): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4752): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4752): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4752): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4752): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4752): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bd7e70 +
I/Prism.WidgetManager( 1271): onLoadItems() +
W/SQLiteOpenHelper( 4752): Opened MyDB.db in read-only mode
I/Icing   ( 1227): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
E/Icing   ( 1227): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1227): Could not init tag ds.tag.deleted

```
