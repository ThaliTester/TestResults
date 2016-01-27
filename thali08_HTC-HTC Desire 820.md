#### Test 564496604206eac_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  911): acquireWL(437c2a90): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
,D/PMS     (  911): releaseWL(437c2a90): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  911): acquireWL(437bc870): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
D/PMS     (  911): releaseWL(437bc870): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  911): acquireWL(43747028): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
D/PMS     (  911): releaseWL(43747028): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  911): acquireWL(436a8030): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
D/PMS     (  911): releaseWL(436a8030): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of /dev/log/main
E/cutils-trace( 3851): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3851): ====startRecUseTime====
D/htc.customization.log.level( 3851):  is 
W/CustomizationLogLevel( 3851): Level value is invalid, use default level 2
D/CustomizationManager( 3851):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3851): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3851): Parsing tag category name = system
I/CustomizationCIDLoader( 3851): Parsing tag category name = application
I/CustomizationCIDLoader( 3851): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3851): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3851): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3851): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3851): Parsing tag category name = Settings
D/CustomizationManager( 3851):  Read CID file spent 0.091 (s)
D/CustomizationManager( 3851):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 3851): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3851): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3851): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3851): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3851
D/PMS     (  911): acquireHCC(436a3c10): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(4364db50): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
W/asset   (  911): Copying FileAsset 0x65219898 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1124486544
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c0eac8
D/PMS     (  911): acquireWL(433d5140): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/ActivityManager(  911): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3864 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1248): [trimMemory] 20
W/asset   ( 3864): Copying FileAsset 0x5c767428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3864): Binding Chromium to main looper Looper (main, tid 1) {41b62f90}
I/LibraryLoader( 3864): Expected native library version number "",actual native library version number ""
I/chromium( 3864): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3864): Initializing chromium process, renderers=0
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424a0050:true
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3864): 1102548480: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  911): acquireWL(42545720): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  911): acquireWL(424db900): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  911): releaseWL(424db900): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3864): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3864): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3864): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3864): Local Branch: 
I/Adreno-EGL( 3864): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3864): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3864):                  aa63bbd948f41d15fc72f585e
W/chromium( 3864): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3864): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3864): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3864): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3864): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3864): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3864): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3864): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3864): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3864): CordovaWebView is running on device made by: HTC
,W/AwContents( 3864): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  911): Disable input method client, pid=1248
,W/ResourceType( 3864): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3864): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41baa388, mServedView=org.apache.cordova.engine.SystemWebView{41b70118 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  911): Enable input method client, pid=3864
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 3864): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  911): Displayed com.test.thalitest/.MainActivity: +266ms
D/PMS     (  911): releaseWL(433d5140): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3864): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3864): JniHelper::setJavaVM(0x41720010), pthread_self() = 1663826208
,I/chromium( 3864): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 11.949MB for 42652-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 12.026MB for 95956-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 12.106MB for 143930-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 12.220MB for 215890-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 12.396MB for 323830-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 12.667MB for 485740-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 13.655MB for 1092904-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 14.580MB for 1639352-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 15.837MB for 2459024-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 18.013MB for 3688532-byte allocation
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
D/PMS     (  911): releaseHCC(436a3c10): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  911): releaseHCC(4364db50): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3864): Initializing JXcore engine
,W/jxcore-log( 3864): JXcore engine is ready
,W/jxcore-log( 3864): Starting JXcore engine
,W/jxcore-log( 3864): Platform android
W/jxcore-log( 3864): 
,W/jxcore-log( 3864): Process ARCH arm
W/jxcore-log( 3864): 
,I/ActivityManager(  911): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3908 uid=10077 gids={50077}
D/PMS     (  911): acquireWL(425ed090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10077}
V/AlarmManager(  911): sending alarm PendingIntent{42540f68: PendingIntentRecord{42549458 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453885518321, Int=60000
,D/PMS     (  911): releaseWL(425ed090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3908): SMSBackupAgentService started
,D/SMSBackup( 3908): Checking restore status
,D/SMSBackup( 3908): Restore complete
,D/SMSBackup( 3908): cancelCheckAlarm
,D/SMSBackup( 3908): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  911): killProcessQuiet, pid=2877
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 2877:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2877
,I/jxcore-log( 3864): JXcore Cordova bridge is ready!
I/jxcore-log( 3864): 
,W/jxcore-log( 3864): JXcore engine is started
,E/jxcore  ( 3864): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3864): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3864): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3864): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 31ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  911): acquireWL(41fe0e88): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
,I/FeedHostManager( 1248): [onResume]
,I/FeedProviderManager( 1248): onResume
,I/SocialFeedProvider( 1248): +onResume
,I/SocialFeedProvider( 1248): updateAccounts - Accounts is no change
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.launcher (1248/10075)
I/SocialFeedProvider( 1248): -onResume
I/ConnectivityHelper( 1248): [getCurrentConnectionType] no network connection
,I/InputMethodManagerService(  911): Disable input method client, pid=3864
,W/IInputConnectionWrapper( 3864): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  911): Enable input method client, pid=1248
,D/PMS     (  911): releaseWL(41fe0e88): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  911): killProcessQuiet, pid=3693
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  911): Killing 3693:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3693
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/libEGL  ( 3864): call to OpenGL ES API with no current context (logged once per thread)
D/WifiService(  911): Client connection lost with reason: 4
,D/PMS     (  911): releaseWL(42545720): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  911): mEventCount = 900
,I/PMS     (  911): Going to sleep due to screen timeout...
,D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4220c0d0
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4220c0d0, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42048ee0
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@42591960
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:,
W/PMS     (  911): mWirelessDisplayManager is null
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
W/BatSI   (  911): Couldn't get kernel wake lock stats,
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 371ms
D/PMS     (  911): nativeSetInteractive:false
D/NfcService( 1230): ScreenObserver: OFF
,D/NfcService( 1230): applyRouting - 0
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
D/PMS     (  911): OOBE c monitor 11
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
I/InputMethodManagerService(  911): Disable input method client, pid=1248
D/NfcService( 1230): applyRouting -2
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@437c74f0)
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
D/PMS     (  911): acquireWL(42617e50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/PMN     (  911): wakingUp
D/PMS     (  911): releaseWL(42617e50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  911): acquireWL(437c4d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/WindowManager(  911): No lock screen! windowToken=null
I/BatteryService(  911): n_update end
,I/IntentController( 1111): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  911): releaseWL(437c4d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  911): onScreenOn
,D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 2209): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1230): applyRouting - 0
D/MtpService( 2209): [MTP][onReceive]-
,D/NfcService( 1230): applyRouting -2
,D/AutoSetting( 1400): receiver - intent: android.intent.action.USER_PRESENT
I/HtcPowerSaver(  911): << updateStatus
D/PMS     (  911): acquireWL(43e2bb50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/PMS     (  911): releaseWL(43e2bb50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
,D/AutoSetting( 1400): service - onCreate()
D/TetherSettings( 3340): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3340): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3340): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3340): Cust_ConnectToPC   : spcsc>false
D/        ( 3340): Cust_ConnectToPC   : IPT>true
D/        ( 3340): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3340): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3340): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3340): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3340): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
D/AutoSetting( 1400): service - AddressCache: using context: com.htc.Weather
,I/PSReceiver( 3340): onReceive:android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
,D/AutoSetting( 1400): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiNative-wlan0(  911):    returned false
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ContextImpl( 3340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
I/SmartNS_PSService( 3340): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3340): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3340):  defaultType:0
D/LocationManagerService(  911): request 42506ca8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
,I/ClockThread( 1111): stop update clock
,V/SRS_Proc(  372): ParamSet string: screen_state=on
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ActivityManager(  911): Disable JIT of com.htc.bgp
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/ActivityManager(  911): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3931 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
D/NetworkPolicy(  911): updateScreenOn: false
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): acquireWL(44188e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1418 10028 null
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42048ee0
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42048ee0, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@42591960
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  911): releaseWL(44188e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMN     (  911): goingToSleep
D/PMS     (  911): acquireWL(42a552a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
,I/FeedHostManager( 1248): [onPause]
,I/FeedProviderManager( 1248): onPause
,I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
,I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c0eac8
D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
,I/AlarmManager(  911): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=19511 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  911):    returned false
I/CalendarProvider2( 3931): Created com.android.providers.calendar.CalendarAlarmManager@41b9eaf8(com.android.providers.calendar.HtcCalendarProvider@41b86e80)
V/SRS_Proc(  372): ParamSet string: screen_state=off
D/PMS     (  911): acquireWL(42b64c48): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/PMS     (  911): releaseWL(42b64c48): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/CalendarProvider2( 3931): wait start:true
D/PMS     (  911): releaseWL(42a552a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  911): updateScreenOn: false
D/ContactMessageStore( 1221): start background delete task...
D/ContactMessageStore( 1221): size: 0 , 0
D/ContactMessageStore( 1221): Background delete complete
D/CalendarProvider2( 3931): wait end:false
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3951 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  911): acquireWL(43103978): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1418 10028 null
D/PMS     (  911): releaseWL(43103978): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1400): service - mHandler: cancel location update
,D/AutoSetting( 1400): service -           changes count: 0
,D/SmartSyncUtils( 3951): isEpsOn(), nState = 0
D/PMS     (  911): acquireWL(43804ab8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3951 1000 null
,D/SmartSyncUtils( 3951): getMobilePolicyEnabled, result = true
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  911): releaseWL(43804ab8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3951): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3951): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3951): isEpsOn(), nState = 0
D/WifiService(  911): New client listening to asynchronous messages
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42591960
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42591960, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42591960, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42591960
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42591e80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42591e80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  911): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  911): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  911): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  911): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  911): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  911): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  911): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  911): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 3931): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3931): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3724): ---------------------------------------------------
,D/ProviderChangeReceiver( 3724): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3724): start to updateAlertNotification!
,W/ContextImpl( 3738): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3724): No fired or scheduled alerts
,D/HtcAlertUtils( 3724): -- cancelReminderNotification --
,D/HtcAlertUtils( 3724): broadcastExistReminder!
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  911): killProcessQuiet, pid=3406
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3406:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3406
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  911): Client com.google.android.music (pid 3406): Died!
,D/Process (  911): killProcessQuiet, pid=3428
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3428:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3428
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{42b399d0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  911): acquireWL(43cd19d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43cd19d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1400): service - handleMessage() stop self
,D/AutoSetting( 1400): service - onDestroy() END
,D/Process (  911): killProcessQuiet, pid=3389
,D/AutoSetting( 1400): service - handleMessage() quit looper
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3389:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3389
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(42dce218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10028}
,V/AlarmManager(  911): sending alarm PendingIntent{434db640: PendingIntentRecord{42575ba8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140575, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{42287c08: PendingIntentRecord{423d1538 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=140863, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{41fa0458: PendingIntentRecord{4252cd80 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140873, Int=0
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    (  911): [NET] getaddrinfo_proxy-
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(43c356b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(42dce218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  911): releaseWL(43c356b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  911): acquireWL(43e5d6a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=144760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43e5d6a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(43c968f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(43c968f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1221): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(43c49678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43c49678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  911): [NET] getaddrinfo_proxy-
D/PMS     (  911): acquireWL(43e31b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{42287c08: PendingIntentRecord{423d1538 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=200888, Int=0
D/PMS     (  911): releaseWL(43e31b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(424e5a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=204760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(424e5a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43127590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(43127590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(436a3128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(436a3128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
,D/PowerUI ( 1111): closing low battery warning: level=100
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(43275cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=264760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43275cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(43e1f220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43e1f220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  911): updateBatteryInfo
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43e44468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=324760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43e44468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1531): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1531): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
I/RemoteViews( 1111): com.google.android.gms (false,0)
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3610): [NET] getaddrinfo-,err=8
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3610): [NET] getaddrinfo-, 1
,D/libc    ( 3610): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7,
D/libc    ( 3610): [NET] getaddrinfo_proxy-
D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41b909d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 12 3 12
,D/PMS     (  911): acquireWL(440fcff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(440fcff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(43ef4d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=384760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43ef4d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,D/PMS     (  911): acquireWL(42557d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1531): [EventService] reorderNotification, total:1
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
V/NotificationService(  911): batLight: plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
D/HtcPowerSaver(  911): updateBatteryInfo
V/LightsService(  911): setLight #8: color=#c80000
D/qdlights(  911): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1111): closing low battery warning: level=98
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): releaseWL(42557d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3340): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3340): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3340): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3340): Cust_ConnectToPC   : spcsc>false
,D/        ( 3340): Cust_ConnectToPC   : IPT>true
D/        ( 3340): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3340): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3340): Index of the first 1 = -1
W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
W/Settings( 3340): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 3340): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3340): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 3340): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3340): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3340): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
D/SmartNS_Utility( 3340): [ACC]android_networking:tethering_guard_support=false
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4308c350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4308c350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(434aac28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=444760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(434aac28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(440e7240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(440e7240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=98
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(4418d650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4418d650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(42bda370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=504760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42bda370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(43c4f768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43c4f768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43dede90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=564761, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43dede90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42600ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): releaseWL(42600ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=99
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(4410d6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4410d6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1221): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1221): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1221): sku_id=99
D/ContactMessageStore( 1221): start background delete task...
D/ContactMessageStore( 1221): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1221): size: 0 , 0
,D/ContactMessageStore( 1221): Background delete complete
,D/PMS     (  911): acquireWL(425c8cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=624759, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(425c8cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41ee7f80 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1111): com.google.android.gms 3 10 3 12
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3610): [NET] getaddrinfo-,err=8
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3610): [NET] getaddrinfo-, 1
,D/libc    ( 3610): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
,D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3610): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/DotMatrix( 1531): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1531): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  911): acquireWL(440f6298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(440f6298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(440e8d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=684760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(440e8d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(440d82d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(440d82d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4408c428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=744760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4408c428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,D/PMS     (  911): acquireWL(43e75920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/PowerUI ( 1111): closing low battery warning: level=100
D/DotMatrix( 1531): [EventService] reorderNotification, total:0
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(43e75920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3340): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3340): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3340): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3340): Cust_ConnectToPC   : spcsc>false
D/        ( 3340): Cust_ConnectToPC   : IPT>true
D/        ( 3340): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3340): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3340): Index of the first 1 = -1
W/ContextImpl( 3340): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3340): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3340): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3340): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
W/ContextImpl( 3340): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
D/SmartNS_NSReceiver( 3340): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(437e95d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(437e95d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(437cfd98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=804760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(437cfd98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(437c78f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(437c78f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(437c49f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=864760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(437c49f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,D/PMS     (  911): acquireWL(437c2a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(437c2a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(437bde90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=924760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(437bde90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1111): com.google.android.gms (false,0)
D/DotMatrix( 1531): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1531): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41fbd338 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3610): [NET] getaddrinfo-,err=8
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3610): [NET] getaddrinfo-, 1
,D/libc    ( 3610): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3610): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 15 3 12
,D/PMS     (  911): acquireWL(425539f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(425539f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(424dd928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=984760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(424dd928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,D/PMS     (  911): acquireWL(4244b418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41e2d918: PendingIntentRecord{424a0178 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782393, Int=0
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  911): Done.
,D/ConnectivityService(  911): Setting timer for 720seconds
,I/ActivityManager(  911): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3998 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  911): sending alarm PendingIntent{42470890: PendingIntentRecord{4253f508 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453885635436, Int=10800000
,V/AlarmManager(  911): sending alarm PendingIntent{41b5fe78: PendingIntentRecord{423cd268 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453886355775, Int=900000
,V/AlarmManager(  911): sending alarm PendingIntent{42533950: PendingIntentRecord{43dd6078 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453886425878, Int=0
,W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3951): call getInstance()
,D/SmartSyncUtils( 3951): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3951): MY_DEBUG = false
D/PMS     (  911): releaseWL(4244b418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  911): acquireWL(42343ef8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3951 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3951): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3951): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3951): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3951): SettingOnTime = 1453960800000, randomSettingOnTime = 1453957251000
,D/SmartSyncScreenOnOffTimeReceiver( 3951): SettingOffTime = 1453939200000, randomSettingOffTime = 1453940492000
,D/SmartSyncScreenOnOffTimeReceiver( 3951): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3951): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3951): bNightModeTurnOffOnce = false
W/BatSI   (  911): Couldn't get kernel wake lock stats
D/PMS     (  911): releaseWL(42343ef8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.aurora (3998/10047)
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/Process (  911): killProcessQuiet, pid=3756
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3756:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3756
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(42b77d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42b77d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(431a5810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1044760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(431a5810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42d1e310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42d1e310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(423ed1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1104760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(423ed1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,D/PMS     (  911): acquireWL(42c4ad08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42c4ad08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43c46730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1164760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43c46730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(424e4190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(424e4190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(437c8a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1224760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(437c8a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
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
,D/DotMatrix( 1531): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1531): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3610): [NET] getaddrinfo-,err=8
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3610): [NET] getaddrinfo-, 1
D/libc    ( 3610): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
I/RemoteViews( 1111): com.google.android.gms (false,0)
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3610): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41e06668 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 2 7 2 12
,D/PMS     (  911): acquireWL(430d6b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(430d6b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43dcd840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41c15798: PendingIntentRecord{423d5168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1284760, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43dcd840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4017): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4017): ====startRecUseTime====
D/htc.customization.log.level( 4017):  is 
W/CustomizationLogLevel( 4017): Level value is invalid, use default level 2
D/CustomizationManager( 4017):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4017): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4017): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4017): Parsing tag category name = system
I/CustomizationCIDLoader( 4017): Parsing tag category name = application
I/CustomizationCIDLoader( 4017): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4017): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4017): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4017): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4017): Parsing tag category name = Settings
D/CustomizationManager( 4017):  Read CID file spent 0.156 (s)
D/CustomizationManager( 4017):  All configurations done spent 0.157 (s)
W/HtcNativeFlag( 4017): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4017): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4017): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4017): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4017, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  911): killProcessQuiet, pid=3864
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  911): Killing 3864:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
W/asset   (  911): Copying FileAsset 0x6263de58 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
D/DotMatrix( 1531): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1531): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1531): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1769): Unregistering com.test.thalitest
E/acms    ( 1769): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1418): Ignoring removeGeofence because network location is disabled.
D/PMS     (  911): acquireWL(4257acf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1418 10028 null
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  911): releaseWL(4257acf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Launcher( 1248): Deferring update until onResume
D/Launcher( 1248): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1275): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
D/PackageBroadcastService( 1202): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/ActivityManager(  911): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4032 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
W/Parcel  ( 1230): Reading a NULL string not supported here.
I/MultiDex( 4032): install
I/MultiDex( 4032): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/MultiDex( 4032): loading existing secondary dex files
I/MultiDex( 4032): load found 1 secondary dex files
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/MultiDex( 4032): install done
E/ExternalAccountType( 1308): Unsupported attribute readOnly
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  911):   Scheme: "mmsto"
I/ActivityManager(  911): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4050 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1221): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1202): CP2 sync disabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1202, uid=10028, userID:0
I/Icing   ( 1202): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4032): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  911): acquireWL(41d97cb0): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
D/PMS     (  911): releaseWL(41d97cb0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4050): install
I/MultiDex( 4050): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  911): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4050): loading existing secondary dex files
I/MultiDex( 4050): load found 1 secondary dex files
I/MultiDex( 4050): install done
I/ProviderInstaller( 4050): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  911): Resuming delayed broadcast
E/SQLiteDatabase( 1202): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1202): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1202): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1202): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1202): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1202): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1202): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1202): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1202): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1202): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1202): Runtime exception while performing operation
E/ClearPendingStateOp( 1202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1202): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1202): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1202): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1202): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1202): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1202): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1202): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1202): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1202): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1186): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
F/ClearPendingStateOp( 1202): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1202): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1202): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1202): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1202): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1202): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1202): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1202): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1202): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1202): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1400): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  911): Resuming delayed broadcast
E/SQLiteLog( 1400): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1400): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9f7ac8
W/[PluginManager]RegisterService( 1400): provider may killed!
W/[PluginManager]RegisterService( 1400): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1400): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1400): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1400): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1400): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1400): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1400): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  911): Can't write: system_app_wtf
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
I/[PluginManager]RegisterService( 1400): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1248): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2657): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4073 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/SQLiteDatabase( 4032): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4032): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4032): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4032): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4032): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4032): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4032): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4032): threadid=12: thread exiting with uncaught exception (group=0x41731e30)
E/AndroidRuntime( 4032): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4032): Process: com.google.android.gms.drive, PID: 4032
E/AndroidRuntime( 4032): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4032): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4032): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4032): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4032): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4032): 	at ctn.run(SourceFile:985)
E/SQLiteLog( 2657): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2657): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x635bd2e8
W/dalvikvm( 2657): threadid=14: thread exiting with uncaught exception (group=0x41731e30)
E/AndroidRuntime( 2657): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2657): Process: com.google.android.googlequicksearchbox:search, PID: 2657
E/AndroidRuntime( 2657): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2657): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2657): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2657): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2657): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2657): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2657): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2657): 	at cid.d(PG:186)
E/AndroidRuntime( 2657): 	at clo.g(PG:594)
E/AndroidRuntime( 2657): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2657): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2657): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2657): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2657): 	at clr.tL(PG:827)
E/AndroidRuntime( 2657): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2657): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2657): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2657): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2657): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2657): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms.drive
E/ActivityManager(  911): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 4032): killProcess, pid=4032
D/Process ( 2657): killProcess, pid=2657
D/Process ( 4032): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
D/Process ( 2657): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
W/ContextImpl( 4073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4073): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4073): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4073): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4073): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4073): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4073): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4073): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4073): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4073): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4073): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4073): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4073): threadid=10: thread exiting with uncaught exception (group=0x41731e30)
E/AndroidRuntime( 4073): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4073): Process: com.android.keychain, PID: 4073
E/AndroidRuntime( 4073): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4073): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4073): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4073): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4073): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4073): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4073): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4073): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4073): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4073): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  911): App crashed! Process: com.android.keychain
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  911): Recipient 2657
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.googlequicksearchbox:search (pid 2657) has died.
D/WifiService(  911): Client connection lost with reason: 4
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/MediaRouterService(  911): Client com.google.android.googlequicksearchbox (pid 2657): Died!
I/ActivityManager(  911): Recipient 4032
I/ActivityManager(  911): Process com.google.android.gms.drive (pid 4032) has died.
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10993ms
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4089 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/Process ( 4073): killProcess, pid=4073
D/Process ( 4073): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453886728761.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
I/ActivityManager(  911): Recipient 4073
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.android.keychain (pid 4073) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10928ms
W/PackageManager(  911): Unable to load service info ResolveInfo{42857008 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
D/AppTag  ( 4089): getInstance(Context context)
D/AppTag  ( 4089): getInstance(Context context)
D/AppTag  ( 4089): onCreate()
D/PMS     (  911): acquireWL(42584678): PARTIAL_WAKE_LOCK  AsyncService 0x1 3646 10160 null
D/PMS     (  911): releaseWL(42584678): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/DeviceManagement( 3773): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 3773): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 3773): WorkflowService: Starting workflow service
I/DeviceManagement( 3773): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d33f40] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 3773): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3773): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 3773): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3773): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 3773): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  911): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4109 uid=10099 gids={50099, 3003, 5012}
E/SQLiteLog( 3773): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3773): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5ca66538
W/DeviceManagement( 3773): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d33f40]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 3773): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 3773): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 3773): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 3773): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 3773): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 3773): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 3773): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 3773): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 3773): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 3773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 3773): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 3773): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 3773): WorkflowService: Stopping workflow service
D/Process (  911): killProcessQuiet, pid=3807
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41bf4010 +
I/Prism.WidgetManager( 1248): onLoadItems() +
I/ActivityManager(  911): Killing 3807:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  911): Recipient 3807
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Documents( 4109): Loading roots for com.android.providers.downloads.documents
D/Documents( 4109): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4109): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4109): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4109): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4109): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4109): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4109): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4109): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4109): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4109): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4109): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4109): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4109): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4109): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4109): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4109): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4109): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4109): threadid=1: thread exiting with uncaught exception (group=0x41731e30)
E/AndroidRuntime( 4109): FATAL EXCEPTION: main
E/AndroidRuntime( 4109): Process: com.android.documentsui, PID: 4109
E/AndroidRuntime( 4109): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4109): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4109): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4109): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4109): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4109): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4109): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4109): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4109): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4109): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4109): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4109): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4109): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4109): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4109): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4109): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4109): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4109): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4109): 	... 10 more
I/ActivityManager(  911): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4123 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process (  911): killProcessQuiet, pid=3824
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/ActivityManager(  911): App crashed! Process: com.android.documentsui
D/GCM     ( 1338): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  911): Killing 3824:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  911): Recipient 3824
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  911): killProcessQuiet, pid=3544
I/ActivityManager(  911): Killing 3544:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
D/GCM     ( 1338): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  911): Recipient 3544
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ExternalStorage( 4123): After updating volumes, found 1 active roots
I/ActivityManager(  911): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4137 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
D/Documents( 4109): Loading roots for com.android.providers.media.documents
D/Process ( 4109): killProcess, pid=4109
D/Process ( 4109): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453886729291.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
I/ActivityManager(  911): Recipient 4109
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.android.documentsui (pid 4109) has died.

```
