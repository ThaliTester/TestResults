#### Test 564496605d11e75_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  900): acquireWL(424f5978): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  900): releaseWL(424f5978): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  900): acquireWL(41c32fe8): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
D/PMS     (  900): releaseWL(41c32fe8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  900): acquireWL(43083b80): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
D/PMS     (  900): releaseWL(43083b80): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  900): acquireWL(4216bbd0): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
D/PMS     (  900): releaseWL(4216bbd0): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of /dev/log/main
E/cutils-trace( 3855): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3855): ====startRecUseTime====
D/htc.customization.log.level( 3855):  is 
W/CustomizationLogLevel( 3855): Level value is invalid, use default level 2
D/CustomizationManager( 3855):  Read ACC file spent 0.068 (s)
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
D/CustomizationManager( 3855):  Read CID file spent 0.114 (s)
D/CustomizationManager( 3855):  All configurations done spent 0.114 (s)
W/HtcNativeFlag( 3855): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3855): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3855): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3855): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  900): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  900): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  900): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  900): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  900): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  900): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  900): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3855
D/PMS     (  900): acquireHCC(41ca89d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 900 1000 null
D/PMS     (  900): acquireHCC(42220e08): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 900 1000 null
W/asset   (  900): Copying FileAsset 0x6762d120 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  900): @test_code: getHtcIntentFlag: 0 obj: 1104957320
I/FeedHostManager( 1245): [onPause]
I/FeedProviderManager( 1245): onPause
D/PMS     (  900): acquireWL(4258dfa8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 900 1000 null
I/FeedHostManager( 1245): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bb2518
I/SocialFeedProvider( 1245): +onPause
I/SocialFeedProvider( 1245): -onPause
I/ActivityManager(  900): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3868 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1245): [trimMemory] 20
W/asset   ( 3868): Copying FileAsset 0x5c70a428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3868): Binding Chromium to main looper Looper (main, tid 1) {41a8c788}
I/LibraryLoader( 3868): Expected native library version number "",actual native library version number ""
I/chromium( 3868): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3868): Initializing chromium process, renderers=0
D/PMS     (  900): acquireWL(422043d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  900): acquireWL(420effe0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  900): java.lang.Throwable: stack dump
D/BluetoothManagerService(  900): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41d70f10:true
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3868): 1101668800: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  900): releaseWL(422043d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3868): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3868): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3868): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3868): Local Branch: 
I/Adreno-EGL( 3868): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3868): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3868):                  aa63bbd948f41d15fc72f585e
W/chromium( 3868): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3868): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3868): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3868): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3868): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3868): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3868): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3868): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3868): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3868): CordovaWebView is running on device made by: HTC
,W/AwContents( 3868): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  900): Disable input method client, pid=1245
,W/ResourceType( 3868): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3868): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ad3748, mServedView=org.apache.cordova.engine.SystemWebView{41a994d8 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  900): Enable input method client, pid=3868
W/XT9_C   ( 1183): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1183): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3868): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  900): Displayed com.test.thalitest/.MainActivity: +291ms
,D/PMS     (  900): releaseWL(4258dfa8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3868): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3868): JniHelper::setJavaVM(0x41561048), pthread_self() = 1663012576
,I/chromium( 3868): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 11.938MB for 42652-byte allocation
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 12.027MB for 95956-byte allocation
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 12.107MB for 143930-byte allocation
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 12.220MB for 215890-byte allocation
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 12.396MB for 323830-byte allocation
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 12.667MB for 485740-byte allocation
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 13.649MB for 1092904-byte allocation
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 14.586MB for 1639352-byte allocation
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 15.833MB for 2459024-byte allocation
,W/CpuWake (  900): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  900): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  900): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  900): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  900): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  900): <<release mCpuPerf_Freq wakelock
D/PMS     (  900): releaseHCC(41ca89d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  900): releaseHCC(42220e08): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3868): Grow heap (frag case) to 17.920MB for 3688532-byte allocation
,W/jxcore-log( 3868): Initializing JXcore engine
,W/jxcore-log( 3868): JXcore engine is ready
,W/jxcore-log( 3868): Starting JXcore engine
,W/jxcore-log( 3868): Platform android
W/jxcore-log( 3868): 
,W/jxcore-log( 3868): Process ARCH arm
W/jxcore-log( 3868): 
,I/jxcore-log( 3868): JXcore Cordova bridge is ready!
I/jxcore-log( 3868): 
,W/jxcore-log( 3868): JXcore engine is started
,E/jxcore  ( 3868): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3868): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3868): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  900): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3868): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  900): acquireWL(41f8ceb8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 900 1000 null
,I/FeedHostManager( 1245): [onResume]
,I/FeedProviderManager( 1245): onResume
I/SocialFeedProvider( 1245): +onResume
,I/ConnectivityHelper( 1245): [getCurrentConnectionType] no network connection
I/SocialFeedProvider( 1245): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1245): -onResume
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.launcher (1245/10075)
,I/InputMethodManagerService(  900): Disable input method client, pid=3868
,W/IInputConnectionWrapper( 3868): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  900): Enable input method client, pid=1245
,D/PMS     (  900): releaseWL(41f8ceb8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  900): killProcessQuiet, pid=3407
,I/ActivityManager(  900): Killing 3407:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/PMS     (  900): releaseWL(420effe0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/libEGL  ( 3868): call to OpenGL ES API with no current context (logged once per thread)
I/ActivityManager(  900): Recipient 3407
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  900): Client com.google.android.music (pid 3407): Died!
,I/ActivityManager(  900): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3917 uid=10077 gids={50077}
,D/PMS     (  900): acquireWL(42094c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10077}
,V/AlarmManager(  900): sending alarm PendingIntent{4255db60: PendingIntentRecord{42588cf8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453807584297, Int=60000
,D/PMS     (  900): releaseWL(42094c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3917): SMSBackupAgentService started
,D/SMSBackup( 3917): Checking restore status
,D/SMSBackup( 3917): Restore complete
,D/SMSBackup( 3917): cancelCheckAlarm
,D/SMSBackup( 3917): SMSBackupAgentService completed: completed in 0.0 seconds
,I/ActivityManager(  900): Killing 3692:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  900): killProcessQuiet, pid=3692
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  900): Recipient 3692
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  900): Client connection lost with reason: 4
,I/SensorManager(  900): mEventCount = 750
,I/PMS     (  900): Going to sleep due to screen timeout...
,W/PMS     (  900): mWirelessDisplayManager is null
I/SensorManager(  900): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4204b3e8
W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  900): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  900): Screen File Receiver; callOnGoing: false, Screen On: false
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 2
W/SensorService(  900): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  900): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  900): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4204b3e8, eanble = 0, strlen(mName) = 59
D/WirelessDisplayService(  900): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  900): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4231bd00
W/SensorService(  900): Listener[1] = com.htc.smartdim.sensor_eye@424c9970
,W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  900): Couldn't get kernel wake lock stats
V/LightsService(  900): setLight #2: color=#0
D/qdlights(  900): set_light_buttons_func: on=0 brightness=0
V/LightsService(  900): setLight #0: color=#0
,D/SurfaceControl(  900): Excessive delay in blankDisplay() while turning screen off: 418ms
D/PMS     (  900): nativeSetInteractive:false
D/PMS     (  900): nativeSetInteractive:false done
D/PMS     (  900): nativeSetAutoSuspend:true
D/PMS     (  900): nativeSetAutoSuspend:true done
D/HABCtrl (  900): TPE algorithm. remove timeout.
D/NfcService( 1231): ScreenObserver: OFF
D/NfcService( 1231): applyRouting - 0
,D/NfcService( 1231): applyRouting -2
,V/KeyguardServiceDelegate(  900): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43d931d0)
D/PMS     (  900): OOBE c monitor 11
I/InputManager(  900): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  900): screenObserver, isScreenOn=false
I/InputMethodManagerService(  900): Disable input method client, pid=1245
D/PMS     (  900): acquireWL(42b498e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
D/PMN     (  900): wakingUp
D/PMS     (  900): releaseWL(42b498e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  900): **** SHOWN CALLED ****
I/WindowManager(  900): No lock screen! windowToken=null
D/PMN     (  900): onScreenOn
D/PMS     (  900): acquireWL(438b3a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/IntentController( 1104): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/BatteryService(  900): n_update end
D/PMS     (  900): releaseWL(438b3a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/MtpService( 2206): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2206): [MTP][onReceive]-
,D/NfcService( 1231): applyRouting - 0
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
,D/NfcService( 1231): applyRouting -2
D/WirelessDisplayService(  900): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  900): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  900): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/AutoSetting( 1385): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  900): ACTION_SCREEN_ON
I/AlarmManager(  900): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  900): [AlarmQueuing] done recovering
I/AlarmManager(  900): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  900): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  900): acquireWL(4312b378): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
D/PMS     (  900): releaseWL(4312b378): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
,D/WirelessDisplayService(  900): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  900): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  900): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0,
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/TetherSettings( 3342): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3342): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3342): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3342): Cust_ConnectToPC   : spcsc>false
D/        ( 3342): Cust_ConnectToPC   : IPT>true
D/        ( 3342): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3342): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3342): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 3342): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3342): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1385): service - onCreate()
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,D/WifiDataStallTracker(  900): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  900): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  900):    returned false
,I/PSReceiver( 3342): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1385): service - AddressCache: using context: com.htc.Weather
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,W/ContextImpl( 3342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3342): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3342): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3342):  defaultType:0
,I/ClockThread( 1104): stop update clock
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/LocationManagerService(  900): request 424af568 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  900): provider request: passive ProviderRequest[ON interval=0]
,D/WirelessDisplayService(  900): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  900): updateScreenOn: false
W/ActivityManager(  900): Disable JIT of com.htc.bgp
W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  900): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3939 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  900): acquireWL(43121d88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
D/PMS     (  900): releaseWL(43121d88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  900): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4231bd00
W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  900): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 2
W/SensorService(  900): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  900): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  900): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4231bd00, eanble = 0, strlen(mName) = 91
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  900): Listener[0] = com.htc.smartdim.sensor_eye@424c9970
,W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  900): goingToSleep
D/PMS     (  900): acquireWL(43bb67c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 900 1000 null
,I/FeedHostManager( 1245): [onPause]
,I/FeedProviderManager( 1245): onPause
I/FeedHostManager( 1245): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bb2518
I/SocialFeedProvider( 1245): +onPause
I/SocialFeedProvider( 1245): -onPause
D/WifiDataStallTracker(  900): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  900): stopDataStallAlarm: current tag=20153 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  900): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  900):    returned false
D/AlarmManager(  900): ACTION_SCREEN_OFF
I/AlarmManager(  900): [AlarmQueuing] screen off now: 
I/AlarmManager(  900): [AlarmQueuing] data connection: true
I/AlarmManager(  900): [AlarmQueuing] wifi connection: false
D/PMS     (  900): acquireWL(42fed4b0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 900 1000 null
D/PMS     (  900): releaseWL(42fed4b0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  900): releaseWL(43bb67c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  900): updateScreenOn: false
,I/CalendarProvider2( 3939): Created com.android.providers.calendar.CalendarAlarmManager@41ac7e10(com.android.providers.calendar.HtcCalendarProvider@41ab0198)
,D/CalendarProvider2( 3939): wait start:true
,D/CalendarProvider2( 3939): wait end:false
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
W/ContextImpl( 3713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1550): [EventService] getTotalRam: 1873 Mb
D/PMS     (  900): acquireWL(43d9cd40): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3713 1000 null
D/PMS     (  900): acquireWL(440fbea0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
,D/SmartSyncUtils( 3713): isEpsOn(), nState = 0
D/AutoSetting( 1385): service - mHandler: cancel location update
,D/AutoSetting( 1385): service -           changes count: 0
D/PMS     (  900): releaseWL(440fbea0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  900): releaseWL(43d9cd40): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 3713): getMobilePolicyEnabled, result = true
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3713): isEpsOn(), nState = 0
D/SmartSyncUtils( 3713): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3713): getMobilePolicyEnabled, result = true
D/WifiService(  900): New client listening to asynchronous messages
,I/SensorManager(  900): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424c9970
W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  900): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 1
W/SensorService(  900): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  900): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424c9970, eanble = 0, strlen(mName) = 36
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  900): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 0
W/SensorService(  900): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424c9970, eanble = 0, strlen(mName) = 36
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  900): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424c9970
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  900): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42506fc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  900): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42506fc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  900): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  900): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  900): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  900): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  900): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  900): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  900): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  900): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  900): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  900): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  900): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  900): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  900): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  900): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  900): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  900): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  900): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 3939): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3939): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3819): ---------------------------------------------------
,D/ProviderChangeReceiver( 3819): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3819): start to updateAlertNotification!
,D/AlertService( 3819): No fired or scheduled alerts
,D/HtcAlertUtils( 3819): -- cancelReminderNotification --
,D/HtcAlertUtils( 3819): broadcastExistReminder!
W/ContextImpl( 3833): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  900): killProcessQuiet, pid=3429
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3429:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 3429
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{42430698 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  900): acquireWL(431145a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
,D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PMS     (  900): releaseWL(431145a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  900): acquireWL(4412b190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=139265, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4412b190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1385): service - handleMessage() stop self
,D/AutoSetting( 1385): service - handleMessage() quit looper
,D/AutoSetting( 1385): service - onDestroy() END
,D/Process (  900): killProcessQuiet, pid=3388
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3388:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 3388
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  900): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  900): [handleMessage] DOWNLOAD_XTRA_DATA
D/PMS     (  900): acquireWL(43cea928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{4231b780: PendingIntentRecord{4231b748 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141546, Int=0
D/PMS     (  900): acquireWL(44115300): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
V/AlarmManager(  900): sending alarm PendingIntent{4207b458: PendingIntentRecord{41ef4310 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142312, Int=0
,D/GpsLocationProvider(  900): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  900): releaseWL(44115300): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
V/AlarmManager(  900): sending alarm PendingIntent{42158180: PendingIntentRecord{422836c0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145661, Int=0
,D/libc    (  900): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-,err=8
,D/libc    (  900): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
,D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  900): [NET] getaddrinfo_proxy-,
D/PMS     (  900): releaseWL(43cea928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  900): acquireWL(43da3d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43da3d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  900): acquireWL(4259a048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  900): updateBatteryInfo
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): releaseWL(4259a048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(4412d940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199265, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4412d940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  900): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-,err=8
,D/libc    (  900): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/PMS     (  900): acquireWL(4316c578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
V/AlarmManager(  900): sending alarm PendingIntent{42158180: PendingIntentRecord{422836c0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=205684, Int=0
D/libc    (  900): [NET] getaddrinfo-, 1
D/libc    (  900): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  900): [NET] getaddrinfo_proxy-
D/PMS     (  900): releaseWL(4316c578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43c58bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43c58bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  900): updateBatteryInfo
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): onReceive BATTERY_CHANGED
,D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  900): acquireWL(43cd50c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
I/BatteryService(  900): n_update end
D/HtcPowerSaver(  900): updateBatteryInfo
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,D/PMS     (  900): releaseWL(43cd50c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43c51f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259265, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43c51f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(441771b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(441771b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(43147208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=319264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43147208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1550): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1550): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,E/PlayEventLogger( 3604): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3604): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3604): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41a954f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1104): com.google.android.gms 1 10 3 12
,D/libc    ( 3604): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3604): [NET] getaddrinfo-,err=8
D/libc    ( 3604): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3604): [NET] getaddrinfo-, 1
,D/libc    ( 3604): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3604): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3604): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  900): acquireWL(43c24820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43c24820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  900): updateBatteryInfo
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  900): acquireWL(4325af38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4325af38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(43d44e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43d44e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(44189868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=439264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(44189868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  900): acquireWL(43136cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43136cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  900): acquireWL(433585a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=499264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(433585a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(43cdef30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43cdef30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42c9d1c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=559264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42c9d1c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(4329ddf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4329ddf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  900): acquireWL(43b97fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=619264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43b97fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1217): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1217): sku_id=99
,D/ContactMessageStore( 1217): start background delete task...
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1550): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1550): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,E/PlayEventLogger( 3604): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3604): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3604): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41ab7e50 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1104): com.google.android.gms 3 14 6 12
D/libc    ( 3604): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3604): [NET] getaddrinfo-,err=8
D/libc    ( 3604): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3604): [NET] getaddrinfo-, 1
,D/libc    ( 3604): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3604): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3604): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  900): acquireWL(44746ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(44746ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(44736598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=679265, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(44736598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(44170c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(44170c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(44156900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=739264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(44156900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  900): acquireWL(44129ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(44129ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(44127ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=799264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(44127ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(440d22b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(440d22b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(44075720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=859264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(44075720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  900): acquireWL(43d9b0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43d9b0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(43d14630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=919264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43d14630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1550): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1550): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3604): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3604): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3604): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 3604): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41b19870 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3604): [NET] getaddrinfo-,err=8
,D/libc    ( 3604): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3604): [NET] getaddrinfo-, 1
,D/libc    ( 3604): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3604): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3604): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1104): com.google.android.gms 1 21 7 12
,D/PMS     (  900): acquireWL(43317478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43317478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(432c8438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=979264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(432c8438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/ConnectivityService(  900): Sampling interval elapsed, updating statistics ..
,D/PMS     (  900): acquireWL(431c35c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41cdee28: PendingIntentRecord{423c3f20 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782904, Int=0
,D/ConnectivityService(  900): Done.
,D/ConnectivityService(  900): Setting timer for 720seconds
,I/ActivityManager(  900): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3984 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  900): sending alarm PendingIntent{4230d578: PendingIntentRecord{4230d4f8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453807701264, Int=10800000
,V/AlarmManager(  900): sending alarm PendingIntent{42378148: PendingIntentRecord{42465628 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453808037433, Int=1800000
V/AlarmManager(  900): sending alarm PendingIntent{41d56100: PendingIntentRecord{42547c40 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453808421660, Int=900000
,V/AlarmManager(  900): sending alarm PendingIntent{424f7328: PendingIntentRecord{42d6eb48 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453808493130, Int=0
,D/PMS     (  900): acquireWL(4306c818): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1200 10028 null
,D/PMS     (  900): acquireWL(430602b0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1200 10028 null
,W/ContextImpl( 3713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/EventLogService( 1200): Aggregate from 1453806237253 (log), 1453806237253 (data)
,D/PowerUsageService( 3713): call getInstance()
,D/SmartSyncUtils( 3713): isEpsOn(), nState = 0
D/PMS     (  900): releaseWL(4306c818): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/PowerUsageList:PowerUsageHelper( 3713): MY_DEBUG = false
,D/PMS     (  900): releaseWL(431c35c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43055ca0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3713 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 3713): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 3713): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3713): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3713): SettingOnTime = 1453856400000, randomSettingOnTime = 1453855148000
,D/SmartSyncScreenOnOffTimeReceiver( 3713): SettingOffTime = 1453852800000, randomSettingOffTime = 1453853360000
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.aurora (3984/10047),
D/SmartSyncScreenOnOffTimeReceiver( 3713): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3713): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3713): bNightModeTurnOffOnce = false
W/BatSI   (  900): Couldn't get kernel wake lock stats
D/PMS     (  900): releaseWL(43055ca0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/EventLogAggregator( 1200): Unknown tag: install_package_attempt
W/EventLogAggregator( 1200): Unknown tag: snet
,W/EventLogAggregator( 1200): Unknown tag: snet_gcore
,D/PMS     (  900): releaseWL(430602b0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,D/Process (  900): killProcessQuiet, pid=3732
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3732:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 3732
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  900): acquireWL(424f5108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(424f5108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(438a9738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1039264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(438a9738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42590a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42590a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42c839f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1099264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42c839f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  900): acquireWL(440909d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/PMS     (  900): releaseWL(440909d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42608b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1159264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42608b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43d1d138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43d1d138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  900): acquireWL(430ba968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1219265, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(430ba968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1550): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1550): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,E/PlayEventLogger( 3604): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3604): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3604): 	at dalvik.system.NativeStart.run(Native Method)
D/libc    ( 3604): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41e0b588 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3604): [NET] getaddrinfo-,err=8
D/libc    ( 3604): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3604): [NET] getaddrinfo-, 1
,D/libc    ( 3604): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3604): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3604): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1104): com.google.android.gms 5 10 2 12
,D/PMS     (  900): acquireWL(43a15b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43a15b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(43068728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41b0a668: PendingIntentRecord{41b08c70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1279264, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43068728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(426164f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(426164f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1104): closing low battery warning: level=100
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
,D/PMS     (  900): runPSCheck
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4003): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4003): ====startRecUseTime====
D/htc.customization.log.level( 4003):  is 
W/CustomizationLogLevel( 4003): Level value is invalid, use default level 2
D/CustomizationManager( 4003):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4003): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4003): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4003): Parsing tag category name = system
I/CustomizationCIDLoader( 4003): Parsing tag category name = application
I/CustomizationCIDLoader( 4003): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4003): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4003): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4003): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4003): Parsing tag category name = Settings
D/CustomizationManager( 4003):  Read CID file spent 0.156 (s)
D/CustomizationManager( 4003):  All configurations done spent 0.156 (s)
W/HtcNativeFlag( 4003): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4003): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4003): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4003): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  900): deletePackageAsUser: pkg=com.test.thalitest, pid=4003, uid=2000 user=0
I/ActivityManager(  900): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  900): killProcessQuiet, pid=3868
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  900): Killing 3868:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
W/asset   (  900): Copying FileAsset 0x62b19cb0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1245): Deferring update until onResume
D/Launcher( 1245): waitUntilResume // bindAppsRemoved
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1550): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1550): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1550): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1763): Unregistering com.test.thalitest
E/acms    ( 1763): Could not unregister removed application com.test.thalitest
W/AccTypeManager( 1303): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1303): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  900): acquireWL(4418e918): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
W/GeofencerStateMachine( 1402): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 1273): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PMS     (  900): releaseWL(4418e918): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "sms"
D/PackageBroadcastService( 1200): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "smsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/ActivityManager(  900): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4017 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/AccTypeManager( 1303): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mmsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "sms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/Parcel  ( 1231): Reading a NULL string not supported here.
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "smsto"
E/ExternalAccountType( 1303): Unsupported attribute readOnly
I/MultiDex( 4017): install
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mms"
I/MultiDex( 4017): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mmsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/MultiDex( 4017): loading existing secondary dex files
I/MultiDex( 4017): load found 1 secondary dex files
I/MultiDex( 4017): install done
I/ActivityManager(  900): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4034 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1200): CP2 sync disabled
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1200, uid=10028, userID:0
D/PMS     (  900): acquireWL(42117ed8): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
I/Icing   ( 1200): doRemovePackageData com.test.thalitest
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1200): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1200): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1200): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1200): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1200): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1200): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1200): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1200): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1200): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1200): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1200): Writing status failed
I/ProviderInstaller( 4017): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/Icing   ( 1200): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp
E/Icing   ( 1200): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/Icing   ( 1200): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/Icing   ( 1200): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/Icing   ( 1200): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Icing   ( 1200): 	at ghk.a(SourceFile:192)
E/Icing   ( 1200): 	at gga.n(SourceFile:1223)
E/Icing   ( 1200): 	at gdz.q(SourceFile:2247)
E/Icing   ( 1200): 	at ger.run(SourceFile:301)
E/Icing   ( 1200): 	at ght.a(SourceFile:259)
E/Icing   ( 1200): 	at ghz.d(SourceFile:73)
E/Icing   ( 1200): 	at ghu.run(SourceFile:250)
E/Icing   ( 1200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 1200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 1200): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 1200): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/Icing   ( 1200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 1200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 1200): 	at ghy.run(SourceFile:50)
E/Icing   ( 1200): 	at java.lang.Thread.run(Thread.java:864)
E/Icing   ( 1200): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/Icing   ( 1200): 	at libcore.io.Posix.open(Native Method)
E/Icing   ( 1200): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/Icing   ( 1200): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/Icing   ( 1200): 	... 17 more
D/PMS     (  900): releaseWL(42117ed8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  900): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4034): install
I/MultiDex( 4034): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4034): loading existing secondary dex files
I/MultiDex( 4034): load found 1 secondary dex files
I/MultiDex( 4034): install done
I/ProviderInstaller( 4034): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  900): Resuming delayed broadcast
E/SQLiteDatabase( 1200): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1200): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1200): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1200): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1200): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1200): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1200): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1200): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1200): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1200): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1200): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1200): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1200): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1183): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/ClearPendingStateOp( 1200): Runtime exception while performing operation
E/ClearPendingStateOp( 1200): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1200): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1200): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1200): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1200): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1200): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1200): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1200): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1200): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1200): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1200): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1200): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1200): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1200): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1200): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1200): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1200): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1200): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1200): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1200): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1200): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1200): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1200): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1200): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  900): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1385): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1385): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1385): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9b19d0
W/[PluginManager]RegisterService( 1385): provider may killed!
W/[PluginManager]RegisterService( 1385): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1385): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1385): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1385): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1385): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1385): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1385): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1385): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1385): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1385): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1385): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1385): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1385): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1385): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1385): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1385): handle notify Blinkfeed plugin client changed
I/ActivityManager(  900): Resuming delayed broadcast
E/DropBoxManagerService(  900): Can't write: system_app_wtf
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
D/Prism.PackageStateRece_( 1245): action: android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  900): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/IcingCorporaProvider( 2652): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteDatabase( 4017): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4017): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4017): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4017): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4017): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4017): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4017): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4017): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4017): threadid=12: thread exiting with uncaught exception (group=0x41659e30)
E/AndroidRuntime( 4017): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4017): Process: com.google.android.gms.drive, PID: 4017
E/AndroidRuntime( 4017): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4017): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4017): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4017): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4017): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4017): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4017): 	at ctn.run(SourceFile:985)
E/ActivityManager(  900): App crashed! Process: com.google.android.gms.drive
I/ActivityManager(  900): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4059 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/DropBoxManagerService(  900): Can't write: system_app_crash
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
D/Process ( 4017): killProcess, pid=4017
D/Process ( 4017): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2652): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2652): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca0b1c0
W/dalvikvm( 2652): threadid=15: thread exiting with uncaught exception (group=0x41659e30)
E/AndroidRuntime( 2652): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2652): Process: com.google.android.googlequicksearchbox:search, PID: 2652
E/AndroidRuntime( 2652): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2652): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2652): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2652): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2652): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2652): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2652): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2652): 	at cid.d(PG:186)
E/AndroidRuntime( 2652): 	at clo.g(PG:594)
E/AndroidRuntime( 2652): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2652): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2652): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2652): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2652): 	at clr.tL(PG:827)
E/AndroidRuntime( 2652): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2652): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2652): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2652): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2652): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ActivityManager(  900): App crashed! Process: com.google.android.googlequicksearchbox:search
I/ActivityManager(  900): Recipient 4017
I/ActivityManager(  900): Process com.google.android.gms.drive (pid 4017) has died.
W/ActivityManager(  900): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/Process ( 2652): killProcess, pid=2652
E/DropBoxManagerService(  900): Can't write: system_app_crash
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
D/Process ( 2652): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
W/ContextImpl( 4059): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4059): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4059): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4059): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4059): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4059): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4059): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4059): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4059): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4059): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4059): threadid=10: thread exiting with uncaught exception (group=0x41659e30)
I/ActivityManager(  900): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4074 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4059): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4059): Process: com.android.keychain, PID: 4059
E/AndroidRuntime( 4059): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4059): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4059): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4059): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4059): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4059): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4059): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4059): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  900): App crashed! Process: com.android.keychain
D/ErrorReport(  900): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4074): getInstance(Context context)
D/Process ( 4059): killProcess, pid=4059
D/Process ( 4059): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  900): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  900): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453808793286.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  900): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  900): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  900): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  900): 	... 4 more
I/ActivityManager(  900): Recipient 4059
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Process com.android.keychain (pid 4059) has died.
D/AppTag  ( 4074): getInstance(Context context)
D/AppTag  ( 4074): onCreate()
W/ActivityManager(  900): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  900): Recipient 2652
D/MediaRouterService(  900): Client com.google.android.googlequicksearchbox (pid 2652): Died!
D/WifiService(  900): Client connection lost with reason: 4
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Process com.google.android.googlequicksearchbox:search (pid 2652) has died.
W/ActivityManager(  900): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  900): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
I/DeviceManagement( 3750): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 3750): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
D/PMS     (  900): acquireWL(4235ce30): PARTIAL_WAKE_LOCK  AsyncService 0x1 3639 10160 null
D/PMS     (  900): releaseWL(4235ce30): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/DeviceManagement( 3750): WorkflowService: Starting workflow service
I/DeviceManagement( 3750): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c65d00] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 3750): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3750): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 3750): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3750): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 3750): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 3750): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3750): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5ca05170
I/ActivityManager(  900): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4094 uid=10099 gids={50099, 3003, 5012}
W/DeviceManagement( 3750): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c65d00]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 3750): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 3750): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 3750): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 3750): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 3750): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 3750): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 3750): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 3750): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 3750): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 3750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 3750): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 3750): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 3750): WorkflowService: Stopping workflow service
D/Process (  900): killProcessQuiet, pid=3784
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3784:com.htc.backup/1000 (adj 15): empty #17
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Recipient 3784
W/PackageManager(  900): Unable to load service info ResolveInfo{42fe5b40 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  900): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  900): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  900): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  900): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  900): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  900): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  900): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  900): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  900): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  900): 	at dalvik.system.NativeStart.main(Native Method)
D/Documents( 4094): Loading roots for com.android.providers.downloads.documents
D/Documents( 4094): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4094): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4094): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4094): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4094): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4094): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4094): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4094): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4094): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4094): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4094): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4094): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4094): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4094): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4094): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4094): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4094): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4094): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4094): threadid=1: thread exiting with uncaught exception (group=0x41659e30)
E/AndroidRuntime( 4094): FATAL EXCEPTION: main
E/AndroidRuntime( 4094): Process: com.android.documentsui, PID: 4094
E/AndroidRuntime( 4094): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4094): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4094): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4094): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4094): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4094): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4094): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4094): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4094): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4094): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4094): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4094): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4094): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4094): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4094): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4094): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4094): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4094): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4094): 	... 10 more
I/ActivityManager(  900): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4108 uid=10023 gids={50023, 1028, 1015, 1023}
E/ActivityManager(  900): App crashed! Process: com.android.documentsui
D/Process (  900): killProcessQuiet, pid=3801
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ErrorReport(  900): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  900): Killing 3801:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/GCM     ( 1342): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/Process (  900): killProcessQuiet, pid=3542
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  900): Recipient 3801
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Killing 3542:com.google.android.gm/u0a107 (adj 15): empty #17
D/GCM     ( 1342): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/ErrorReport(  900): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  900): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453808793556.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  900): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  900): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  900): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  900): 	... 4 more
D/Process ( 4094): killProcess, pid=4094
D/Process ( 4094): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/ExternalStorage( 4108): After updating volumes, found 1 active roots
W/ContentService(  900): Found dead observer, removing
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Recipient 4094
I/ActivityManager(  900): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4123 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  900): Process com.android.documentsui (pid 4094) has died.
I/ActivityManager(  900): Recipient 3542
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4123): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4123): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4123): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4123): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4123): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4123): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4123): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4123): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4123): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4123): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4123): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4123): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4123): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4123): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4123): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4123): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4123): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4123): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4123): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4123): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4123): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4123): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4123): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4123): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 4123): Opened MyDB.db in read-only mode
D/RemoteDisplayProvider(  900): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOV,ED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  900): start
W/AtomicFile(  900): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  900): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml

```
