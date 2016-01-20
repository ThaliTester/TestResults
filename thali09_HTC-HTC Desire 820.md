#### Test 564496606be5677_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,--------- beginning of /dev/log/main
E/cutils-trace( 4461): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4461): ====startRecUseTime====
D/htc.customization.log.level( 4461):  is 
W/CustomizationLogLevel( 4461): Level value is invalid, use default level 2
D/CustomizationManager( 4461):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4461): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4461): Parsing tag category name = system
I/CustomizationCIDLoader( 4461): Parsing tag category name = application
I/CustomizationCIDLoader( 4461): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4461): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4461): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4461): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4461): Parsing tag category name = Settings
D/CustomizationManager( 4461):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4461):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 4461): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4461): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4461): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4461): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4461
D/PMS     (  905): acquireHCC(43990058): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(44407798): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1130634600
D/PMS     (  905): acquireWL(42e6d538): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d1bc68
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4472 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4472): Binding Chromium to main looper Looper (main, tid 1) {41b5efb0}
I/LibraryLoader( 4472): Expected native library version number "",actual native library version number ""
I/chromium( 4472): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4472): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(444079d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(42660d78): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42660eb8:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4472): 1102548056: getState(). Returning 12
D/PMS     (  905): releaseWL(444079d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4472): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4472): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4472): Local Branch: 
I/Adreno-EGL( 4472): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4472): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4472):                  aa63bbd948f41d15fc72f585e
W/chromium( 4472): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4472): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4472): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4472): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4472): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4472): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4472): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4472): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4472): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4472): CordovaWebView is running on device made by: HTC
W/AwContents( 4472): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Disable input method client, pid=1273
W/ResourceType( 4472): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4472): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41baa308, mServedView=org.apache.cordova.engine.SystemWebView{41b6ff70 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Enable input method client, pid=4472
W/AwContents( 4472): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +409ms
D/PMS     (  905): releaseWL(42e6d538): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 6
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 12
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/JsMessageQueue( 4472): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4472): JniHelper::setJavaVM(0x4163c048), pthread_self() = 1663951376
I/chromium( 4472): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.993MB for 42652-byte allocation
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 12.070MB for 95956-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 12.150MB for 143930-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 12.264MB for 215890-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 12.439MB for 323830-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 12.711MB for 485740-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 13.679MB for 1092904-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 14.631MB for 1639352-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 15.877MB for 2459024-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(43990058): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(44407798): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 18.065MB for 3688532-byte allocation
,W/jxcore-log( 4472): Initializing JXcore engine
,W/jxcore-log( 4472): JXcore engine is ready
,W/jxcore-log( 4472): Starting JXcore engine
,W/jxcore-log( 4472): Platform android
W/jxcore-log( 4472): 
,W/jxcore-log( 4472): Process ARCH arm
W/jxcore-log( 4472): 
,I/jxcore-log( 4472): JXcore Cordova bridge is ready!
I/jxcore-log( 4472): 
,W/jxcore-log( 4472): JXcore engine is started
,E/jxcore  ( 4472): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4472): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4472): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4472): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  905): acquireWL(43e73590): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
,I/FeedHostManager( 1273): [onResume]
,I/FeedProviderManager( 1273): onResume
,I/SocialFeedProvider( 1273): +onResume
,I/SocialFeedProvider( 1273): updateAccounts - Accounts is no change
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.launcher (1273/10076)
I/SocialFeedProvider( 1273): -onResume
,I/InputMethodManagerService(  905): Disable input method client, pid=4472
,I/InputMethodManagerService(  905): Enable input method client, pid=1273
W/IInputConnectionWrapper( 4472): reportFullscreenMode on inactive InputConnection
,D/PMS     (  905): releaseWL(43e73590): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/PMS     (  905): releaseWL(42660d78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/Process (  905): killProcessQuiet, pid=3884
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  905): Killing 3884:com.google.android.music:main/u0a154 (adj 15): empty #17
,E/libEGL  ( 4472): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  905): Recipient 3884
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.music (pid 3884): Died!
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 18
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422636d8
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422636d8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4246e988
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@4263a7e8
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  905): mWirelessDisplayManager is null
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 317ms
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  905): Disable input method client, pid=1273
D/NfcService( 1257): ScreenObserver: OFF
D/NfcService( 1257): applyRouting - 0
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42bf3630)
,D/NfcService( 1257): applyRouting -2
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/PMS     (  905): acquireWL(42600f60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMN     (  905): wakingUp
D/PMS     (  905): releaseWL(42600f60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): acquireWL(4246fc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(4246fc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  905): onScreenOn
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,D/MtpService( 2721): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2721): [MTP][onReceive]-
,D/NfcService( 1257): applyRouting - 0
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
,D/AutoSetting( 1317): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1257): applyRouting -2
D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/ClockThread( 1117): stop update clock
D/PMS     (  905): acquireWL(41c88070): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  905): releaseWL(41c88070): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20814 delay=15s
D/TetherSettings( 4132): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4132): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4132): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4132): Cust_ConnectToPC   : spcsc>false
D/        ( 4132): Cust_ConnectToPC   : IPT>true
D/        ( 4132): Cust_ConnectToPC   : Singel_USB>false
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:On
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): BG scan when screen On
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): Match BG scan, scan!
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  905):    returned true
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,W/Settings( 4132): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/SRS_Proc(  372): ParamSet string: screen_state=on
E/SmartNS_Utility( 4132): hasRemovableStorageSlot: true
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/SmartNS_Utility( 4132): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4132): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4132): onReceive:android.intent.action.USER_PRESENT
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  905): updateScreenOn: false
W/ContextImpl( 4132): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4132): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4132): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4132):  defaultType:0
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4529 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  905): acquireWL(4270f460): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4270f460): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(426cf7c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426cf7c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1751): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1751): onScreenOn: 1453288509054
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1751): onScreenOn: 1453288509055
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4246e988
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4246e988, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@4263a7e8
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
W/ContextImpl( 4529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): acquireWL(42530810): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,I/FeedHostManager( 1273): [onPause]
,I/FeedProviderManager( 1273): onPause
,I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d1bc68
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20814 mDataStallAlarmIntent=PendingIntent{4269c568: PendingIntentRecord{4257e990 android broadcastIntent}}
,I/SocialFeedProvider( 1273): +onPause
,I/SocialFeedProvider( 1273): -onPause
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
D/PMS     (  905): acquireWL(4308cc08): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(42530810): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 4529): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(4256da20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4529 1000 null
,D/PMS     (  905): releaseWL(4256da20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4529): getMobilePolicyEnabled, result = true
,D/Process (  905): killProcessQuiet, pid=4252
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4252:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4252
D/WifiService(  905): Client connection lost with reason: 4
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 6
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:Off
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1159): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 24
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,D/WifiNative-wlan0(  905):    returned true
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/NetworkPolicy(  905): updateScreenOn: false
,D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
W/ContextImpl( 4529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4529): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4529): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4529): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4263a7e8
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  905): pid=905, uid=1000
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4263a7e8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4263a7e8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4263a7e8
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4263ad30 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4263ad30 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
,I/PhoneStatusBar( 1117): removeHeadsNotification.gc: 59
D/AutoSetting( 1317): service - mHandler: cancel location update
D/AutoSetting( 1317): service -           changes count: 0
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): acquireWL(42b59ef8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42b59ef8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(435d3ed8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(435d3ed8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1751): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1751): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1751): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1751): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1751): onScreenOff
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4308cc08): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1159): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1159): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1159): Add randomness: count=9 entropy=4
D/wpa_supplicant( 1159): Add randomness: count=10 en,tropy=5
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-46
I/wpa_supplicant( 1159): tsf=0000000106305331,
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-58,
I/wpa_supplicant( 1159): tsf=0000000106305357
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412,
I/wpa_supplicant( 1159): level=-80
I/wpa_supplicant( 1159): tsf=0000000106305368
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43905c60 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43905c60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43905c60 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 106305331, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 106305357, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 106305368, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 3 to mScanResults,
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (3) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==,
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=3862
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3862:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3862
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3919
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3919:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3919
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=11 entropy=6
D/wpa_supplicant( 1159): Add randomness: count=12 entropy=7
D/wpa_supplicant( 1159): Add randomness: count=13 entropy=8
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=14 entropy=9
D/wpa_supplicant( 1159): Add randomness: count=15 entropy=10
D/wpa_supplicant( 1159): Add randomness: count=16 entropy=11
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-46
I/wpa_supplicant( 1159): tsf=0000000123694773
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-58
I/wpa_supplicant( 1159): tsf=0000000123694796
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-78
I/wpa_supplicant( 1159): tsf=0000000123694810
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 123694773, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 123694796, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 123694810, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 3 to mScanResults
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiManager( 1226): getScanResults enter 
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/PMS     (  905): acquireWL(42e1b3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42e1b3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43f94698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{43d6c1e8: PendingIntentRecord{427f5720 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122949, Int=0
,D/PMS     (  905): acquireWL(4443b9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{4269b260: PendingIntentRecord{42826660 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135130, Int=0
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10029)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(43f7b390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1317): service - handleMessage() stop self
,D/AutoSetting( 1317): service - handleMessage() quit looper
,D/AutoSetting( 1317): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=4072
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4072:com.google.android.talk/u0a111 (adj 15): empty #17
,D/PMS     (  905): releaseWL(43f7b390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Recipient 4072
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(4443b9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43f94698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  905): acquireWL(4267ab30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): releaseWL(4267ab30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43b3d0f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1159): Change stage from stage3 to stage1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): acquireWL(422fdf80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(438b28f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1226): Vacuum at: now=1453288540131 tag=VacuumService
,D/PMS     (  905): releaseWL(43b3d0f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(422fdf80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44434560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): releaseWL(44434560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43b7f0b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(438b28f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
D/PMS     (  905): releaseWL(43b7f0b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(426fcfa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): releaseWL(426fcfa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43ed3aa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): releaseWL(43ed3aa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44430950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): acquireWL(43bd87c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43bd87c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4380f278): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44430950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(435dd5f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): releaseWL(435dd5f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1226): Scheduling Phenotype for one-off execution 9181 seconds from now (1453288541076)
,D/GetConfigurationSnapshotOperation( 1226): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1226): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1226): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,W/dalvikvm( 1226): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1c78 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(4380f278): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(443e4ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): releaseWL(443e4ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(427424a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): releaseWL(427424a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-90
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=17 entropy=12
D/wpa_supplicant( 1159): Add randomness: count=18 entropy=13
D/wpa_supplicant( 1159): Add randomness: count=19 entropy=14
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -90
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-90
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): selected network = 1
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-90
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=20 entropy=15
D/wpa_supplicant( 1159): Add randomness: count=21 entropy=16
D/wpa_supplicant( 1159): Add randomness: count=22 entropy=17
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/w,pa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0,
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-46
I/wpa_supplicant( 1159): tsf=0000000140782020
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
,I/wpa_supplicant( 1159): level=-90
I/wpa_supplicant( 1159): tsf=0000000140782045
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
,I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-78
I/wpa_supplicant( 1159): tsf=0000000140782057
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -90, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 140782020, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -90, frequency: 2412, timestamp: 140782045, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 140782057, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 3 to mScanResults
,V/ScoreHelper(  905):  + ScoreResult:  81, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi:  0 [-90], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(439f6a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{425c98d8: PendingIntentRecord{424b7110 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142433, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(44431238): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(439f6a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =59c6 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(44431238): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): acquireWL(43f65ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=155288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43f65ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(436ff208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(436ff208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(4378adc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{424ff1c8: PendingIntentRecord{438354f8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172338, Int=0
,D/PMS     (  905): releaseWL(4378adc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(43b65c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b65c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1365): disconnect managed GoogleApiClient
,D/PMS     (  905): acquireWL(427de838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=215288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427de838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42707eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42707eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43b9f980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b9f980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(42753228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=275288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42753228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(4309cce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4309cce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4340c3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/PowerUI ( 1117): closing low battery warning: level=100
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(4340c3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(438c3228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=335288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(438c3228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4353db48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4353db48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(446c9168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(446c9168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43ed3598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=395288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43ed3598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43ea4838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43ea4838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43ac63c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(43ac63c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43849f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=455288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43849f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43820998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43820998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(437f9848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=515288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(437f9848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(437f46e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(437f46e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(437eab18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/PMS     (  905): releaseWL(437eab18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(437e6598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=575288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(437e6598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(437e5838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/BatteryService(  905): n_update end
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(437e5838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(437cbb58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(437cbb58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1242): sku_id=99
D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete,
,D/PMS     (  905): acquireWL(423545d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=635288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(423545d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  905): killProcessQuiet, pid=4287,
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4287:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4287
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42729990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/BatteryService(  905): n_update end
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42729990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(424be150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(424be150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4220a6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=695288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4220a6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(438d2a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(438d2a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425ea2d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(425ea2d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425acb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=755288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425acb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426ebe18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(426ebe18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42599128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42599128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(425c5b10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=815288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425c5b10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4265df00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4265df00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(424bc118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(424bc118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4244c168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=875288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4244c168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42544c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42544c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(430cb120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(430cb120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42c04588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=935288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42c04588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42e11088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41e6a7f8: PendingIntentRecord{424fd598 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783126, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{425b2a60: PendingIntentRecord{4280e5a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=945178, Int=0
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4595 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{423c7a68: PendingIntentRecord{42428348 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453288616682, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{42678ca8: PendingIntentRecord{42678c70 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453289337092, Int=900000
,D/PMS     (  905): acquireWL(435da1f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(435da1f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4529): call getInstance()
,D/PMS     (  905): releaseWL(42e11088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4529): MY_DEBUG = false
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4595/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(42c05a68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024885
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025051
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025170
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025176
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025184
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026656
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026681
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029334
,D/PMS     (  905): releaseWL(42c05a68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=4317
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4317:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4317
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  905): acquireWL(4363af80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(4363af80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43439098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43439098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4309bee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=995288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4309bee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(436025a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/SmartSyncUtils( 4529): isEpsOn(), nState = 0
V/AlarmManager(  905): sending alarm PendingIntent{43965828: PendingIntentRecord{423ec7f0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453289409751, Int=0
,D/SmartSyncScreenOnOffTimeReceiver( 4529): [updateNmRange] bManual = false
D/PMS     (  905): acquireWL(437f54a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4529 1000 null
,D/PMS     (  905): releaseWL(436025a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4529): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4529): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4529): SettingOnTime = 1453356000000, randomSettingOnTime = 1453354791000
D/SmartSyncScreenOnOffTimeReceiver( 4529): SettingOffTime = 1453341600000, randomSettingOffTime = 1453344105000
D/SmartSyncScreenOnOffTimeReceiver( 4529): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4529): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4529): bNightModeTurnOffOnce = false
,D/PMS     (  905): releaseWL(437f54a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  905): acquireWL(43954b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43954b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  905): << updateStatus
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43b2d0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43b2d0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43885af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1055288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43885af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4308ce30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4308ce30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42e5c400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e5c400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42eb7c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1115288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42eb7c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43afd0c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43afd0c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(444419b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(444419b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4361b9e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1175288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4361b9e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(444168a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(444168a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(427d7100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1235288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427d7100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43ef5c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  905): releaseWL(43ef5c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42e4f950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e4f950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43b0d438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420f9298: PendingIntentRecord{420f9210 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1295288, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43b0d438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(435dbeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(435dbeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4622): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4622): ====startRecUseTime====
D/htc.customization.log.level( 4622):  is 
W/CustomizationLogLevel( 4622): Level value is invalid, use default level 2
D/CustomizationManager( 4622):  Read ACC file spent 0.096 (s)
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4622): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4622): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4622): Parsing tag category name = system
I/CustomizationCIDLoader( 4622): Parsing tag category name = application
I/CustomizationCIDLoader( 4622): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4622): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4622): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4622): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4622): Parsing tag category name = Settings
D/CustomizationManager( 4622):  Read CID file spent 0.140 (s)
D/CustomizationManager( 4622):  All configurations done spent 0.140 (s)
W/HtcNativeFlag( 4622): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4622): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4622): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4622): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4622, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=4472
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 4472:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  905): Skipping PackageSetting{422fb0d8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1226): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(44428628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
D/PMS     (  905): releaseWL(44428628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/IcingCorporaProvider( 2860): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4636 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
E/ExternalAccountType( 1339): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  905): acquireWL(421e70d0): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2860): UpdateCorporaTask done [took 288 ms] updated apps [took 288 ms] 
E/SQLiteDatabase( 4636): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4636): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4636): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4636): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4636): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4636): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4636): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4636): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4636): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4636): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4636): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4636): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4636): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4636): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4636): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4636): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4636): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4636): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4636): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4636): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4636): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4636): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4636): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4636): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4636): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4636): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4636): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4636): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4636): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4636): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4636): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4636): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4636): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4636): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4636): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4636): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4636): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4636): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4636): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4636): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4636): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4636): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4636): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4636): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4636): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4636): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4636): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4636): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4636): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4636): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4636): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4636): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4636): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4636): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4636): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4636): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4636): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4636): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4636): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4636): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4636): threadid=11: thread exiting with uncaught exception (group=0x41734e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4636): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4636): Process: com.google.android.apps.docs, PID: 4636
E/AndroidRuntime( 4636): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4636): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4636): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4636): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4636): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4636): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4636): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4636): 	at aho.run(AbstractDatabaseInstance.java:455)
E/SQLiteDatabase( 4636): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4636): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4636): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4636): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4636): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4636): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4636): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4636): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4636): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4636): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4636): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4636): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4636): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4636): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4636): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4636): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4636): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4636): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4636): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4636): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4636): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4636): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4636): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4636): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4636): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4636): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4636): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4636): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4636): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4636): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4636): Opened ClientFlag.db in read-only mode
D/Process ( 4636): killProcess, pid=4636
D/Process ( 4636): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4654 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
I/ActivityManager(  905): Recipient 4636
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4636) has died.
W/ProcessCpuTracker(  905): Skipping unknown process pid 4636
W/ContextImpl( 4654): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4667 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4654): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4654): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4654): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4654): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4654): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4654): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4654): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4654): threadid=10: thread exiting with uncaught exception (group=0x41734e30)
E/AndroidRuntime( 4654): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4654): Process: com.android.keychain, PID: 4654
E/AndroidRuntime( 4654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4654): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4654): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4654): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4654): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4654): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4654): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4667): getInstance(Context context)
D/Process ( 4654): killProcess, pid=4654
D/Process ( 4654): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453289717345.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Recipient 4654
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4667): getInstance(Context context)
I/ActivityManager(  905): Process com.android.keychain (pid 4654) has died.
D/AppTag  ( 4667): onCreate()
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  905): acquireWL(4277d240): PARTIAL_WAKE_LOCK  AsyncService 0x1 4110 10160 null
D/PMS     (  905): releaseWL(4277d240): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4146): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2180): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2180): Clearing selected account for com.test.thalitest
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bf7c38 +
I/Prism.WidgetManager( 1273): onLoadItems() +
D/ChimeraCfgMgr( 2180): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2180): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2180): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2180): Module APK com.google.android.play.games already loaded
I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2180): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2180): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2180): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2180): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65ac77a0
E/SQLiteDBG( 2180): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cb24c18
W/dalvikvm( 2180): threadid=44: thread exiting with uncaught exception (group=0x41734e30)
E/DriveAsyncService( 2180): disk I/O error (code 3850)
E/DriveAsyncService( 2180): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2180): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2180): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2180): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2180): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2180): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2180): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2180): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2180): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2180): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2180): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2180): Process: com.google.android.gms, PID: 2180
E/AndroidRuntime( 2180): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2180): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2180): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2180): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2180): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2180): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2180): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2180): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2180): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2180): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2180): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2180): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2180): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
D/Process ( 2180): killProcess, pid=2180
D/Process ( 2180): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2180
I/ActivityManager(  905): Process com.google.android.gms (pid 2180) has died.
D/WifiService(  905): Client connection lost with reason: 4
D/PMS     (  905): handleWLDeath(421e70d0): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
I/ActivityManager(  905): Resuming delayed broadcast
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20983ms
E/SQLiteLog( 1365): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1365): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5ca6e6f0
W/dalvikvm( 1365): threadid=1: thread exiting with uncaught exception (group=0x41734e30)
E/AndroidRuntime( 1365): FATAL EXCEPTION: main
E/AndroidRuntime( 1365): Process: com.google.process.gapps, PID: 1365
E/AndroidRuntime( 1365): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1365): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1365): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1365): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1365): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1365): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1365): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1365): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1365): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1365): 	... 10 more
E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
D/Process ( 1365): killProcess, pid=1365
D/Process ( 1365): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
I/DeviceManagement( 4304): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4304): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4304): WorkflowService: Starting workflow service
I/DeviceManagement( 4304): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d3bef8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4304): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4304): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4304): PackageUpdateWorkflow: ==================================================
I/ActivityManager(  905): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/DeviceManagement( 4304): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4304): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 4304): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4304): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5cac5df8
W/DeviceManagement( 4304): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d3bef8]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 4304): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 4304): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 4304): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4304): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4304): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4304): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4304): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4304): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4304): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4304): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4304): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4304): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4304): WorkflowService: Stopping workflow service
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4699 uid=10099 gids={50099, 3003, 5012}
I/ActivityManager(  905): Recipient 1365
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
I/ActivityManager(  905): Process com.google.process.gapps (pid 1365) has died.

```
