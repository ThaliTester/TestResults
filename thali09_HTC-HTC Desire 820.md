#### Test 5065027865f659b_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  911): acquireWL(423289e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
--------- beginning of /dev/log/main
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): releaseWL(423289e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 3807): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3807): ====startRecUseTime====
D/htc.customization.log.level( 3807):  is 
W/CustomizationLogLevel( 3807): Level value is invalid, use default level 2
D/CustomizationManager( 3807):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3807): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3807): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3807): Parsing tag category name = system
I/CustomizationCIDLoader( 3807): Parsing tag category name = application
I/CustomizationCIDLoader( 3807): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3807): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3807): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3807): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3807): Parsing tag category name = Settings
D/CustomizationManager( 3807):  Read CID file spent 0.095 (s)
D/CustomizationManager( 3807):  All configurations done spent 0.095 (s)
W/HtcNativeFlag( 3807): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3807): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3807): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3807): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3807
D/PMS     (  911): acquireHCC(42573698): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(42421408): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
W/asset   (  911): Copying FileAsset 0x6c63f590 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1113211992
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f6caf8
I/SocialFeedProvider( 1250): +onPause
I/SocialFeedProvider( 1250): -onPause
D/PMS     (  911): acquireWL(41f40638): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/ActivityManager(  911): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3818 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1250): [trimMemory] 20
W/asset   ( 3818): Copying FileAsset 0x5c729560 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3818): Binding Chromium to main looper Looper (main, tid 1) {41ab4f88}
I/LibraryLoader( 3818): Expected native library version number "",actual native library version number ""
I/chromium( 3818): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3818): Initializing chromium process, renderers=0
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424afeb8:true
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3818): 1101835768: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  911): acquireWL(42660c50): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): acquireWL(4259fd38): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  911): releaseWL(42660c50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3818): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3818): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3818): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3818): Local Branch: 
I/Adreno-EGL( 3818): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3818): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3818):                  aa63bbd948f41d15fc72f585e
W/chromium( 3818): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3818): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3818): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3818): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3818): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3818): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3818): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3818): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3818): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3818): CordovaWebView is running on device made by: HTC
,W/AwContents( 3818): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  911): Disable input method client, pid=1250
,W/ResourceType( 3818): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3818): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41afc380, mServedView=org.apache.cordova.engine.SystemWebView{41ac2110 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  911): Enable input method client, pid=3818
I/ActivityManager(  911): Displayed com.test.thalitest/.MainActivity: +275ms
W/AwContents( 3818): nativeOnDraw failed; clearing to background color.
,D/PMS     (  911): releaseWL(41f40638): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/PMS     (  911): acquireWL(43fc7f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029}
,V/AlarmManager(  911): sending alarm PendingIntent{41e5bd30: PendingIntentRecord{425957c0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449598341255, Int=1800000
,D/PMS     (  911): acquireWL(435ad7d8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{4259d9e0: PendingIntentRecord{43994948 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449598347696, Int=0
,I/ActivityManager(  911): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3859 uid=10078 gids={50078}
,V/AlarmManager(  911): sending alarm PendingIntent{423694f0: PendingIntentRecord{42655db8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449598349000, Int=60000
,D/PMS     (  911): releaseWL(43fc7f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  911): acquireWL(42647368): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(435ad7d8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/SMSBackup( 3859): SMSBackupAgentService started
,D/SMSBackup( 3859): Checking restore status
,I/EventLogService( 1956): Aggregate from 1449596541189 (log), 1449596541189 (data)
D/SMSBackup( 3859): Restore complete
,D/SMSBackup( 3859): cancelCheckAlarm
,D/SMSBackup( 3859): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360022844
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023433
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023436
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023443
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027739
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360022844
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023194
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023433
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023436
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023443
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027739
,D/PMS     (  911): releaseWL(42647368): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/JsMessageQueue( 3818): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3818): JniHelper::setJavaVM(0x4158f048), pthread_self() = 1663077728
,D/JX-Cordova( 3818): jxcore cordova android initializing
,W/dalvikvm( 3818): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/Finsky  ( 3479): [362] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3479): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  911): killProcessQuiet, pid=3620
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3620:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3620
D/WifiService(  911): Client connection lost with reason: 4
,I/SensorManager(  911): mEventCount = 900
,I/dalvikvm-heap( 3818): Grow heap (frag case) to 11.641MB for 143930-byte allocation
,I/dalvikvm-heap( 3818): Grow heap (frag case) to 11.762MB for 215890-byte allocation
,I/dalvikvm-heap( 3818): Grow heap (frag case) to 11.934MB for 323830-byte allocation
,I/dalvikvm-heap( 3818): Grow heap (frag case) to 12.193MB for 485740-byte allocation
,I/dalvikvm-heap( 3818): Grow heap (frag case) to 12.595MB for 728606-byte allocation
,I/dalvikvm-heap( 3818): Grow heap (frag case) to 14.093MB for 1639352-byte allocation
,I/dalvikvm-heap( 3818): Grow heap (frag case) to 15.460MB for 2459024-byte allocation
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
,D/PMS     (  911): releaseHCC(42573698): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
,D/PMS     (  911): releaseHCC(42421408): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3818): Grow heap (frag case) to 17.541MB for 3688532-byte allocation
,W/jxcore-log( 3818): Initializing JXcore engine
,W/jxcore-log( 3818): JXcore engine is ready
,W/jxcore-log( 3818): Starting JXcore engine
,W/jxcore-log( 3818): Platform android
W/jxcore-log( 3818): 
,W/jxcore-log( 3818): Process ARCH arm
W/jxcore-log( 3818): 
,D/PMS     (  911): releaseWL(4259fd38): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3818): JXcore Cordova bridge is ready!
I/jxcore-log( 3818): 
,W/jxcore-log( 3818): JXcore engine is started
,I/chromium( 3818): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3818): Error!: missing ) after argument list
E/jxcore  ( 3818): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3818): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37),
I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3818): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 37ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  911): acquireWL(43b1b248): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
,I/FeedHostManager( 1250): [onResume]
,I/FeedProviderManager( 1250): onResume
I/SocialFeedProvider( 1250): +onResume
I/SocialFeedProvider( 1250): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1250): -onResume
I/ConnectivityHelper( 1250): [getCurrentConnectionType] no network connection
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.launcher (1250/10076)
,I/InputMethodManagerService(  911): Disable input method client, pid=3818
,I/InputMethodManagerService(  911): Enable input method client, pid=1250
,W/IInputConnectionWrapper( 3818): reportFullscreenMode on inactive InputConnection
,D/PMS     (  911): releaseWL(43b1b248): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  911): killProcessQuiet, pid=3529
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  911): Killing 3529:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3529
,E/libEGL  ( 3818): call to OpenGL ES API with no current context (logged once per thread)
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421403f8
,D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  911): pid=911, uid=1000
,W/SensorService(  911): Active sensors: size = 2
,W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421403f8, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f04e18
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@42311bc0
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  911): mWirelessDisplayManager is null
W/BatSI   (  911): Couldn't get kernel wake lock stats
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 336ms
D/PMS     (  911): nativeSetInteractive:false
,D/PMS     (  911): nativeSetInteractive:false done
,D/PMS     (  911): nativeSetAutoSuspend:true
,D/PMS     (  911): nativeSetAutoSuspend:true done
,D/HABCtrl (  911): TPE algorithm. remove timeout.
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
D/PMS     (  911): OOBE c monitor 11
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
,D/NfcService( 1232): ScreenObserver: OFF
,D/NfcService( 1232): applyRouting - 0
I/InputMethodManagerService(  911): Disable input method client, pid=1250
D/NfcService( 1232): applyRouting -2
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4403eb60)
D/PMS     (  911): acquireWL(439b7cb8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMN     (  911): wakingUp
D/PMS     (  911): acquireWL(43f72e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(43f72e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
,I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(439b7cb8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  911): No lock screen! windowToken=null
D/PMN     (  911): onScreenOn
D/HtcPowerSaver(  911): updateBatteryInfo
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 2165): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1232): applyRouting - 0
,D/MtpService( 2165): [MTP][onReceive]-
,D/NfcService( 1232): applyRouting -2
,D/AutoSetting( 1295): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  911): acquireWL(43fbeea0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
D/PMS     (  911): releaseWL(43fbeea0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  911): << updateStatus
,D/TetherSettings( 3268): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3268): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3268): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3268): Cust_ConnectToPC   : spcsc>false
D/        ( 3268): Cust_ConnectToPC   : IPT>true
D/        ( 3268): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3268): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3268): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3268): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3268): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1295): service - onCreate()
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
,D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/PSReceiver( 3268): onReceive:android.intent.action.USER_PRESENT
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
,D/AutoSetting( 1295): service - AddressCache: using context: com.htc.Weather
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
I/SmartNS_PSService( 3268): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3268): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3268):  defaultType:0
,D/WifiNative-wlan0(  911):    returned false
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
,W/ContextImpl( 3268): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1295): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  911): request 41db6500 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
I/ClockThread( 1109): stop update clock
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  911): updateScreenOn: false
,W/ActivityManager(  911): Disable JIT of com.htc.bgp
,I/ActivityManager(  911): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3887 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/PMS     (  911): acquireWL(4308f970): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): releaseWL(4308f970): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(43adb090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(43adb090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f04e18
,W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f04e18, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@42311bc0
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
,I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f6caf8
D/PMN     (  911): goingToSleep
,D/PMS     (  911): acquireWL(42558ff8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
I/SocialFeedProvider( 1250): +onPause
,I/SocialFeedProvider( 1250): -onPause
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=19541 mDataStallAlarmIntent=null
D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
I/AlarmManager(  911): [AlarmQueuing] wifi connection: false
,D/PMS     (  911): releaseWL(42558ff8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  911):    returned false
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  911): acquireWL(43b8d2a8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/PMS     (  911): releaseWL(43b8d2a8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/NetworkPolicy(  911): updateScreenOn: false
,I/CalendarProvider2( 3887): Created com.android.providers.calendar.CalendarAlarmManager@41af0ae0(com.android.providers.calendar.HtcCalendarProvider@41ad8e68)
,D/CalendarProvider2( 3887): wait start:true
,D/CalendarProvider2( 3887): wait end:false
,D/ContactMessageStore( 1220): start background delete task...
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3906 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ContactMessageStore( 1220): size: 0 , 0
D/ContactMessageStore( 1220): Background delete complete
,D/PMS     (  911): acquireWL(423fa500): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] getTotalRam: 1873 Mb
D/PMS     (  911): releaseWL(423fa500): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4294f270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  911): releaseWL(4294f270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43c5c9c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3906 1000 null
D/SmartSyncUtils( 3906): isEpsOn(), nState = 0
D/AutoSetting( 1295): service - mHandler: cancel location update
D/AutoSetting( 1295): service -           changes count: 0
,D/SmartSyncUtils( 3906): getMobilePolicyEnabled, result = true
D/PMS     (  911): releaseWL(43c5c9c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3906): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3906): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3906): isEpsOn(), nState = 0
D/WifiService(  911): New client listening to asynchronous messages
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42311bc0
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42311bc0, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42311bc0, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42311bc0
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42560548 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42560548 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/CalendarProvider2( 3887): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3887): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3647): ---------------------------------------------------
,D/ProviderChangeReceiver( 3647): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3647): start to updateAlertNotification!
,W/ContextImpl( 3661): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3647): No fired or scheduled alerts
,D/HtcAlertUtils( 3647): -- cancelReminderNotification --
,D/HtcAlertUtils( 3647): broadcastExistReminder!
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  911): killProcessQuiet, pid=2894
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 2894:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 2894
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  911): killProcessQuiet, pid=3342
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3342:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3342
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(44019210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029}
,V/AlarmManager(  911): sending alarm PendingIntent{4286cdb8: PendingIntentRecord{423a1160 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122249, Int=0
,D/PMS     (  911): releaseWL(44019210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  911): acquireWL(4254edb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1346/10029)
,D/PMS     (  911): releaseWL(4254edb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{4323af28 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(43add9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/HtcPowerSaver(  911): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1109): closing low battery warning: level=100
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(43add9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(430ccb90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=133815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(430ccb90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1295): service - handleMessage() stop self
,D/AutoSetting( 1295): service - onDestroy() END
,D/AutoSetting( 1295): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=3562
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3562:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3562
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(43c19cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{43c6d598: PendingIntentRecord{424e1680 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138622, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{421a2858: PendingIntentRecord{42457e58 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140918, Int=0
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
V/AlarmManager(  911): sending alarm PendingIntent{42411698: PendingIntentRecord{42335b20 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145800, Int=0
,D/PMS     (  911): acquireWL(42472fd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  911): [NET] getaddrinfo_proxy-
D/PMS     (  911): releaseWL(43c19cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): releaseWL(42472fd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  911): acquireWL(43c3e430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(43c3e430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(43904868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43904868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(43b3dec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=193815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43b3dec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(44045c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{434da120: PendingIntentRecord{423a1160 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=181945, Int=0
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  911): [NET] getaddrinfo_proxy-
V/AlarmManager(  911): sending alarm PendingIntent{42411698: PendingIntentRecord{42335b20 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=205823, Int=0
D/PMS     (  911): acquireWL(4278ad20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(44045c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1346/10029)
,D/PMS     (  911): releaseWL(4278ad20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(437c8098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(437c8098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43af61d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=253814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43af61d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(44013830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/HtcPowerSaver(  911): updateBatteryInfo
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(44013830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(43b2d450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43b2d450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43bfc260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=313815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43bfc260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3479): [NET] getaddrinfo-,err=8
D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3479): [NET] getaddrinfo-, 1
,D/libc    ( 3479): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3479): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(43ad2568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43ad2568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(43ba3db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=373815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43ba3db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4292fc48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4292fc48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(435fdda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=433815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(435fdda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(43b782c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43b782c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(44049c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=493814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44049c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4341cd48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4341cd48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4363ac20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=553814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4363ac20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43b601a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43b601a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(43bf3b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=613815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43bf3b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1220): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1220): sku_id=99
D/ContactMessageStore( 1220): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1220): start background delete task...
,D/ContactMessageStore( 1220): size: 0 , 0
,D/ContactMessageStore( 1220): Background delete complete
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3479): [NET] getaddrinfo-,err=8
D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3479): [NET] getaddrinfo-, 1
,D/libc    ( 3479): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3479): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(43b9cd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43b9cd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43bfbf38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=673815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43bfbf38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(441e3190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(441e3190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43180368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=733814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43180368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43704ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43704ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(438eb238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=793814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1250): Grow heap (frag case) to 12.653MB for 50416-byte allocation
,D/PMS     (  911): releaseWL(438eb238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43fb8618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43fb8618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(44025788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=853815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44025788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42904b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42904b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4310f6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=913815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4310f6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3479): [NET] getaddrinfo-,err=8
,D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3479): [NET] getaddrinfo-, 1
,D/libc    ( 3479): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3479): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(441ecc40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(441ecc40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(441ec3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=973814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(441ec3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(441ea158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  911): sending alarm PendingIntent{41d048f8: PendingIntentRecord{4242bd30 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782306, Int=0
,D/ConnectivityService(  911): Done.
,D/ConnectivityService(  911): Setting timer for 720seconds
,I/ActivityManager(  911): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3949 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  911): sending alarm PendingIntent{42557558: PendingIntentRecord{41fd9718 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449598457740, Int=10800000
V/AlarmManager(  911): sending alarm PendingIntent{4241c4e0: PendingIntentRecord{422cff28 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449599178179, Int=900000
,V/AlarmManager(  911): sending alarm PendingIntent{42293400: PendingIntentRecord{4409d748 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449599254870, Int=0
,W/ContextImpl( 3906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3906): call getInstance()
,D/SmartSyncUtils( 3906): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3906): MY_DEBUG = false
D/PMS     (  911): releaseWL(441ea158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  911): acquireWL(441da688): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3906 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3906): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3906): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3906): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3906): SettingOnTime = 1449640800000, randomSettingOnTime = 1449640429000
,D/SmartSyncScreenOnOffTimeReceiver( 3906): SettingOffTime = 1449626400000, randomSettingOffTime = 1449628057000
,D/SmartSyncScreenOnOffTimeReceiver( 3906): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3906): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3906): bNightModeTurnOffOnce = false
W/BatSI   (  911): Couldn't get kernel wake lock stats
D/PMS     (  911): releaseWL(441da688): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.aurora (3949/10049)
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/Process (  911): killProcessQuiet, pid=3685
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3685:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3685
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(43b5cf48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43b5cf48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(44050940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1033815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44050940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(438d1618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(438d1618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43ba0a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43ba0a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(440200a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1093814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(440200a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42a60380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42a60380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(44040550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1153814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44040550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4382de10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4382de10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(43b4a7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1213814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43b4a7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3479): [NET] getaddrinfo-,err=8
D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3479): [NET] getaddrinfo-, 1
,D/libc    ( 3479): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3479): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(43fbacd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43fbacd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42983118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1273815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42983118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(44021bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44021bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(429dc738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1333814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(429dc738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClearcutLoggerApiImpl( 1346): disconnect managed GoogleApiClient
,D/PMS     (  911): acquireWL(42431ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42431ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(437cba28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1393815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(437cba28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42463798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42463798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43446130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1453814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1250): Grow heap (frag case) to 12.653MB for 50416-byte allocation
,D/PMS     (  911): releaseWL(43446130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4409e558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4409e558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(4266a248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1513815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4266a248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3479): [NET] getaddrinfo-,err=8
D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3479): [NET] getaddrinfo-, 1
,D/libc    ( 3479): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3479): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(433f5258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(433f5258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43e77950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1573814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43e77950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42984320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42984320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43fbe6d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1633815, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43fbe6d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43fa4848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43fa4848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(440228f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1693814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(440228f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(44159838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(44159838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(433ac850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(433ac850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(425b1da8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1753814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(425b1da8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/PMS     (  911): acquireWL(43ba2a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43ba2a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(42bbcb88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1813814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42bbcb88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(441cf978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/PMS     (  911): releaseWL(441cf978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,I/ProcessStatsService(  911): Prepared write state in 43ms
,I/ProcessStatsService(  911): Pruning old procstats: /data/system/procstats/state-2015-12-07-22-15-00.bin
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3479): [NET] getaddrinfo-,err=8
D/libc    ( 3479): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3479): [NET] getaddrinfo-, 1
,D/libc    ( 3479): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3479): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(43b61918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/Process (  911): killProcessQuiet, pid=3448
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/PMS     (  911): releaseWL(43b61918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/ActivityManager(  911): Killing 3448:com.google.android.apps.plus/u0a160 (adj 15): empty for 1800s
,D/Process (  911): killProcessQuiet, pid=3756
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 ,
D/Process (  911): killProcessQuiet, pid=3702
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
,D/Process (  911): killProcessQuiet, pid=3737
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  911): Killing 3756:com.htc.providers.settings:remote/u0a17 (adj 15): empty for 1801s
I/ActivityManager(  911): Killing 3702:com.htc.cs.dm/u0a98 (adj 15): empty for 1801s
I/ActivityManager(  911): Killing 3737:com.htc.backup/1000 (adj 15): empty for 1801s
,D/Process (  911): killProcessQuiet, pid=3715
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  911): Killing 3715:com.google.android.apps.docs/u0a100 (adj 15): empty for 1801s
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/ActivityManager(  911): Recipient 3702
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3756
I/ActivityManager(  911): Recipient 3737
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3715
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3448
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(43f6f0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41fa4508: PendingIntentRecord{41d2e4c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1873814, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(43f6f0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,D/PMS     (  911): acquireWL(425063f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41d048f8: PendingIntentRecord{4242bd30 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1728698, Int=0
,D/Process (  911): killProcessQuiet, pid=3859
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  911): killProcessQuiet, pid=3479
I/ActivityManager(  911): Killing 3859:com.htc.mms.backupagent/u0a78 (adj 15): empty for 1800s
,I/ActivityManager(  911): Killing 3479:com.android.vending/u0a74 (adj 15): empty for 1800s
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
V/AlarmManager(  911): sending alarm PendingIntent{42005d78: PendingIntentRecord{4256ebc8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820459, Int=1800000
D/ConnectivityService(  911): Done.
V/AlarmManager(  911): sending alarm PendingIntent{424d2f78: PendingIntentRecord{425f9b78 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1850194, Int=0
D/PMS     (  911): acquireWL(43bafc68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
V/AlarmManager(  911): sending alarm PendingIntent{437760f8: PendingIntentRecord{43791308 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1862083, Int=0
V/AlarmManager(  911): sending alarm PendingIntent{4241c4e0: PendingIntentRecord{422cff28 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449600078179, Int=900000
D/ConnectivityService(  911): Setting timer for 720seconds
V/AlarmManager(  911): sending alarm PendingIntent{424ecaf0: PendingIntentRecord{423faa98 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449600111515, Int=0
I/ActivityManager(  911): Recipient 3859
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/AlarmManager(  911): sending alarm PendingIntent{4252cfe0: PendingIntentRecord{425957c0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449600149176, Int=1800000
,D/PMS     (  911): releaseWL(43bafc68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/LocationManagerService(  911): getAllProviders()=[passive, gps, network]
W/ContextImpl( 3906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,I/ActivityManager(  911): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1956/10029)
,I/ActivityManager(  911): Resuming delayed broadcast
V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  911): Recipient 3479
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  911): Scheduling restart of crashed service com.android.vending/com.google.android.finsky.services.DailyHygiene in 1000ms
,D/PMS     (  911): acquireWL(42493778): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.checkin.EventLogService$Receiver
,D/PMS     (  911): acquireWL(42538790): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42493778): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,I/EventLogService( 1956): Aggregate from 1449598349139 (log), 1449598349139 (data)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360022844
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023194
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023433
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023436
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023443
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027739
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): releaseWL(425063f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  911): releaseWL(42538790): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1346): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/libc    ( 1346): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1346): [NET] getaddrinfo-,err=8
D/libc    ( 1346): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1346): [NET] getaddrinfo-, 1
,D/libc    ( 1346): [NET] getaddrinfo_proxy+
,W/BatSI   (  911): Couldn't get kernel wake lock stats
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 1346): [NET] getaddrinfo_proxy-
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,I/ActivityManager(  911): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=3992 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,W/dalvikvm( 3992): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3992, uid=10074, userID:0
,D/Finsky  ( 3992): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (3992/10074)
,W/dalvikvm( 3992): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3992): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (3992/10074)
,D/Finsky  ( 3992): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3992): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3992): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3992): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3992): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3992): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3992): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3992): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3992, uid=10074, userID:0
,D/Finsky  ( 3992): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3992): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3992/10074)
,D/Ads     ( 3992): Skipping gmscore version check
,D/Finsky  ( 3992): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3992): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3992): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3992): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/libc    ( 3992): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3992): [NET] getaddrinfo-,err=8
D/libc    ( 3992): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3992): [NET] getaddrinfo-, 1
,D/libc    ( 3992): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3992): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3992): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3992/10074)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3992/10074)
,D/libc    ( 3992): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3992): [NET] getaddrinfo-,err=8
D/libc    ( 3992): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3992): [NET] getaddrinfo-, 1
,D/libc    ( 3992): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3992): [NET] getaddrinfo_proxy-
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3992/10074)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3992/10074)
,D/libc    ( 3992): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3992): [NET] getaddrinfo-,err=8
D/libc    ( 3992): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3992): [NET] getaddrinfo-, 1
,D/libc    ( 3992): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3992): [NET] getaddrinfo_proxy-
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3992/10074)
W/Finsky  ( 3992): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3992/10074)
,D/libc    ( 3992): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3992): [NET] getaddrinfo-,err=8
D/libc    ( 3992): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3992): [NET] getaddrinfo-, 1
,D/libc    ( 3992): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3992): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3992): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3992/10074)
D/Finsky  ( 3992): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 3992): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  911): acquireWL(441a3a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10074}
,V/AlarmManager(  911): sending alarm PendingIntent{43b81530: PendingIntentRecord{43f7f4b8 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1449600152069, Int=0
,D/Finsky  ( 3992): [1] DailyHygiene.reschedule: Scheduling new run in 98 minutes (failures=3)
,D/PMS     (  911): acquireWL(438d7910): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3992 10074 null
,D/Finsky  ( 3992): [421] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/PMS     (  911): releaseWL(441a3a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/DeviceConnectionService( 1199): client connected with version: 8296000
,D/libc    ( 3992): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3992): [NET] getaddrinfo-,err=8
D/libc    ( 3992): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3992): [NET] getaddrinfo-, 1
,D/libc    ( 3992): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3992): [NET] getaddrinfo_proxy-
D/PMS     (  911): releaseWL(438d7910): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/Process (  911): killProcessQuiet, pid=3818
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3818:com.test.thalitest/u0a389 (adj 15): empty for 1802s
,I/ActivityManager(  911): Recipient 3818
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(42553720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42553720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/PowerUI ( 1109): closing low battery warning: level=100
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/ContextImpl( 3906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,D/TetherSettings( 3268): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3268): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3268): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3268): Cust_ConnectToPC   : spcsc>false
D/        ( 3268): Cust_ConnectToPC   : IPT>true
D/        ( 3268): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3268): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3268): Index of the first 1 = 3
W/ContextImpl( 3268): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3268): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3268): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3268): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3268): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3268): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4043): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4043): ====startRecUseTime====
D/htc.customization.log.level( 4043):  is 
W/CustomizationLogLevel( 4043): Level value is invalid, use default level 2
D/CustomizationManager( 4043):  Read ACC file spent 0.126 (s)
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4043): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4043): Parsing tag category name = system
I/CustomizationCIDLoader( 4043): Parsing tag category name = application
I/CustomizationCIDLoader( 4043): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4043): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4043): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4043): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4043): Parsing tag category name = Settings
D/CustomizationManager( 4043):  Read CID file spent 0.188 (s)
D/CustomizationManager( 4043):  All configurations done spent 0.188 (s)
W/HtcNativeFlag( 4043): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4043): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4043): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4043): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4043, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/asset   (  911): Copying FileAsset 0x6be58f60 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  911): Skipping PackageSetting{42127468 com.example.hello/10396} due to missing metadata
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1531): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1531): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1531): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1199): Ignoring removeGeofence because network location is disabled.
D/PMS     (  911): acquireWL(43f97f98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1275): Cleaning up data for package: com.test.thalitest
I/Launcher( 1250): Deferring update until onResume
D/Launcher( 1250): waitUntilResume // bindAppsRemoved
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PMS     (  911): releaseWL(43f97f98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/[PluginManager]RegisterService( 1295): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1295): handle notify Blinkfeed plugin client changed
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1250): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/IcingCorporaProvider( 2553): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4057 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  911): acquireWL(43c58838): PARTIAL_WAKE_LOCK  Icing 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2553): UpdateCorporaTask done [took 307 ms] updated apps [took 306 ms] 
W/PackageManager(  911): Unable to load service info ResolveInfo{43659c68 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
W/GAV2    ( 4057): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  911): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
E/SQLiteLog( 4057): (3850) statement aborts at 59: [DELETE FROM CachedSearch111 WHERE timestamp<?] disk I/O error
E/SQLiteDBG( 4057): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.apps.docs/databases/DocList.db, handle = 0x5c9e46e8
E/AbstractDatabaseInstance( 4057): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4057): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 4057): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 4057): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AbstractDatabaseInstance( 4057): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 4057): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 4057): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AbstractDatabaseInstance( 4057): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4057): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4057): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4057): 	at fv.run(DocsApplication.java:288)
W/dalvikvm( 4057): threadid=11: thread exiting with uncaught exception (group=0x41687e30)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
D/Process ( 4057): killProcess, pid=4057
D/Process ( 4057): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 4057): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4057): Process: com.google.android.apps.docs, PID: 4057
E/AndroidRuntime( 4057): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4057): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4057): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4057): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4057): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4057): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4057): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime( 4057): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime( 4057): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime( 4057): 	at fv.run(DocsApplication.java:288)
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  911): Recipient 4057
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4057) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
F/ProcessStats(  911): Starting service ServiceState{441a6378 com.google.android.apps.docs.sync.syncadapter.ContentSyncService pkg=com.google.android.apps.docs proc=441a6378} without owner
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  911): start
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1449600160654.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  911): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  911): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  911): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  911): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  911): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  911): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4131)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
E/ErrorReport(  911): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
E/ErrorReport(  911): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 18 more
I/TrimMemoryManager( 1250): [trimMemory] 5
W/AtomicFile(  911): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  911): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4081 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/ContextImpl( 4081): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
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
W/dalvikvm( 4081): threadid=10: thread exiting with uncaught exception (group=0x41687e30)
E/ActivityManager(  911): App crashed! Process: com.android.keychain
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
D/Process ( 4081): killProcess, pid=4081
D/Process ( 4081): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449600161048.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  911): Recipient 4081
I/ActivityManager(  911): Process com.android.keychain (pid 4081) has died.
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10577ms
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4095 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 4095): getInstance(Context context)
D/AppTag  ( 4095): getInstance(Context context)
D/AppTag  ( 4095): onCreate()
I/ActivityManager(  911): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4109 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
F/ProcessStats(  911): Starting service ServiceState{441a6378 com.google.android.apps.docs.sync.syncadapter.ContentSyncService pkg=com.google.android.apps.docs proc=441a6378} without owner
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1449600161160.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  911): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  911): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  911): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  911): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  911): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  911): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16827)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16804)
E/ErrorReport(  911): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1897)
E/ErrorReport(  911): 	at com.android.server.am.ActiveServices.publishServiceLocked(ActiveServices.java:868)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.publishService(ActivityManagerService.java:13917)
E/ErrorReport(  911): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:898)
E/ErrorReport(  911): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
E/ErrorReport(  911): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  911): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 23 more
I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  911): acquireWL(44068470): PARTIAL_WAKE_LOCK  AsyncService 0x1 4109 10160 null
D/PMS     (  911): releaseWL(44068470): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/SQLiteDatabase( 4109): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
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
E/SQLiteDatabase( 4109): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4109): 	at del.a(PG:264)
E/SQLiteDatabase( 4109): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4109): 	at java.lang.Thread.run(Thread.java:864)
D/Process (  911): killProcessQuiet, pid=3887
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Killing 3887:com.htc.bgp/u0a14 (adj 15): empty for 1806s
E/SQLiteDatabase( 4109): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
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
E/SQLiteDatabase( 4109): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4109): 	at del.a(PG:264)
E/SQLiteDatabase( 4109): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4109): 	at java.lang.Thread.run(Thread.java:864)
D/PackageBroadcastService( 1956): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/AccountUtils( 1956): Clearing selected account for com.test.thalitest
E/EsApplication( 4109): Failed app initialization
E/EsApplication( 4109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4109): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4109): 	at del.a(PG:264)
E/EsApplication( 4109): 	at eeq.run(PG:187)
E/EsApplication( 4109): 	at java.lang.Thread.run(Thread.java:864)
I/LocationSettingsChecker( 1956): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteDatabase( 1956): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1956): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1956): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1956): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1956): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1956): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1956): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1956): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1956): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1956): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1956): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1956): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1956): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1956): Opened phenotype.db in read-only mode
E/SQLiteOpenHelper( 1956): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1956): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1956): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1956): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1956): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1956): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1956): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1956): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1956): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1956): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1956): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1956): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1956): threadid=35: thread exiting with uncaught exception (group=0x41687e30)
E/AndroidRuntime( 1956): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1956): Process: com.google.android.gms, PID: 1956
E/AndroidRuntime( 1956): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1956): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1956): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1956): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1956): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1956): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1956): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1956): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1956): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1956): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms
W/BaseAppContext( 1956): Using Auth Proxy for data requests.
D/Process ( 1956): killProcess, pid=1956
I/Icing   ( 1956): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
D/Process ( 1956): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  911): Recipient 3887
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41b49f48 +
I/Prism.WidgetManager( 1250): onLoadItems() +
I/ActivityManager(  911): Recipient 1956
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.gms (pid 1956) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10094ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20094ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20094ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30094ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30094ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30094ms
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): handleWLDeath(43c58838): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  911): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService: pid=4136 uid=10100 gids={50100, 3003, 5012, 1028, 1015}

```
