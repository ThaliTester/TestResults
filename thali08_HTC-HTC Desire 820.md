#### Test 50650278b1aec71_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  899): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3863 uid=10077 gids={50077}
D/PMS     (  899): acquireWL(447b1800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{10077}
V/AlarmManager(  899): sending alarm PendingIntent{42cc6d78: PendingIntentRecord{42dbdde8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449595649515, Int=60000
,D/PMS     (  899): releaseWL(447b1800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
--------- beginning of /dev/log/main
D/SMSBackup( 3863): SMSBackupAgentService started
D/SMSBackup( 3863): Checking restore status
D/SMSBackup( 3863): Restore complete
D/SMSBackup( 3863): cancelCheckAlarm
D/SMSBackup( 3863): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  899): killProcessQuiet, pid=1464
D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  899): Killing 1464:com.htc.bgp/u0a14 (adj 15): empty #17
I/ActivityManager(  899): Recipient 1464
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/cutils-trace( 3876): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3876): ====startRecUseTime====
D/htc.customization.log.level( 3876):  is 
W/CustomizationLogLevel( 3876): Level value is invalid, use default level 2
D/CustomizationManager( 3876):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3876): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3876): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3876): Parsing tag category name = system
I/CustomizationCIDLoader( 3876): Parsing tag category name = application
I/CustomizationCIDLoader( 3876): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3876): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3876): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3876): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3876): Parsing tag category name = Settings
D/CustomizationManager( 3876):  Read CID file spent 0.088 (s)
D/CustomizationManager( 3876):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 3876): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3876): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3876): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3876): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  899): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  899): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  899): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  899): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  899): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  899): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  899): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3876
I/Intent  (  899): @test_code: getHtcIntentFlag: 0 obj: 1149118384
D/PMS     (  899): acquireHCC(444c5d70): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 899 1000 null
D/PMS     (  899): acquireHCC(444c0b60): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 899 1000 null
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42500650
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
D/PMS     (  899): acquireWL(444b8c50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 899 1000 null
I/ActivityManager(  899): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3887 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1247): [trimMemory] 20
W/asset   ( 3887): Copying FileAsset 0x5d7cd428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3887): Binding Chromium to main looper Looper (main, tid 1) {423e9408}
I/LibraryLoader( 3887): Expected native library version number "",actual native library version number ""
I/chromium( 3887): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3887): Initializing chromium process, renderers=0
W/System.err(  899): java.lang.Throwable: stack dump
D/BluetoothManagerService(  899): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  899): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44449b60:true
W/System.err(  899): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  899): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  899): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  899): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  899): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3887): 1111486016: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  899): acquireWL(44452a80): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  899): acquireWL(4444f670): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  899): releaseWL(44452a80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3887): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3887): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3887): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3887): Local Branch: 
I/Adreno-EGL( 3887): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3887): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3887):                  aa63bbd948f41d15fc72f585e
W/chromium( 3887): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3887): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3887): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3887): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3887): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3887): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3887): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3887): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3887): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3887): CordovaWebView is running on device made by: HTC
,W/AwContents( 3887): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  899): Disable input method client, pid=1247
,W/ResourceType( 3887): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3887): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@424303c8, mServedView=org.apache.cordova.engine.SystemWebView{423f6158 VFEDH.C. .F...... 0,0-720,1134 #64}
W/XT9_C   ( 1183): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1183): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  899): Enable input method client, pid=3887
D/PMS     (  899): releaseWL(444b8c50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  899): Displayed com.test.thalitest/.MainActivity: +269ms
,D/JsMessageQueue( 3887): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3887): JniHelper::setJavaVM(0x41fa3010), pthread_self() = 1662323784
,D/JX-Cordova( 3887): jxcore cordova android initializing
,W/dalvikvm( 3887): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 11.550MB for 95956-byte allocation
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 11.629MB for 143930-byte allocation
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 11.745MB for 215890-byte allocation
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 11.918MB for 323830-byte allocation
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 12.191MB for 485740-byte allocation
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 13.191MB for 1092904-byte allocation
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 14.067MB for 1639352-byte allocation
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 15.434MB for 2459024-byte allocation
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 17.470MB for 3688532-byte allocation
,W/jxcore-log( 3887): Initializing JXcore engine
,W/jxcore-log( 3887): JXcore engine is ready
,W/CpuWake (  899): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  899): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  899): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  899): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  899): >>release mCpuPerf_Freq wakelock
W/CpuWake (  899): <<release mCpuPerf_Freq wakelock
,D/PMS     (  899): releaseHCC(444c5d70): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/jxcore-log( 3887): Starting JXcore engine
D/PMS     (  899): releaseHCC(444c0b60): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3887): Platform android
W/jxcore-log( 3887): 
,W/jxcore-log( 3887): Process ARCH arm
W/jxcore-log( 3887): 
,I/jxcore-log( 3887): JXcore Cordova bridge is ready!
I/jxcore-log( 3887): 
,W/jxcore-log( 3887): JXcore engine is started
,I/chromium( 3887): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3887): Error!: missing ) after argument list
E/jxcore  ( 3887): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/ActivityManager(  899): mThumbnailWidth=360, mThumbnailHeight=640
,I/chromium( 3887): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,W/PluginManager( 3887): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  899): acquireWL(443fa158): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 899 1000 null
,I/FeedHostManager( 1247): [onResume]
,I/FeedProviderManager( 1247): onResume
I/SocialFeedProvider( 1247): +onResume
I/SocialFeedProvider( 1247): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1247): -onResume
,I/ConnectivityHelper( 1247): [getCurrentConnectionType] no network connection
D/ConnectivityService(  899): getActiveNetworkInfo called by com.htc.launcher (1247/10075)
,I/InputMethodManagerService(  899): Disable input method client, pid=3887
,I/InputMethodManagerService(  899): Enable input method client, pid=1247
,W/IInputConnectionWrapper( 3887): reportFullscreenMode on inactive InputConnection
D/PMS     (  899): releaseWL(443fa158): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  899): killProcessQuiet, pid=3357
,D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  899): Killing 3357:com.htc.mediamanager/u0a32 (adj 15): empty #17
,E/libEGL  ( 3887): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  899): Recipient 3357
,I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  899): releaseWL(4444f670): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  899): mEventCount = 900
,I/PMS     (  899): Going to sleep due to screen timeout...
,I/SensorManager(  899): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a8ae38
W/SensorService(  899): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  899): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  899): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  899): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  899): pid=899, uid=1000
W/PMS     (  899): mWirelessDisplayManager is null
W/BatSI   (  899): Couldn't get kernel wake lock stats
V/LightsService(  899): setLight #2: color=#0
D/qdlights(  899): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  899): setLight #0: color=#0
W/SensorService(  899): Active sensors: size = 2
W/SensorService(  899): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  899): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  899): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a8ae38, eanble = 0, strlen(mName) = 59
W/SensorService(  899): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  899): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42c50068
W/SensorService(  899): Listener[1] = com.htc.smartdim.sensor_eye@42cda738
W/SensorService(  899): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  899): Excessive delay in blankDisplay() while turning screen off: 380ms
D/PMS     (  899): nativeSetInteractive:false
D/PMS     (  899): nativeSetInteractive:false done
D/PMS     (  899): nativeSetAutoSuspend:true
D/PMS     (  899): nativeSetAutoSuspend:true done
D/HABCtrl (  899): TPE algorithm. remove timeout.
I/InputManager(  899): Cancel all due to getting PMS screen off broadcast
I/IntentController( 1108): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  899): screenObserver, isScreenOn=false
D/PMS     (  899): OOBE c monitor 11
,I/InputMethodManagerService(  899): Disable input method client, pid=1247
D/NfcService( 1230): ScreenObserver: OFF
D/NfcService( 1230): applyRouting - 0
,V/KeyguardServiceDelegate(  899): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43629948)
,D/NfcService( 1230): applyRouting -2
D/PMS     (  899): acquireWL(43e4e510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  899): wakingUp
I/BatteryService(  899): n_update end
D/PMS     (  899): acquireWL(43e44860): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/PMS     (  899): releaseWL(43e4e510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/KeyguardServiceDelegate(  899): **** SHOWN CALLED ****
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/WindowManager(  899): No lock screen! windowToken=null
D/PMS     (  899): releaseWL(43e44860): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMN     (  899): onScreenOn
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 2208): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2208): [MTP][onReceive]-
,D/NfcService( 1230): applyRouting - 0
I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  899): << updateStatus
D/AlarmManager(  899): ACTION_SCREEN_ON
I/AlarmManager(  899): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  899): [AlarmQueuing] done recovering
I/AlarmManager(  899): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  899): [AlarmQueuing] done EPS screen off alarm recovering
D/WirelessDisplayService(  899): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/NfcService( 1230): applyRouting -2
D/WirelessDisplayService(  899): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  899): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WirelessDisplayService(  899): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/AutoSetting( 1376): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  899): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  899): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  899): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  899): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  899):    returned false
D/PMS     (  899): acquireWL(43e05e90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
V/NotificationService(  899): batLight: Full, plugged
V/LightsService(  899): setLight #8: color=#c8c800
D/qdlights(  899): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  899): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  899): setLight #8: color=#c800
D/PMS     (  899): releaseWL(43e05e90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/qdlights(  899): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  899): [LedInfo] has indicator attribute
D/qdlights(  899): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  899): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/TetherSettings( 3287): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3287): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3287): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3287): Cust_ConnectToPC   : spcsc>false
D/        ( 3287): Cust_ConnectToPC   : IPT>true
D/        ( 3287): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3287): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3287): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3287): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3287): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1376): service - onCreate()
,I/ClockThread( 1108): stop update clock
,I/PSReceiver( 3287): onReceive:android.intent.action.USER_PRESENT
W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
V/NotificationService(  899): batLight: Full, plugged
V/LightsService(  899): setLight #8: color=#c8c800
D/qdlights(  899): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  899): [LedInfo] has indicator attribute mode=x0ff
W/ContextImpl( 3287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/LightsService(  899): setLight #8: color=#c800
D/qdlights(  899): set_color_led color=51200, mode=1, off_min=0, off_sec=0
I/SmartNS_PSService( 3287): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3287): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3287):  defaultType:0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/AutoSetting( 1376): service - AddressCache: using context: com.htc.Weather
,D/WirelessDisplayService(  899): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  899): [LedInfo] has indicator attribute
D/qdlights(  899): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  899): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1376): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  899): request 42e60b48 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  899): provider request: passive ProviderRequest[ON interval=0]
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
W/ActivityManager(  899): Disable JIT of com.htc.bgp
W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/ActivityManager(  899): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3940 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/NetworkPolicy(  899): updateScreenOn: false
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  899): acquireWL(43c4ce78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1393 10028 null
,D/PMS     (  899): releaseWL(43c4ce78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  899): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42c50068
W/SensorService(  899): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  899): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  899): pid=899, uid=1000
W/SensorService(  899): Active sensors: size = 2
W/SensorService(  899): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  899): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  899): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42c50068, eanble = 0, strlen(mName) = 91
W/SensorService(  899): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  899): Listener[0] = com.htc.smartdim.sensor_eye@42cda738
,W/SensorService(  899): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
D/PMN     (  899): goingToSleep
,D/PMS     (  899): acquireWL(43b5d830): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 899 1000 null
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42500650
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
,D/AlarmManager(  899): ACTION_SCREEN_OFF
,I/AlarmManager(  899): [AlarmQueuing] screen off now: 
I/AlarmManager(  899): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  899): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  899): stopDataStallAlarm: current tag=19990 mDataStallAlarmIntent=null
,I/CalendarProvider2( 3940): Created com.android.providers.calendar.CalendarAlarmManager@42423c38(com.android.providers.calendar.HtcCalendarProvider@4240bfc0)
,D/WifiNative-wlan0(  899): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  899):    returned false
I/AlarmManager(  899): [AlarmQueuing] wifi connection: false
D/PMS     (  899): releaseWL(43b5d830): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  899): acquireWL(43440c78): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 899 1000 null
,D/CalendarProvider2( 3940): wait start:true
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  899): releaseWL(43440c78): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/NetworkPolicy(  899): updateScreenOn: false
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/CalendarProvider2( 3940): wait end:false
,W/ContextImpl( 3721): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3721): isEpsOn(), nState = 0
D/PMS     (  899): acquireWL(431b78e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3721 1000 null
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] getTotalRam: 1873 Mb
D/PMS     (  899): releaseWL(431b78e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  899): acquireWL(42cbede8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1393 10028 null
D/PMS     (  899): releaseWL(42cbede8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1376): service - mHandler: cancel location update
D/AutoSetting( 1376): service -           changes count: 0
,D/SmartSyncUtils( 3721): getMobilePolicyEnabled, result = true
W/ContextImpl(  899): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3721): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3721): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3721): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3721): isEpsOn(), nState = 0
D/WifiService(  899): New client listening to asynchronous messages
,W/ContextImpl(  899): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  899): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42cda738
W/SensorService(  899): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  899): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  899): pid=899, uid=1000
W/SensorService(  899): Active sensors: size = 1
W/SensorService(  899): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  899): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42cda738, eanble = 0, strlen(mName) = 36
W/SensorService(  899): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  899): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  899): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  899): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  899): pid=899, uid=1000
W/SensorService(  899): Active sensors: size = 0
W/SensorService(  899): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42cda738, eanble = 0, strlen(mName) = 36
W/SensorService(  899): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  899): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  899): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42cda738
E/ActivityThread(  899): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42cdac80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  899): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42cdac80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  899): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  899): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  899): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  899): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  899): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  899): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  899): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  899): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  899): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  899): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  899): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  899): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  899): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  899): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  899): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  899): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 3940): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3940): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3734): ---------------------------------------------------
,D/ProviderChangeReceiver( 3734): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3734): start to updateAlertNotification!
,W/ContextImpl( 3748): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3734): No fired or scheduled alerts
,D/HtcAlertUtils( 3734): -- cancelReminderNotification --
,D/HtcAlertUtils( 3734): broadcastExistReminder!
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  899): killProcessQuiet, pid=3409
,D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  899): Killing 3409:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  899): Recipient 3409
,I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  899): Waited long enough for: ServiceRecord{4384cb40 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  899): acquireWL(440fb370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
,D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): releaseWL(440fb370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  899): acquireWL(440cb730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=134515, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(440cb730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1376): service - handleMessage() stop self
,D/AutoSetting( 1376): service - handleMessage() quit looper
,D/AutoSetting( 1376): service - onDestroy() END
,D/Process (  899): killProcessQuiet, pid=3521
,D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  899): Killing 3521:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  899): Recipient 3521
,I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  899): acquireWL(4409ffa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{10028}
,V/AlarmManager(  899): sending alarm PendingIntent{441635a0: PendingIntentRecord{42c5ea98 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140707, Int=0
V/AlarmManager(  899): sending alarm PendingIntent{42ae1e78: PendingIntentRecord{42daea08 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141421, Int=0
,D/GpsLocationProvider(  899): ALARM_XTRA_TIMEOUT
V/AlarmManager(  899): sending alarm PendingIntent{42c516b0: PendingIntentRecord{42c55410 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145724, Int=0
D/PMS     (  899): acquireWL(440959a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 899 1000 null
,D/PMS     (  899): releaseWL(4409ffa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  899): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  899): [NET] getaddrinfo-,err=8
D/libc    (  899): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  899): [NET] getaddrinfo-, 1
D/libc    (  899): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    (  899): [NET] getaddrinfo_proxy-
,D/GpsLocationProvider(  899): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  899): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  899): releaseWL(440959a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  899): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  899): acquireWL(44045240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
,D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): releaseWL(44045240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  899): acquireWL(4400dfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(4400dfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  899): updateBatteryInfo
,D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
,I/HtcPowerSaver(  899): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(43fcadb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
D/UsbnetService(  899): BroadcastReceiver::onReceive+
,D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  899): releaseWL(43fcadb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  899): acquireWL(43f98fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=194516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(43f98fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(43f7d468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
D/libc    (  899): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  899): [NET] getaddrinfo-,err=8
D/libc    (  899): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  899): [NET] getaddrinfo-, 1
,D/libc    (  899): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  899): [NET] getaddrinfo_proxy-
V/AlarmManager(  899): sending alarm PendingIntent{42c516b0: PendingIntentRecord{42c55410 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=205747, Int=0
D/PMS     (  899): releaseWL(43f7d468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  899): acquireWL(43f58250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/HtcPowerSaver(  899): updateBatteryInfo
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
D/PMS     (  899): releaseWL(43f58250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  899): acquireWL(43f180e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
D/PMS     (  899): releaseWL(43f180e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(43ecd550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=254515, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(43ecd550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(43ea5060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(43ea5060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(43e985f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=314516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(43e985f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  899): acquireWL(43e7a070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(43e7a070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NotificationStore( 1338): System rebooted after Notification storage file was last written
,I/NotificationStore( 1338): Deleting the file
,D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3608): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3608): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3608): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3608): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{4242e0f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.google.android.gms 2 10 4 12
,D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3608): [NET] getaddrinfo-,err=8
D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3608): [NET] getaddrinfo-, 1
,D/libc    ( 3608): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3608): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3608): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  899): acquireWL(44124688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(44124688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  899): BroadcastReceiver::onReceive+
,D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  899): acquireWL(43e467a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=374516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(43e467a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  899): acquireWL(43e459d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(43e459d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(43e452d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(43e452d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(43e44910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=434516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(43e44910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  899): acquireWL(43e44308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(43e44308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(43e43688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=494516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  899): releaseWL(43e43688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(43e42b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(43e42b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(43e422d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=554516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(43e422d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(43e410f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  899): releaseWL(43e410f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(4384f410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(4384f410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  899): acquireWL(4378e298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=614516, Int=0
I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(4378e298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1217): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1217): sku_id=99
,D/ContactMessageStore( 1217): start background delete task...
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,E/PlayEventLogger( 3608): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3608): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3608): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3608): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{4249d808 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3608): [NET] getaddrinfo-,err=8
,D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3608): [NET] getaddrinfo-, 1
,D/libc    ( 3608): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3608): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3608): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1108): com.google.android.gms 2 13 4 12
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(42f93658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(42f93658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(42f6df80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=674515, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(42f6df80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(42e9ba38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(42e9ba38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(42e8b748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=734516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(42e8b748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(42e65670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(42e65670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(42e612b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=794516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(42e612b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(42e40f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(42e40f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(42e39a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=854516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(42e39a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(42e33ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(42e33ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(42e08848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=914516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(42e08848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 3608): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3608): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3608): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3608): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1108): com.google.android.gms (false,0)
D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3608): [NET] getaddrinfo-,err=8
D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3608): [NET] getaddrinfo-, 1
,D/libc    ( 3608): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3608): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3608): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{426fd0b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.google.android.gms 1 12 2 12
,D/PMS     (  899): acquireWL(43509d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(43509d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(42644570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=974515, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(42644570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(42dea638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
D/ConnectivityService(  899): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  899): sending alarm PendingIntent{426cf4b8: PendingIntentRecord{42d0e7b0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781188, Int=0
,D/ConnectivityService(  899): Done.
,D/ConnectivityService(  899): Setting timer for 720seconds
,I/ActivityManager(  899): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3990 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  899): sending alarm PendingIntent{42de0828: PendingIntentRecord{42e68810 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449595765869, Int=10800000
,V/AlarmManager(  899): sending alarm PendingIntent{428d88f0: PendingIntentRecord{429294e0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449596461433, Int=1800000
,V/AlarmManager(  899): sending alarm PendingIntent{42c46878: PendingIntentRecord{42cbf818 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449596486246, Int=900000
,V/AlarmManager(  899): sending alarm PendingIntent{43258b20: PendingIntentRecord{441686c8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449596556228, Int=0
,D/PMS     (  899): acquireWL(43195870): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1197 10028 null
,D/PMS     (  899): acquireWL(42d49360): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1197 10028 null
,W/ContextImpl( 3721): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  899): releaseWL(43195870): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 1197): Aggregate from 1449594756906 (log), 1449594661392 (data)
,D/PowerUsageService( 3721): call getInstance()
,D/SmartSyncUtils( 3721): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3721): MY_DEBUG = false
D/PMS     (  899): acquireWL(42cfc2c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3721 1000 null
D/PMS     (  899): releaseWL(42dea638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 3721): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3721): [updateNmRange] USERNIGHT_TIMESTART = 2, USERNIGHT_TIMEEND = 7, nStart = 2, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 3721): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3721): SettingOnTime = 1449640800000, randomSettingOnTime = 1449639184000
,D/SmartSyncScreenOnOffTimeReceiver( 3721): SettingOffTime = 1449622800000, randomSettingOffTime = 1449628685000
,D/SmartSyncScreenOnOffTimeReceiver( 3721): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3721): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3721): bNightModeTurnOffOnce = false
W/BatSI   (  899): Couldn't get kernel wake lock stats
D/PMS     (  899): releaseWL(42cfc2c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  899): getActiveNetworkInfo called by com.htc.aurora (3990/10047)
,W/EventLogAggregator( 1197): Unknown tag: install_package_attempt
W/EventLogAggregator( 1197): Unknown tag: snet
,W/EventLogAggregator( 1197): Unknown tag: snet_gcore
,D/PMS     (  899): releaseWL(42d49360): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  899): Couldn't get kernel wake lock stats
,W/BatSI   (  899): Couldn't get kernel wake lock stats
,W/BatSI   (  899): Couldn't get kernel wake lock stats
,D/Process (  899): killProcessQuiet, pid=3317
,D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  899): Killing 3317:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  899): Recipient 3317
,I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(4478a610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  899): releaseWL(4478a610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  899): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(4391ebc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1034516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(4391ebc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(43f652d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(43f652d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(443bf898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1094516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(443bf898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(42eafa40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): releaseWL(42eafa40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
,I/HtcPowerSaver(  899): >> updateStatus
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(444b3198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1154516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(444b3198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(42f51340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): releaseWL(42f51340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  899): acquireWL(44489c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1214516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(44489c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(448a4118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(448a4118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3608): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3608): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3608): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3608): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1108): com.google.android.gms (false,0)
D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3608): [NET] getaddrinfo-,err=8
D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3608): [NET] getaddrinfo-, 1
,D/libc    ( 3608): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3608): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3608): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{42528ea8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.google.android.gms 2 9 2 12
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(43f9ada8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(43f9ada8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(44360aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1274516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(44360aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(4493c070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): releaseWL(4493c070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(4493a9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
,D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
D/PMS     (  899): releaseWL(4493a9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  899): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(44856d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1334515, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(44856d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(448497d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(448497d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(4483fe70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(4483fe70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(447a1580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1394516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(447a1580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(44793ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/PMS     (  899): releaseWL(44793ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  899): acquireWL(444c23d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1454516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(444c23d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(444a6108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): releaseWL(444a6108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(43f98280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1514515, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(43f98280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,E/PlayEventLogger( 3608): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3608): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3608): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3608): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{427fbc98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3608): [NET] getaddrinfo-,err=8
D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3608): [NET] getaddrinfo-, 1
D/libc    ( 3608): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
I/RemoteViews.Performance( 1108): com.google.android.gms 2 14 4 12
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3608): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3608): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  899): acquireWL(43e402d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): releaseWL(43e402d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(43871820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1574515, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(43871820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(4384f410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
,D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  899): releaseWL(4384f410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
,I/HtcPowerSaver(  899): >> updateStatus
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(43520650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1634516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(43520650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(434376c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
D/PMS     (  899): releaseWL(434376c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(42f8ae28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1694516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(42f8ae28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(42f16ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  899): releaseWL(42f16ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  899): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  899): acquireWL(42c21928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1754515, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(42c21928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  899): Couldn't get kernel wake lock stats
,D/PMS     (  899): acquireWL(42671960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): releaseWL(42671960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
I/HtcPowerSaver(  899): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  899): acquireWL(42cdba50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1814516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(42cdba50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  899): acquireWL(42dbbfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{426cf4b8: PendingIntentRecord{42d0e7b0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1730766, Int=0
,V/AlarmManager(  899): sending alarm PendingIntent{42c6ade8: PendingIntentRecord{42dcbc18 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821002, Int=1800000
,D/ConnectivityService(  899): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  899): sending alarm PendingIntent{42660a70: PendingIntentRecord{42fb5f40 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1852015, Int=0
,D/PMS     (  899): acquireWL(42e5dbd8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 899 1000 null
,V/AlarmManager(  899): sending alarm PendingIntent{42c46878: PendingIntentRecord{42cbf818 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449597386246, Int=900000
,D/ConnectivityService(  899): Done.
,D/ConnectivityService(  899): Setting timer for 720seconds
,I/ProcessStatsService(  899): Prepared write state in 40ms
,D/PMS     (  899): releaseWL(42e5dbd8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ProcessStatsService(  899): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-14-00.bin
,W/ContextImpl( 3721): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  899): releaseWL(42dbbfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,W/BatSI   (  899): Couldn't get kernel wake lock stats
,W/BatSI   (  899): Couldn't get kernel wake lock stats
,W/BatSI   (  899): Couldn't get kernel wake lock stats
,W/BatSI   (  899): Couldn't get kernel wake lock stats
,D/PMS     (  899): acquireWL(43171890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  899): BroadcastReceiver::onReceive+
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  899): n_update end
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  899): BroadcastReceiver::onReceive-
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  899): updateBatteryInfo
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
D/PMS     (  899): releaseWL(43171890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  899): >> updateStatus
,I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,E/PlayEventLogger( 3608): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3608): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3608): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3608): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3608): [NET] getaddrinfo-,err=8
D/libc    ( 3608): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3608): [NET] getaddrinfo-, 1
D/libc    ( 3608): [NET] getaddrinfo_proxy+
D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{428f6058 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3608): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3608): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1108): com.google.android.gms 1 8 3 12
,D/ConnectivityService(  899): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  899): acquireWL(43f22ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  899): n_update end
D/UsbnetService(  899): BroadcastReceiver::onReceive+
D/UsbnetService(  899): onReceive BATTERY_CHANGED
D/UsbnetService(  899):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  899): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  899): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PMS     (  899): releaseWL(43f22ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  899): runPSCheck
D/HtcPowerSaver(  899): Checking...
,I/HtcPowerSaver(  899): >> updateStatus
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  899): killProcessQuiet, pid=3646
I/ActivityManager(  899): Killing 3646:com.google.android.apps.plus/u0a160 (adj 15): empty for 1800s
I/HtcPowerSaver(  899): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  899): << updateStatus
D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
,D/Process (  899): killProcessQuiet, pid=3837
,D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/Process (  899): killProcessQuiet, pid=3783
,D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  899): Killing 3837:com.htc.providers.settings:remote/u0a17 (adj 15): empty for 1800s
I/ActivityManager(  899): Killing 3783:com.htc.cs.dm/u0a98 (adj 15): empty for 1800s
,D/Process (  899): killProcessQuiet, pid=3820
,D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
,D/Process (  899): killProcessQuiet, pid=3798
,D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  899): Killing 3820:com.htc.backup/1000 (adj 15): empty for 1800s
I/ActivityManager(  899): Killing 3798:com.google.android.apps.docs/u0a100 (adj 15): empty for 1800s
,D/Process (  899): killProcessQuiet, pid=3763
,D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  899): Killing 3763:com.google.android.partnersetup/u0a31 (adj 15): empty for 1801s
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  899): Recipient 3837
I/ActivityManager(  899): Recipient 3646
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  899): Recipient 3820
,I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  899): Recipient 3783
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  899): Recipient 3798
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  899): Recipient 3763
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AppWidgetServiceImpl(  899): updateAppWidget failed! callbacks null
,D/PMS     (  899): acquireWL(4409d0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 899 1000 WorkSource{1000}
,V/AlarmManager(  899): sending alarm PendingIntent{42697458: PendingIntentRecord{426954a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1874516, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  899): releaseWL(4409d0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4029): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4029): ====startRecUseTime====
D/htc.customization.log.level( 4029):  is 
W/CustomizationLogLevel( 4029): Level value is invalid, use default level 2
D/CustomizationManager( 4029):  Read ACC file spent 0.090 (s)
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4029): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4029): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4029): Parsing tag category name = system
I/CustomizationCIDLoader( 4029): Parsing tag category name = application
I/CustomizationCIDLoader( 4029): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4029): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4029): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4029): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4029): Parsing tag category name = Settings
D/CustomizationManager( 4029):  Read CID file spent 0.136 (s)
D/CustomizationManager( 4029):  All configurations done spent 0.137 (s)
W/HtcNativeFlag( 4029): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4029): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4029): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4029): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  899): deletePackageAsUser: pkg=com.test.thalitest, pid=4029, uid=2000 user=0
I/ActivityManager(  899): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  899): killProcessQuiet, pid=3887
D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  899): Killing 3887:com.test.thalitest/u0a348 (adj 15): stop com.test.thalitest
W/asset   (  899): Copying FileAsset 0x6880fc50 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  899): Skipping PackageSetting{42b38fd0 com.example.hello/10355} due to missing metadata
I/ActivityManager(  899): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1540): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1540): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1773): Unregistering com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
E/acms    ( 1773): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
I/Launcher( 1247): Deferring update until onResume
D/Launcher( 1247): waitUntilResume // bindAppsRemoved
W/GeofencerStateMachine( 1393): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 1275): Cleaning up data for package: com.test.thalitest
D/PMS     (  899): acquireWL(448f5520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1393 10028 null
D/PMS     (  899): releaseWL(448f5520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1305): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1305): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PackageBroadcastService( 1197): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  899):   Action: "android.intent.action.SENDTO"
I/PackageManager(  899):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  899):   Scheme: "sms"
I/PackageManager(  899): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/AccTypeManager( 1305): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  899): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  899):   Action: "android.intent.action.SENDTO"
I/PackageManager(  899):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  899):   Scheme: "smsto"
I/ActivityManager(  899): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4043 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  899):   Action: "android.intent.action.SENDTO"
I/PackageManager(  899):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  899):   Scheme: "mms"
I/PackageManager(  899): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  899):   Action: "android.intent.action.SENDTO"
I/PackageManager(  899):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  899):   Scheme: "mmsto"
I/PackageManager(  899): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/Parcel  ( 1230): Reading a NULL string not supported here.
I/ActivityManager(  899): Delaying start of: ServiceRecord{43e81558 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  899):   Action: "android.intent.action.SENDTO"
I/PackageManager(  899):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  899):   Scheme: "sms"
I/PackageManager(  899): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/MultiDex( 4043): install
I/MultiDex( 4043): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/ExternalAccountType( 1305): Unsupported attribute readOnly
I/MultiDex( 4043): loading existing secondary dex files
I/MultiDex( 4043): load found 1 secondary dex files
I/PeopleContactsSync( 1197): CP2 sync disabled
I/MultiDex( 4043): install done
D/PMS     (  899): acquireWL(43c6acf0): PARTIAL_WAKE_LOCK  Icing 0x1 1197 10028 null
I/PackageManager(  899):   Action: "android.intent.action.SENDTO"
I/PackageManager(  899):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  899):   Scheme: "smsto"
I/PackageManager(  899): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/Icing   ( 1197): doRemovePackageData com.test.thalitest
I/PackageManager(  899):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1197, uid=10028, userID:0
D/PMS     (  899): releaseWL(43c6acf0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  899):   Action: "android.intent.action.SENDTO"
I/PackageManager(  899):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  899):   Scheme: "mms"
I/PackageManager(  899): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/ActivityManager(  899): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4063 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4043): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/PackageManager(  899):   Action: "android.intent.action.SENDTO"
I/PackageManager(  899):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  899):   Scheme: "mmsto"
I/PackageManager(  899): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  899): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4063): install
I/MultiDex( 4063): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4063): loading existing secondary dex files
I/MultiDex( 4063): load found 1 secondary dex files
I/MultiDex( 4063): install done
I/ActivityManager(  899): Resuming delayed broadcast
I/ProviderInstaller( 4063): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1376): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1376): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1376): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9c4af0
I/ActivityManager(  899): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
W/[PluginManager]RegisterService( 1376): provider may killed!
W/[PluginManager]RegisterService( 1376): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1376): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1376): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1376): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1376): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1376): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1376): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1376): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1376): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1376): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1376): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1376): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1376): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1376): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1376): handle notify Blinkfeed plugin client changed
I/ActivityManager(  899): Resuming delayed broadcast
D/Process (  899): killProcessQuiet, pid=3863
D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  899): Killing 3863:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1812s
D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  899): Recipient 3863
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/IcingCorporaProvider( 2662): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  899): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4083 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4043): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4043): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4043): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4043): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4043): threadid=12: thread exiting with uncaught exception (group=0x41fb4e30)
E/AndroidRuntime( 4043): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4043): Process: com.google.android.gms.drive, PID: 4043
E/AndroidRuntime( 4043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4043): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4043): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4043): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4043): 	at ctn.run(SourceFile:985)
E/ActivityManager(  899): App crashed! Process: com.google.android.gms.drive
D/Process ( 4043): killProcess, pid=4043
D/Process ( 4043): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2662): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2662): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x639982c8
W/dalvikvm( 2662): threadid=14: thread exiting with uncaught exception (group=0x41fb4e30)
E/DropBoxManagerService(  899): Can't write: system_app_crash
E/DropBoxManagerService(  899): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  899): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  899): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  899): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  899): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  899): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  899): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  899): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  899): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  899): 	... 5 more
E/AndroidRuntime( 2662): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2662): Process: com.google.android.googlequicksearchbox:search, PID: 2662
E/AndroidRuntime( 2662): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2662): 	at cid.d(PG:186)
E/AndroidRuntime( 2662): 	at clo.g(PG:594)
E/AndroidRuntime( 2662): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2662): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2662): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2662): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2662): 	at clr.tL(PG:827)
E/AndroidRuntime( 2662): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2662): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2662): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2662): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2662): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2662): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  899): Recipient 4043
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  899): Process com.google.android.gms.drive (pid 4043) has died.
W/ActivityManager(  899): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
E/ActivityManager(  899): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2662): killProcess, pid=2662
D/Process ( 2662): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  899): Can't write: system_app_crash
E/DropBoxManagerService(  899): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  899): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  899): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  899): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  899): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  899): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  899): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  899): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  899): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  899): 	... 5 more
I/InputMethodManagerService(  899): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  899): Recipient 2662
D/MediaRouterService(  899): Client com.google.android.googlequicksearchbox (pid 2662): Died!
D/WifiService(  899): Client connection lost with reason: 4
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  899): Process com.google.android.googlequicksearchbox:search (pid 2662) has died.
W/ActivityManager(  899): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  899): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
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
W/dalvikvm( 4083): threadid=11: thread exiting with uncaught exception (group=0x41fb4e30)
E/ActivityManager(  899): App crashed! Process: com.google.android.apps.docs
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
E/DropBoxManagerService(  899): Can't write: system_app_crash
E/DropBoxManagerService(  899): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  899): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  899): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  899): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  899): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  899): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  899): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  899): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  899): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  899): 	... 5 more
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
E/SQLiteDatabase( 4083): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
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
E/SQLiteOpenHelper( 4083): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
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
D/Process ( 4083): killProcess, pid=4083
D/Process ( 4083): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  899): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4102 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  899): Recipient 4083
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  899): killProcessQuiet, pid=3287
D/Process (  899): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  899): Killing 3287:com.android.settings/1000 (adj 15): empty for 1806s
I/ActivityManager(  899): Process com.google.android.apps.docs (pid 4083) has died.
F/ProcessStats(  899): Starting service ServiceState{43694650 com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService pkg=com.google.android.googlequicksearchbox proc=43694650} without owner
I/ActivityManager(  899): Recipient 3287
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ErrorReport(  899): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  899): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  899): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1449597462767.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  899): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  899): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  899): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  899): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  899): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  899): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  899): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  899): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  899): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  899): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  899): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  899): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  899): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  899): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4131)
E/ErrorReport(  899): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
E/ErrorReport(  899): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
E/ErrorReport(  899): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  899): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  899): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  899): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  899): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  899): 	... 18 more
W/ContextImpl( 4102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/TrimMemoryManager( 1247): [trimMemory] 5
E/SQLiteDatabase( 4102): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4102): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4102): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4102): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4102): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4102): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4102): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4102): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4102): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4102): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4102): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4102): threadid=10: thread exiting with uncaught exception (group=0x41fb4e30)
I/ActivityManager(  899): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4116 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4102): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4102): Process: com.android.keychain, PID: 4102
E/AndroidRuntime( 4102): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4102): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4102): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4102): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4102): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4102): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4102): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4102): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4102): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4102): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  899): App crashed! Process: com.android.keychain
D/ErrorReport(  899): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4116): getInstance(Context context)
E/ErrorReport(  899): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  899): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449597462983.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  899): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  899): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  899): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  899): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  899): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  899): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  899): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  899): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  899): 	... 4 more
D/Process ( 4102): killProcess, pid=4102
D/Process ( 4102): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/PackageManager(  899): Unable to load service info ResolveInfo{43e400e8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  899): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  899): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  899): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  899): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  899): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  899): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  899): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  899): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  899): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  899): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  899): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  899): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  899): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  899): 	at dalvik.system.NativeStart.main(Native Method)
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@42476f38 +
I/Prism.WidgetManager( 1247): onLoadItems() +
I/ActivityManager(  899): Recipient 4102
I/DisplayManagerService(  899): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4116): getInstance(Context context)
I/ActivityManager(  899): Process com.android.keychain (pid 4102) has died.
W/ActivityManager(  899): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10380ms
D/AppTag  ( 4116): onCreate()
I/ActivityManager(  899): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4131 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}

```
