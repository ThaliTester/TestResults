#### Test 573480789efee08_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  907): mEventCount = 750
,--------- beginning of /dev/log/system
V/LightsService(  907): setLight #0: color=#24
V/LightsService(  907): setLight #0: color=#21
V/LightsService(  907): setLight #0: color=#1a
V/LightsService(  907): setLight #0: color=#14
D/CustomizationManager( 3928): ====startRecUseTime====
D/htc.customization.log.level( 3928):  is 
W/CustomizationLogLevel( 3928): Level value is invalid, use default level 2
D/CustomizationManager( 3928):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3928): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3928): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3928): Parsing tag category name = system
I/CustomizationCIDLoader( 3928): Parsing tag category name = application
I/CustomizationCIDLoader( 3928): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3928): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3928): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3928): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3928): Parsing tag category name = Settings
D/CustomizationManager( 3928):  Read CID file spent 0.104 (s)
D/CustomizationManager( 3928):  All configurations done spent 0.104 (s)
W/HtcNativeFlag( 3928): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3928): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3928): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3928): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3928
D/PMS     (  907): acquireHCC(443a7920): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(42d7e910): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x63d90b30 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1143475624
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ba59c0
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
E/cutils-trace( 3928): Error opening trace file: No such file or directory (2)
D/PMS     (  907): acquireWL(4251d0f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3940 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1247): [trimMemory] 20
W/asset   ( 3940): Copying FileAsset 0x5c70e428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3940): Binding Chromium to main looper Looper (main, tid 1) {41a8f3f0}
I/LibraryLoader( 3940): Expected native library version number "",actual native library version number ""
I/chromium( 3940): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3940): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(42d81e48): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(433517b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42611308:true
D/BluetoothAdapter( 3940): 1101680168: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  907): releaseWL(42d81e48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3940): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3940): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3940): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3940): Local Branch: 
I/Adreno-EGL( 3940): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3940): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3940):                  aa63bbd948f41d15fc72f585e
W/chromium( 3940): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3940): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3940): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3940): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3940): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3940): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3940): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3940): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3940): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3940): CordovaWebView is running on device made by: HTC
,W/AwContents( 3940): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1247
W/ResourceType( 3940): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3940): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ad9810, mServedView=org.apache.cordova.engine.SystemWebView{41a9c140 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1183): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1183): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Enable input method client, pid=3940
,W/AwContents( 3940): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +407ms
D/PMS     (  907): releaseWL(4251d0f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3940): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3940): JniHelper::setJavaVM(0x41565048), pthread_self() = 1662609960
,I/chromium( 3940): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 11.997MB for 42652-byte allocation
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 12.074MB for 95956-byte allocation
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 12.153MB for 143930-byte allocation
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 12.268MB for 215890-byte allocation
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 12.443MB for 323830-byte allocation
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 12.715MB for 485740-byte allocation
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 13.687MB for 1092904-byte allocation
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 14.635MB for 1639352-byte allocation
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 15.879MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(443a7920): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(42d7e910): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3940): Grow heap (frag case) to 18.062MB for 3688532-byte allocation
,W/jxcore-log( 3940): Initializing JXcore engine
,W/jxcore-log( 3940): JXcore engine is ready
,W/jxcore-log( 3940): Starting JXcore engine
,W/jxcore-log( 3940): Platform android
W/jxcore-log( 3940): 
,W/jxcore-log( 3940): Process ARCH arm
W/jxcore-log( 3940): 
,I/jxcore-log( 3940): JXcore Cordova bridge is ready!
I/jxcore-log( 3940): 
,W/jxcore-log( 3940): JXcore engine is started
,E/jxcore  ( 3940): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3940): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3940): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3940): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  907): acquireWL(441d4e90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
,I/FeedHostManager( 1247): [onResume]
I/FeedProviderManager( 1247): onResume
I/SocialFeedProvider( 1247): +onResume
I/SocialFeedProvider( 1247): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1247): -onResume
,I/ConnectivityHelper( 1247): [getCurrentConnectionType] no network connection
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1247/10076)
,I/InputMethodManagerService(  907): Disable input method client, pid=3940
,W/IInputConnectionWrapper( 3940): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  907): Enable input method client, pid=1247
,D/PMS     (  907): releaseWL(441d4e90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  907): killProcessQuiet, pid=3374
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  907): Killing 3374:com.htc.mediamanager/u0a34 (adj 15): empty #17
,E/libEGL  ( 3940): call to OpenGL ES API with no current context (logged once per thread)
D/PMS     (  907): releaseWL(433517b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3374
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420f9328
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
,W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420f9328, eanble = 0, strlen(mName) = 59,
,W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420743c0,
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@426110c8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  907): mWirelessDisplayManager is null
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 324ms
,D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
,D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
,D/PMS     (  907): OOBE c monitor 11
,I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
,D/PMS     (  907): acquireWL(42429ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@442338e0)
D/NfcService( 1225): ScreenObserver: OFF
,D/NfcService( 1225): applyRouting - 0
,D/NfcService( 1225): applyRouting -2
,I/IntentController( 1106): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  907): Disable input method client, pid=1247
D/PMN     (  907): wakingUp
D/PMS     (  907): releaseWL(42429ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): acquireWL(4231fdb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
,D/PMS     (  907): releaseWL(4231fdb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  907): updateBatteryInfo
W/ActivityManager(  907): Disable JIT of com.htc.bgp
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/MtpService( 2158): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2158): [MTP][onReceive]-
,D/NfcService( 1225): applyRouting - 0
I/ActivityManager(  907): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3989 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PMS     (  907): acquireWL(425c3a88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
,D/NfcService( 1225): applyRouting -2
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,I/ClockThread( 1106): stop update clock
D/PMS     (  907): releaseWL(425c3a88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  907):    returned false
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  907): updateScreenOn: false
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,I/CalendarProvider2( 3989): Created com.android.providers.calendar.CalendarAlarmManager@41ac9c18(com.android.providers.calendar.HtcCalendarProvider@41ab1fa0)
,D/CalendarProvider2( 3989): wait start:true
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(442e2988): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(442e2988): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CalendarProvider2( 3989): wait end:false
D/PMS     (  907): acquireWL(42418ec0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42418ec0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420743c0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420743c0, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@426110c8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
,D/PMS     (  907): acquireWL(423467e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,W/ContextImpl( 3753): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 ,
,I/FeedHostManager( 1247): [onPause]
,I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ba59c0
I/SocialFeedProvider( 1247): +onPause
,I/SocialFeedProvider( 1247): -onPause
,D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20916 mDataStallAlarmIntent=null
I/AlarmManager(  907): [AlarmQueuing] wifi connection: false
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  907):    returned false
D/PMS     (  907): acquireWL(436fb300): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/PMS     (  907): releaseWL(436fb300): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  907): releaseWL(423467e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 3753): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(424ed258): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3753 1000 null
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1214): start background delete task...
D/ContactMessageStore( 1214): size: 0 , 0
,D/ContactMessageStore( 1214): Background delete complete
,D/PMS     (  907): releaseWL(424ed258): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 3753): getMobilePolicyEnabled, result = true
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1293): receiver - intent: android.intent.action.USER_PRESENT
,D/TetherSettings( 3340): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3340): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3340): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3340): Cust_ConnectToPC   : spcsc>false
D/        ( 3340): Cust_ConnectToPC   : IPT>true
D/        ( 3340): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3340): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3340): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3340): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3340): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1293): service - onCreate()
,I/PSReceiver( 3340): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3340): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3340): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3340):  defaultType:0
W/ContextImpl( 3340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.android.settings/.PSReceiver
,D/AutoSetting( 1293): service - AddressCache: using context: com.htc.Weather
I/ActivityManager(  907): Resuming delayed broadcast
,D/AutoSetting( 1293): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  907): request 42566338 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 3753): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): acquireWL(43d9ff20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43d9ff20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 3753): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3753): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3753): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(441938a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/WifiService(  907): New client listening to asynchronous messages
D/PMS     (  907): releaseWL(441938a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426110c8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426110c8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426110c8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426110c8
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4265e138 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4265e138 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/CalendarProvider2( 3989): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3989): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/ProviderChangeReceiver( 3881): ---------------------------------------------------
,D/ProviderChangeReceiver( 3881): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3881): start to updateAlertNotification!
,W/ContextImpl( 3895): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3881): No fired or scheduled alerts,
D/HtcAlertUtils( 3881): -- cancelReminderNotification --
,D/HtcAlertUtils( 3881): broadcastExistReminder!
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  907): Killing 3415:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3415
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3415
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1293): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1293): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1293): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{441da228 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(422bec90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(422bec90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(436fc1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=135522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(436fc1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(434a7278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{425ed720: PendingIntentRecord{424cd900 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122250, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42d81eb0: PendingIntentRecord{424272f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136565, Int=0
,D/PMS     (  907): acquireWL(4258ed18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1354/10029)
,D/PMS     (  907): releaseWL(4258ed18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(434a7278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1293): service - handleMessage() stop self,
,D/AutoSetting( 1293): service - handleMessage() quit looper
,D/AutoSetting( 1293): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=3633
,I/ActivityManager(  907): Killing 3633:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3633
,D/PMS     (  907): acquireWL(42c0a2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e9fd8: PendingIntentRecord{42298b48 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142368, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{422f1bf0: PendingIntentRecord{42403320 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146540, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(43d24df8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
,D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  907): [NET] getaddrinfo_proxy-
D/PMS     (  907): releaseWL(43d24df8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  907): releaseWL(42c0a2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  907): acquireWL(442a3cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1106): closing low battery warning: level=100
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(442a3cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1214): switchBindHtcMsgCursor: null
,I/ClearcutLoggerApiImpl( 1354): disconnect managed GoogleApiClient
,D/PMS     (  907): acquireWL(442d63d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(442d63d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43a43a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=195521, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43a43a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44375500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42565ba8: PendingIntentRecord{424cd900 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=181988, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{422f1bf0: PendingIntentRecord{42403320 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=206628, Int=0
,D/PMS     (  907): acquireWL(44366f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  907): [NET] getaddrinfo_proxy-
D/PMS     (  907): releaseWL(44375500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1354/10029)
,D/PMS     (  907): acquireWL(442aec40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44366f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(442aec40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42495cd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024719
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024838
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024940
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024949
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026180
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026193
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028788
,D/PMS     (  907): releaseWL(42495cd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(442b36f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1354/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024719
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024838
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024940
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024949
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026180
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026193
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028788
,D/PMS     (  907): acquireWL(44315ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1198): Vacuum at: now=1453981691440 tag=VacuumService
D/PMS     (  907): releaseWL(442b36f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44315ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4242a7d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024719
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024838
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024940
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024944
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024949
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026180
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026193
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028788
,D/PMS     (  907): releaseWL(4242a7d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(423c0568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1354 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1354/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024719
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024838
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024940
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024944
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024949
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026180
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026193
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028788
D/PMS     (  907): releaseWL(423c0568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(435ed0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(435ed0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4253ae70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=255522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4253ae70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(4268c958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4268c958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1106): closing low battery warning: level=100
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(423f8610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(423f8610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(436835e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=315522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(436835e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3563): [NET] getaddrinfo-,err=8
D/libc    ( 3563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3563): [NET] getaddrinfo-, 1
,D/libc    ( 3563): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3563): [NET] getaddrinfo_proxy-
,D/PMS     (  907): acquireWL(42753b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42753b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(422c31f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=375522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(422c31f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43e730a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(43e730a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(442fa868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=435522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(442fa868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42427170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42427170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(436f77b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=495522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(436f77b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(433c9a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(433c9a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(431a98e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=555522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(431a98e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(433e1740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(433e1740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(42dce920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=615522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42dce920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1214): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1214): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1214): sku_id=99
D/ContactMessageStore( 1214): start background delete task...
,D/ContactMessageStore( 1214): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1214): size: 0 , 0
,D/ContactMessageStore( 1214): Background delete complete
,D/Process (  907): killProcessQuiet, pid=3778
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3778:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3778
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3563): [NET] getaddrinfo-,err=8
D/libc    ( 3563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3563): [NET] getaddrinfo-, 1
,D/libc    ( 3563): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3563): [NET] getaddrinfo_proxy-
,D/PMS     (  907): acquireWL(42d8f648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42d8f648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(433699b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=675522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(433699b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43573900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43573900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c97d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=735521, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c97d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42656970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42656970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(442ef330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=795522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(442ef330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(424e8a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424e8a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43379960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=855522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43379960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(436e9828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(436e9828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(441868b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=915522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(441868b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3563): [NET] getaddrinfo-,err=8
D/libc    ( 3563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3563): [NET] getaddrinfo-, 1
,D/libc    ( 3563): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3563): [NET] getaddrinfo_proxy-
,D/PMS     (  907): acquireWL(4315f280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4315f280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(437876a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=975522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(437876a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(442d60e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41ba2658: PendingIntentRecord{4241e580 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782429, Int=0
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4048 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42423518: PendingIntentRecord{425e0cd8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453981695876, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{42046d30: PendingIntentRecord{425cdd58 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453982416271, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{441866f0: PendingIntentRecord{4309fa40 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453982491032, Int=0
,W/ContextImpl( 3753): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3753): call getInstance()
,D/SmartSyncUtils( 3753): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3753): MY_DEBUG = false
D/PMS     (  907): releaseWL(442d60e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  907): acquireWL(442dbb28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3753 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3753): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3753): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3753): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3753): SettingOnTime = 1454047200000, randomSettingOnTime = 1454043759000
,D/SmartSyncScreenOnOffTimeReceiver( 3753): SettingOffTime = 1454032800000, randomSettingOffTime = 1454033337000
,D/SmartSyncScreenOnOffTimeReceiver( 3753): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3753): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3753): bNightModeTurnOffOnce = false
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/PMS     (  907): releaseWL(442dbb28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4048/10049)
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/Process (  907): killProcessQuiet, pid=3808
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  907): Killing 3808:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3808
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4242a150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4242a150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(442d5838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1035522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(442d5838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41e02d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41e02d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42d9e918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1095522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42d9e918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4318f8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4318f8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(436ffff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(436ffff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(442e9b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1155522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(442e9b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(429d7750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(429d7750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(4336a080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1215522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4336a080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3563): [NET] getaddrinfo-,err=8
D/libc    ( 3563): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3563): [NET] getaddrinfo-, 1
,D/libc    ( 3563): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3563): [NET] getaddrinfo_proxy-
,D/PMS     (  907): acquireWL(43a4d110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43a4d110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(425e0f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{420eabe8: PendingIntentRecord{41df7cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1275522, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425e0f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4067): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4067): ====startRecUseTime====
D/htc.customization.log.level( 4067):  is 
W/CustomizationLogLevel( 4067): Level value is invalid, use default level 2
D/CustomizationManager( 4067):  Read ACC file spent 0.105 (s)
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4067): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4067): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4067): Parsing tag category name = system
I/CustomizationCIDLoader( 4067): Parsing tag category name = application
I/CustomizationCIDLoader( 4067): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4067): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4067): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4067): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4067): Parsing tag category name = Settings
D/CustomizationManager( 4067):  Read CID file spent 0.159 (s)
D/CustomizationManager( 4067):  All configurations done spent 0.159 (s)
W/HtcNativeFlag( 4067): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4067): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4067): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4067): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4067, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=3940
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 3940:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
W/asset   (  907): Copying FileAsset 0x678c4308 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  907): Skipping PackageSetting{422255e8 com.example.hello/10397} due to missing metadata
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1525): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1315): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): acquireWL(426715c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426715c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1261): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/Launcher( 1247): Deferring update until onResume
D/Launcher( 1247): waitUntilResume // bindAppsRemoved
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/[PluginManager]RegisterService( 1293): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1293): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Scheme: "mmsto"
W/AccTypeManager( 1315): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1315): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1225): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/IcingCorporaProvider( 2582): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
E/ExternalAccountType( 1315): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4083 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PhoneApp( 1214): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  907): acquireWL(43ddb350): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2582): UpdateCorporaTask done [took 338 ms] updated apps [took 338 ms] 
E/SQLiteDatabase( 4083): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4083): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4083): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4083): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4083): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4083): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4083): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4083): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4083): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4083): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4083): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4083): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4083): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4083): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4083): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4083): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4083): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4083): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4083): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4083): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4083): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4083): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4083): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4083): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4083): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4083): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4083): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4083): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4083): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4083): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4083): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4083): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4083): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4083): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4083): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4083): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4083): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4083): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4083): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4083): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4083): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4083): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4083): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4083): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4083): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4083): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4083): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4083): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4083): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4083): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4083): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4083): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4083): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4083): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4083): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4083): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4083): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4083): threadid=11: thread exiting with uncaught exception (group=0x4165de30)
E/AndroidRuntime( 4083): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4083): Process: com.google.android.apps.docs, PID: 4083
E/AndroidRuntime( 4083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4083): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4083): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4083): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4083): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4083): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4083): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4083): killProcess, pid=4083
D/Process ( 4083): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4103 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4083
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4083) has died.
W/ContextImpl( 4103): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4116 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4103): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4103): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4103): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4103): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4103): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4103): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4103): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4103): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4103): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4103): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4103): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4103): threadid=10: thread exiting with uncaught exception (group=0x4165de30)
E/AndroidRuntime( 4103): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4103): Process: com.android.keychain, PID: 4103
E/AndroidRuntime( 4103): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4103): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4103): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4103): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4103): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4103): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4103): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4103): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4103): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4103): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4103): killProcess, pid=4103
D/Process ( 4103): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453982796269.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 4116): getInstance(Context context)
D/AppTag  ( 4116): getInstance(Context context)
D/AppTag  ( 4116): onCreate()
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  907): acquireWL(425e9900): PARTIAL_WAKE_LOCK  AsyncService 0x1 3536 10160 null
D/PMS     (  907): releaseWL(425e9900): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
W/dalvikvm( 3563): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4103
I/ActivityManager(  907): Process com.android.keychain (pid 4103) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1962): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
W/PackageManager(  907): Unable to load service info ResolveInfo{438b22c8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/LocationSettingsChecker( 1962): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1962): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1962): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x5ca29290
W/dalvikvm( 1962): threadid=36: thread exiting with uncaught exception (group=0x4165de30)
E/AndroidRuntime( 1962): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1962): Process: com.google.android.gms, PID: 1962
E/AndroidRuntime( 1962): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1962): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1962): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1962): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1962): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1962): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1962): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1962): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1962): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1962): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1962): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1962): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1962): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 1962): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1962): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1962): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1962): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1962): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1962): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1962): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1962): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1962): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1962): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1962): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1962): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1962): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1962): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1962): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1962): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1962): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1962): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1962): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1962): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1962): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1962): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1962): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 1962): killProcess, pid=1962
W/SQLiteOpenHelper( 1962): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
E/SQLiteDatabase( 1962): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1962): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1962): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1962): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1962): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1962): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1962): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1962): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1962): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1962): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/Process ( 1962): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 1962
I/ActivityManager(  907): Process com.google.android.gms (pid 1962) has died.
D/PMS     (  907): handleWLDeath(43ddb350): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20996ms
E/SQLiteLog( 1354): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1354): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x647f5fc8
W/dalvikvm( 1354): threadid=1: thread exiting with uncaught exception (group=0x4165de30)
E/AndroidRuntime( 1354): FATAL EXCEPTION: main
E/AndroidRuntime( 1354): Process: com.google.process.gapps, PID: 1354
E/AndroidRuntime( 1354): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1354): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1354): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1354): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1354): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1354): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1354): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1354): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1354): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1354): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1354): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1354): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1354): 	... 10 more
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
D/Process ( 1354): killProcess, pid=1354
I/DeviceManagement( 3795): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
D/Process ( 1354): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 3795): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
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
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/DeviceManagement( 3795): WorkflowService: Starting workflow service
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41b1fd70 +
I/DeviceManagement( 3795): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c68078] args=[Bundle[mParcelledData.dataSize=120]]
I/Prism.WidgetManager( 1247): onLoadItems() +
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4146 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 3795): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3795): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 3795): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3795): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 3795): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 3795): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3795): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5c9f3ad8
W/DeviceManagement( 3795): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c68078]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 3795): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 3795): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 3795): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 3795): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 3795): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 3795): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 3795): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 3795): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 3795): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 3795): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 3795): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 3795): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 3795): WorkflowService: Stopping workflow service
D/Documents( 4146): Loading roots for com.android.providers.downloads.documents
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 1354
I/ActivityManager(  907): Process com.google.process.gapps (pid 1354) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20852ms
D/WifiService(  907): Client connection lost with reason: 4
D/Documents( 4146): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4146): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4146): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4146): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4146): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4146): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4146): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4146): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4146): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4146): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4146): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4146): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4146): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4146): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4146): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4146): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4146): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4146): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4146): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4146): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4146): threadid=1: thread exiting with uncaught exception (group=0x4165de30)
E/AndroidRuntime( 4146): FATAL EXCEPTION: main
E/AndroidRuntime( 4146): Process: com.android.documentsui, PID: 4146
E/AndroidRuntime( 4146): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4146): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4146): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4146): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4146): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4146): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4146): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4146): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4146): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4146): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4146): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4146): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4146): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4146): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4146): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4146): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4146): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4146): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4146): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4146): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4146): 	... 10 more
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4160 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4172 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
D/Process (  907): killProcessQuiet, pid=3824
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
E/ActivityManager(  907): App crashed! Process: com.android.documentsui
I/ActivityManager(  907): Killing 3824:com.htc.backup/1000 (adj 15): empty #17
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  907): Recipient 3824
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ExternalStorage( 4160): After updating volumes, found 1 active roots
D/Documents( 4146): Loading roots for com.android.providers.media.documents
D/Process ( 4146): killProcess, pid=4146
D/Process ( 4146): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453982796774.dbox_tmp: open failed: EROFS (Read-only file system)
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
W/dalvikvm( 4172): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 4172): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4172): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4172): install
I/MultiDex( 4172): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/MultiDex( 4172): loading existing secondary dex files

```
