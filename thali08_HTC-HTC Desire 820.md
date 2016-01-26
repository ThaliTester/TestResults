#### Test 5667282762e056f_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  907): acquireWL(432df470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
--------- beginning of /dev/log/main
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(432df470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,E/cutils-trace( 3855): Error opening trace file: No such file or directory (2)
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3864 uid=10077 gids={50077}
D/PMS     (  907): acquireWL(433492a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
V/AlarmManager(  907): sending alarm PendingIntent{42488f40: PendingIntentRecord{424dd1d8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453830978570, Int=60000
D/PMS     (  907): releaseWL(433492a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
D/SMSBackup( 3864): SMSBackupAgentService started
D/SMSBackup( 3864): Checking restore status
D/SMSBackup( 3864): Restore complete
D/SMSBackup( 3864): cancelCheckAlarm
D/SMSBackup( 3864): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  907): killProcessQuiet, pid=3688
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3688:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3688
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
D/CustomizationManager( 3855): ====startRecUseTime====
D/htc.customization.log.level( 3855):  is 
W/CustomizationLogLevel( 3855): Level value is invalid, use default level 2
D/CustomizationManager( 3855):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3855): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3855): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3855): Parsing tag category name = system
I/CustomizationCIDLoader( 3855): Parsing tag category name = application
I/CustomizationCIDLoader( 3855): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3855): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3855): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3855): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3855): Parsing tag category name = Settings
D/CustomizationManager( 3855):  Read CID file spent 0.101 (s)
D/CustomizationManager( 3855):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 3855): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3855): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3855): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3855): Fail to get flag for type 'language', use default value: -1
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1120690960
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3855
D/PMS     (  907): acquireHCC(432d4fe8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(43448d08): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b12c48
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
D/PMS     (  907): acquireWL(433974a8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3879 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1248): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3879): Binding Chromium to main looper Looper (main, tid 1) {41a80148}
I/LibraryLoader( 3879): Expected native library version number "",actual native library version number ""
I/chromium( 3879): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3879): Initializing chromium process, renderers=0
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42ccc048:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  907): acquireWL(439818c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(43b8f1a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): releaseWL(43b8f1a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 3879): 1101618048: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3879): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3879): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3879): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3879): Local Branch: 
I/Adreno-EGL( 3879): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3879): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3879):                  aa63bbd948f41d15fc72f585e
W/chromium( 3879): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3879): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3879): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3879): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3879): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3879): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3879): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3879): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3879): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3879): CordovaWebView is running on device made by: HTC
,W/AwContents( 3879): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1248
,W/ResourceType( 3879): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3879): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ac7108, mServedView=org.apache.cordova.engine.SystemWebView{41a8ce98 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  907): Enable input method client, pid=3879
W/AwContents( 3879): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +278ms
,D/PMS     (  907): releaseWL(433974a8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3879): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3879): JniHelper::setJavaVM(0x41555048), pthread_self() = 1663351928
,I/chromium( 3879): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 11.939MB for 42652-byte allocation
,W/PluginManager( 3879): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 12.029MB for 95956-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 12.111MB for 143930-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 12.227MB for 215890-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 12.403MB for 323830-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 12.669MB for 485740-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 13.683MB for 1092904-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 14.583MB for 1639352-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 15.843MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(432d4fe8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(43448d08): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 18.024MB for 3688532-byte allocation
,W/jxcore-log( 3879): Initializing JXcore engine
,W/jxcore-log( 3879): JXcore engine is ready
,W/jxcore-log( 3879): Starting JXcore engine
,W/jxcore-log( 3879): Platform android
W/jxcore-log( 3879): 
,W/jxcore-log( 3879): Process ARCH arm
W/jxcore-log( 3879): 
,I/jxcore-log( 3879): JXcore Cordova bridge is ready!
I/jxcore-log( 3879): 
,W/jxcore-log( 3879): JXcore engine is started
D/PMS     (  907): releaseWL(439818c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/jxcore  ( 3879): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3879): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3879): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3879): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 24ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  907): acquireWL(432c6d30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
,I/FeedHostManager( 1248): [onResume]
,I/FeedProviderManager( 1248): onResume
,I/SocialFeedProvider( 1248): +onResume
,I/ConnectivityHelper( 1248): [getCurrentConnectionType] no network connection
I/SocialFeedProvider( 1248): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1248): -onResume
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1248/10075)
,I/InputMethodManagerService(  907): Disable input method client, pid=3879
,W/IInputConnectionWrapper( 3879): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  907): Enable input method client, pid=1248
,D/PMS     (  907): releaseWL(432c6d30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  907): killProcessQuiet, pid=3412
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  907): Killing 3412:com.google.android.music:main/u0a154 (adj 15): empty #17
,E/libEGL  ( 3879): call to OpenGL ES API with no current context (logged once per thread)
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3412
,D/MediaRouterService(  907): Client com.google.android.music (pid 3412): Died!
,I/SensorManager(  907): mEventCount = 1050
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420846a8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420846a8, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420a80a0
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@42517848
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  907): mWirelessDisplayManager is null
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 371ms
D/PMS     (  907): nativeSetInteractive:false
D/NfcService( 1232): ScreenObserver: OFF
,D/NfcService( 1232): applyRouting - 0
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
D/PMS     (  907): OOBE c monitor 11
I/InputMethodManagerService(  907): Disable input method client, pid=1248
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
,D/NfcService( 1232): applyRouting -2
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43923580)
D/PMS     (  907): acquireWL(4352c7b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  907): releaseWL(4352c7b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): wakingUp
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2210): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/MtpService( 2210): [MTP][onReceive]-
,D/AutoSetting( 1392): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1232): applyRouting - 0
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907):    returned false
,D/NfcService( 1232): applyRouting -2
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  907): acquireWL(43d1dfa8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
,D/TetherSettings( 3344): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3344): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3344): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3344): Cust_ConnectToPC   : spcsc>false
D/        ( 3344): Cust_ConnectToPC   : IPT>true
,D/        ( 3344): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3344): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3344): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3344): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3344): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1392): service - onCreate()
,D/PMS     (  907): releaseWL(43d1dfa8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/PSReceiver( 3344): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1392): service - AddressCache: using context: com.htc.Weather
I/SmartNS_PSService( 3344): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3344): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3344):  defaultType:0
,V/SRS_Proc(  372): ParamSet string: screen_state=on
W/ContextImpl( 3344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1392): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/LocationManagerService(  907): request 42308dd0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
,I/ClockThread( 1109): stop update clock
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
W/ActivityManager(  907): Disable JIT of com.htc.bgp
,I/ActivityManager(  907): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3937 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/NetworkPolicy(  907): updateScreenOn: false
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(4320ea40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
D/PMS     (  907): releaseWL(4320ea40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420a80a0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420a80a0, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@42517848
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
,I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b12c48
,I/SocialFeedProvider( 1248): +onPause
D/PMN     (  907): goingToSleep
,D/PMS     (  907): acquireWL(42f414d8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/SocialFeedProvider( 1248): -onPause
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20619 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  907):    returned false
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: false
D/PMS     (  907): acquireWL(437eaf68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/PMS     (  907): releaseWL(437eaf68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/ContactMessageStore( 1221): start background delete task...
D/PMS     (  907): releaseWL(42f414d8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/NetworkPolicy(  907): updateScreenOn: false
I/CalendarProvider2( 3937): Created com.android.providers.calendar.CalendarAlarmManager@41aba978(com.android.providers.calendar.HtcCalendarProvider@41aa2d00)
D/ContactMessageStore( 1221): size: 0 , 0
D/ContactMessageStore( 1221): Background delete complete
D/CalendarProvider2( 3937): wait start:true
,D/CalendarProvider2( 3937): wait end:false
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3956 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  907): acquireWL(4343bac8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
,D/PMS     (  907): releaseWL(4343bac8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1392): service - mHandler: cancel location update
,D/AutoSetting( 1392): service -           changes count: 0
,W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3956): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(42b50ad8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3956 1000 null
,D/PMS     (  907): releaseWL(42b50ad8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3956): isEpsOn(), nState = 0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42517848
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42517848, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42517848, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42517848
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42517d90 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42517d90 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/SmartSyncUtils( 3956): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3956): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3956): getMobilePolicyEnabled, result = true
D/WifiService(  907): New client listening to asynchronous messages
,I/CalendarProvider2( 3937): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3937): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  907): killProcessQuiet, pid=3393
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3393:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3393
,D/ProviderChangeReceiver( 3719): ---------------------------------------------------
,D/ProviderChangeReceiver( 3719): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3719): start to updateAlertNotification!
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 3733): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3719): No fired or scheduled alerts
,D/HtcAlertUtils( 3719): -- cancelReminderNotification --
,D/HtcAlertUtils( 3719): broadcastExistReminder!
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  907): killProcessQuiet, pid=3433
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3433:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3433
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{432a06a8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  907): acquireWL(43ff7d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43ff7d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43fea9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10028}
,D/AutoSetting( 1392): service - handleMessage() stop self
V/AlarmManager(  907): sending alarm PendingIntent{436f7fb8: PendingIntentRecord{42506938 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141930, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{423d5b88: PendingIntentRecord{4244d410 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142014, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{42158648: PendingIntentRecord{42391f20 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=142020, Int=0
,D/AutoSetting( 1392): service - handleMessage() quit looper
,D/AutoSetting( 1392): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=3544
,I/ActivityManager(  907): Killing 3544:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3544
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  907): [NET] getaddrinfo_proxy-,
D/PMS     (  907): acquireWL(43d79c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(43d79c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  907): releaseWL(43fea9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43d30940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=145692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43d30940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1221): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(43b8fb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(43b8fb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43b142b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
V/AlarmManager(  907): sending alarm PendingIntent{42158648: PendingIntentRecord{42391f20 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=202284, Int=0
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3,
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  907): [NET] getaddrinfo_proxy-,
D/PMS     (  907): releaseWL(43b142b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(438d3a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=205692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(438d3a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43807088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43807088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43803938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43803938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(437f8078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=265692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(437f8078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(437f7138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(437f7138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(433eb8e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=325692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(433eb8e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1351): GoogleAccountDataService.getToken()
,W/GLSActivity( 1351): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1351): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1351): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NotificationStore( 1351): System rebooted after Notification storage file was last written
,I/NotificationStore( 1351): Deleting the file
,W/GLSActivity( 1351): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1351): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1351): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1351): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296),
W/GLSActivity( 1351): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1351): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1351): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1351): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1526): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 3609): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3609): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3609): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3609): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3609): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ba2620 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 4 13 3 12
,D/libc    ( 3609): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3609): [NET] getaddrinfo-,err=8
D/libc    ( 3609): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3609): [NET] getaddrinfo-, 1
D/libc    ( 3609): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3609): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3609): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  907): acquireWL(41fc5bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41fc5bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(421b34b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=385692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(421b34b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(41e262a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41e262a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(41b827b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=445692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41b827b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(424baee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(424baee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42490640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42490640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(4227dca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=505692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4227dca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,D/PMS     (  907): acquireWL(428e8e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428e8e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(424ff790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(424ff790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42308d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=565692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42308d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(422a4358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(422a4358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1221): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1221): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1221): sku_id=99
D/ContactMessageStore( 1221): start background delete task...
,D/ContactMessageStore( 1221): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1221): size: 0 , 0
,D/ContactMessageStore( 1221): Background delete complete,
,D/PMS     (  907): acquireWL(423c6670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=625692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(423c6670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,W/GLSUser ( 1351): GoogleAccountDataService.getToken()
,W/GLSActivity( 1351): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1351): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1351): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1526): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1351): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1351): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1351): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1351): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1351): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1351): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1351): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1351): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,E/PlayEventLogger( 3609): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3609): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3609): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3609): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3609): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ddac30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 3609): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
I/RemoteViews.Performance( 1109): com.google.android.gms 1 10 3 12
D/libc    ( 3609): [NET] getaddrinfo-,err=8
D/libc    ( 3609): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3609): [NET] getaddrinfo-, 1
D/libc    ( 3609): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3609): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3609): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  907): acquireWL(4229e9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4229e9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42eda0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=685692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42eda0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(424b3078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424b3078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(422b5210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(422b5210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3344): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3344): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3344): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3344): Cust_ConnectToPC   : spcsc>false
D/        ( 3344): Cust_ConnectToPC   : IPT>true
,D/        ( 3344): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3344): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3344): Index of the first 1 = 3
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
W/ContextImpl( 3344): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3344): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3344): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3344): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3344): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3344): [ACC]android_networking:tethering_guard_support=false
,W/ContextImpl( 3344): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(423d5cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=745692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(423d5cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,D/PMS     (  907): acquireWL(42304648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42304648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  907): acquireWL(42a76f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(42a76f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42aa37c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=805692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42aa37c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(424a80d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(424a80d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42a865b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42a865b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(422bc1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=865692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(422bc1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,D/PMS     (  907): acquireWL(429ad7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(429ad7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(429b8348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(429b8348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(429769e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=925692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(429769e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1351): GoogleAccountDataService.getToken()
,W/GLSActivity( 1351): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1351): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1351): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1526): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1351): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1351): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1351): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1351): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1351): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1351): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1351): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1351): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3609): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3609): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3609): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3609): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3609): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/libc    ( 3609): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3609): [NET] getaddrinfo-,err=8
D/libc    ( 3609): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3609): [NET] getaddrinfo-, 1
,D/libc    ( 3609): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024,
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3609): [NET] getaddrinfo_proxy-
E/PlayEventLogger( 3609): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ba92b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 3 11 2 12
,D/PMS     (  907): acquireWL(42a73e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(42a73e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42a033f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42a033f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(427947e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=985692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427947e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,D/PMS     (  907): acquireWL(429defb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41d45c68: PendingIntentRecord{423b9e40 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785456, Int=0
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4007 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42470720: PendingIntentRecord{42451078 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453831095379, Int=10800000
V/AlarmManager(  907): sending alarm PendingIntent{41ef4e98: PendingIntentRecord{4231e3d8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453831815771, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{427b3ed8: PendingIntentRecord{43eec1a0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453831886353, Int=0
,D/PowerUsageService( 3956): call getInstance()
,D/SmartSyncUtils( 3956): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3956): MY_DEBUG = false
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(427b2a80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3956 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 3956): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 3956): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3956): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3956): SettingOnTime = 1453856400000, randomSettingOnTime = 1453854356000
,D/SmartSyncScreenOnOffTimeReceiver( 3956): SettingOffTime = 1453852800000, randomSettingOffTime = 1453853101000
,D/SmartSyncScreenOnOffTimeReceiver( 3956): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3956): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3956): bNightModeTurnOffOnce = false
D/PMS     (  907): releaseWL(429defb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  907): releaseWL(427b2a80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4007/10047)
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/Process (  907): killProcessQuiet, pid=2912
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2912:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2912
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4269ac30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4269ac30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42640f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42640f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4242bab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1045692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4242bab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4231ebc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4231ebc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(422b4018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(422b4018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41c12828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1105692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41c12828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,D/PMS     (  907): acquireWL(422de0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(422de0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(420246f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(420246f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(41dce728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1165692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41dce728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42336a98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42336a98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  907): acquireWL(422a7ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(422a7ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus,
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424f3150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1225692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(424f3150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1205/10028)
,W/GLSUser ( 1351): GoogleAccountDataService.getToken()
,W/GLSActivity( 1351): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1351): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1351): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1526): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1351): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1351): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1351): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1351): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1351): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1351): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1351): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1351): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,E/PlayEventLogger( 3609): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3609): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3609): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3609): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3609): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3609): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 3609): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3609): [NET] getaddrinfo-,err=8
D/libc    ( 3609): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3609): [NET] getaddrinfo-, 1
D/libc    ( 3609): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41f34d60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3609): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3609): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 11 2 12
,D/PMS     (  907): acquireWL(42aa79d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(42aa79d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42503a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(42503a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41d8c6a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4207acd8: PendingIntentRecord{422d4cf8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1285692, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41d8c6a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4030): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4030): ====startRecUseTime====
D/htc.customization.log.level( 4030):  is 
W/CustomizationLogLevel( 4030): Level value is invalid, use default level 2
D/CustomizationManager( 4030):  Read ACC file spent 0.099 (s)
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4030): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4030): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4030): Parsing tag category name = system
I/CustomizationCIDLoader( 4030): Parsing tag category name = application
I/CustomizationCIDLoader( 4030): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4030): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4030): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4030): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4030): Parsing tag category name = Settings
D/CustomizationManager( 4030):  Read CID file spent 0.150 (s)
D/CustomizationManager( 4030):  All configurations done spent 0.150 (s)
W/HtcNativeFlag( 4030): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4030): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4030): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4030): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4030, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=3879
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 3879:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
I/acms    ( 1776): Unregistering com.test.thalitest
E/acms    ( 1776): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1526): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1526): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1526): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  907): acquireWL(422d6458): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
W/GeofencerStateMachine( 1415): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1306): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1306): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(422d6458): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
D/VoicemailCleanupService( 1276): Cleaning up data for package: com.test.thalitest
I/Launcher( 1248): Deferring update until onResume
D/Launcher( 1248): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1306): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
D/PackageBroadcastService( 1205): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
E/ExternalAccountType( 1306): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  907):   Scheme: "sms"
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4044 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
D/PhoneApp( 1221): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4044): install
I/MultiDex( 4044): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4044): loading existing secondary dex files
I/MultiDex( 4044): load found 1 secondary dex files
I/ActivityManager(  907): Delaying start of: ServiceRecord{44066270 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4044): install done
I/PeopleContactsSync( 1205): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1205, uid=10028, userID:0
D/PMS     (  907): acquireWL(433825a8): PARTIAL_WAKE_LOCK  Icing 0x1 1205 10028 null
I/Icing   ( 1205): doRemovePackageData com.test.thalitest
D/PMS     (  907): releaseWL(433825a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4062 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4044): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4062): install
I/MultiDex( 4062): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4062): loading existing secondary dex files
I/MultiDex( 4062): load found 1 secondary dex files
I/MultiDex( 4062): install done
I/ProviderInstaller( 4062): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  907): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1392): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1392): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1248): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2658): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4081 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/SQLiteLog( 2658): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2658): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63548388
W/dalvikvm( 2658): threadid=14: thread exiting with uncaught exception (group=0x4164de30)
E/AndroidRuntime( 2658): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2658): Process: com.google.android.googlequicksearchbox:search, PID: 2658
E/AndroidRuntime( 2658): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2658): 	at cid.d(PG:186)
E/AndroidRuntime( 2658): 	at clo.g(PG:594)
E/AndroidRuntime( 2658): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2658): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2658): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2658): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2658): 	at clr.tL(PG:827)
E/AndroidRuntime( 2658): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2658): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2658): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2658): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2658): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2658): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PackageManager(  907): Unable to load service info ResolveInfo{41d23268 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2658): killProcess, pid=2658
D/Process ( 2658): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4044): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4044): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4044): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4044): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4044): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4044): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4044): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4044): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4044): threadid=12: thread exiting with uncaught exception (group=0x4164de30)
I/ActivityManager(  907): Recipient 2658
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.googlequicksearchbox:search (pid 2658) has died.
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 2658): Died!
E/AndroidRuntime( 4044): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4044): Process: com.google.android.gms.drive, PID: 4044
E/AndroidRuntime( 4044): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4044): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4044): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4044): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4044): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4044): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4044): 	at ctn.run(SourceFile:985)
D/WifiService(  907): Client connection lost with reason: 4
E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ContextImpl( 4081): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4044): killProcess, pid=4044
D/Process ( 4044): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4081): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4081): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4081): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4081): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4081): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4081): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4081): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4081): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4081): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4081): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4081): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4081): threadid=10: thread exiting with uncaught exception (group=0x4164de30)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4081): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4081): Process: com.android.keychain, PID: 4081
E/AndroidRuntime( 4081): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4081): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4081): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4081): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4081): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4081): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4081): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4081): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4081): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4081): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4081): killProcess, pid=4081
D/Process ( 4081): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453832190959.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 4081
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4044
I/ActivityManager(  907): Process com.android.keychain (pid 4081) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10896ms
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4100 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4044) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10862ms
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
D/AppTag  ( 4100): getInstance(Context context)
D/AppTag  ( 4100): getInstance(Context context)
D/AppTag  ( 4100): onCreate()
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  907): acquireWL(422ce160): PARTIAL_WAKE_LOCK  AsyncService 0x1 3647 10160 null
D/PMS     (  907): releaseWL(422ce160): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/DeviceManagement( 3774): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 3774): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 3774): WorkflowService: Starting workflow service
I/DeviceManagement( 3774): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c50190] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 3774): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3774): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 3774): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3774): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 3774): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 3774): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3774): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5c9f5770
W/DeviceManagement( 3774): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c50190]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 3774): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 3774): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 3774): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 3774): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 3774): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 3774): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 3774): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 3774): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 3774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 3774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 3774): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 3774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4119 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 3774): WorkflowService: Stopping workflow service
D/Process (  907): killProcessQuiet, pid=3755
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3755:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3755
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Documents( 4119): Loading roots for com.android.providers.downloads.documents
D/Documents( 4119): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4119): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4119): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4119): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4119): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4119): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4119): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4119): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4119): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4119): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4119): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4119): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4119): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4119): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4119): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4119): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4119): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4119): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4119): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4119): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4119): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4119): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4119): threadid=1: thread exiting with uncaught exception (group=0x4164de30)
E/AndroidRuntime( 4119): FATAL EXCEPTION: main
E/AndroidRuntime( 4119): Process: com.android.documentsui, PID: 4119
E/AndroidRuntime( 4119): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4119): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4119): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4119): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4119): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4119): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4119): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4119): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4119): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4119): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4119): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4119): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4119): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4119): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4119): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4119): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4119): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4119): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4119): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4119): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4119): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4119): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4119): 	... 10 more
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4133 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process (  907): killProcessQuiet, pid=3807
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3807:com.htc.backup/1000 (adj 15): empty #17
E/ActivityManager(  907): App crashed! Process: com.android.documentsui
D/GCM     ( 1351): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4119): killProcess, pid=4119
D/Process ( 4119): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/Process (  907): killProcessQuiet, pid=3823
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453832191277.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 3807
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Killing 3823:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  907): Recipient 4119
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3823
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.documentsui (pid 4119) has died.
D/GCM     ( 1351): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ExternalStorage( 4133): After updating volumes, found 1 active roots
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4149 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4149): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4149): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4149): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4149): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4149): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4149): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4149): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4149): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4149): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4149): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4149): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4149): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4149): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4149): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4149): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4149): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4149): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4149): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4149): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4149): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4149): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4149): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4149): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4149): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4149): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4149): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 4149): Opened MyDB.db in read-only mode
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b10010 +
I/Prism.WidgetManager( 1248): onLoadItems() +

```
