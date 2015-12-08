#### Test 5065027865f659b_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  906): mEventCount = 1350
,E/cutils-trace( 3833): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3833): ====startRecUseTime====
D/htc.customization.log.level( 3833):  is 
W/CustomizationLogLevel( 3833): Level value is invalid, use default level 2
--------- beginning of /dev/log/system
D/PMS     (  906): acquireWL(43889ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
V/AlarmManager(  906): sending alarm PendingIntent{423dbb10: PendingIntentRecord{425427e0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449598356445, Int=1800000
D/PMS     (  906): acquireWL(43871e20): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1208 10028 null
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3842 uid=10077 gids={50077}
V/AlarmManager(  906): sending alarm PendingIntent{425c5d30: PendingIntentRecord{425c5c90 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449598356522, Int=60000
D/PMS     (  906): releaseWL(43889ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  906): acquireWL(4385d988): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1208 10028 null
I/EventLogService( 1208): Aggregate from 1449596556401 (log), 1449596556401 (data)
D/PMS     (  906): releaseWL(43871e20): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
D/SMSBackup( 3842): SMSBackupAgentService started
D/SMSBackup( 3842): Checking restore status
D/SMSBackup( 3842): Restore complete
D/SMSBackup( 3842): cancelCheckAlarm
D/SMSBackup( 3842): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  906): killProcessQuiet, pid=3674
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3674:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
W/EventLogAggregator( 1208): Unknown tag: install_package_attempt
W/EventLogAggregator( 1208): Unknown tag: snet
W/EventLogAggregator( 1208): Unknown tag: snet_gcore
D/CustomizationManager( 3833):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3833): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3833): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3833): Parsing tag category name = system
I/CustomizationCIDLoader( 3833): Parsing tag category name = application
I/CustomizationCIDLoader( 3833): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3833): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3833): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3833): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3833): Parsing tag category name = Settings
D/CustomizationManager( 3833):  Read CID file spent 0.120 (s)
D/CustomizationManager( 3833):  All configurations done spent 0.120 (s)
W/HtcNativeFlag( 3833): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3833): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3833): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3833): Fail to get flag for type 'language', use default value: -1
D/PMS     (  906): releaseWL(4385d988): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Recipient 3674
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1136441224
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3833
D/PMS     (  906): acquireHCC(437eef68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(437e7e48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
I/FeedHostManager( 1251): [onPause]
I/FeedProviderManager( 1251): onPause
I/FeedHostManager( 1251): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c72f78
I/SocialFeedProvider( 1251): +onPause
I/SocialFeedProvider( 1251): -onPause
D/PMS     (  906): acquireWL(437d5300): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3858 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1251): [trimMemory] 20
W/asset   ( 3858): Copying FileAsset 0x5c789428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3858): Binding Chromium to main looper Looper (main, tid 1) {41b65200}
I/LibraryLoader( 3858): Expected native library version number "",actual native library version number ""
I/chromium( 3858): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3858): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(43735080): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): acquireWL(4372c8d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(43735080): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43720b38:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3858): 1102556216: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3858): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3858): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3858): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3858): Local Branch: 
I/Adreno-EGL( 3858): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3858): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3858):                  aa63bbd948f41d15fc72f585e
W/chromium( 3858): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3858): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3858): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3858): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3858): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3858): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3858): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3858): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3858): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3858): CordovaWebView is running on device made by: HTC
,W/AwContents( 3858): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1251
,W/ResourceType( 3858): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3858): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bac1c0, mServedView=org.apache.cordova.engine.SystemWebView{41b71f50 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1188): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1188): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  906): Enable input method client, pid=3858
W/AwContents( 3858): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +273ms
,D/PMS     (  906): releaseWL(437d5300): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3858): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3858): JniHelper::setJavaVM(0x41721010), pthread_self() = 1556877736
,D/JX-Cordova( 3858): jxcore cordova android initializing
W/dalvikvm( 3858): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 11.507MB for 63974-byte allocation
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 11.564MB for 95956-byte allocation
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 11.646MB for 143930-byte allocation
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 11.765MB for 215890-byte allocation
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 11.933MB for 323830-byte allocation
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 12.595MB for 728606-byte allocation
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 13.192MB for 1092904-byte allocation
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 14.103MB for 1639352-byte allocation
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 15.444MB for 2459024-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(437eef68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(437e7e48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3858): Grow heap (frag case) to 17.544MB for 3688532-byte allocation
,W/jxcore-log( 3858): Initializing JXcore engine
,W/jxcore-log( 3858): JXcore engine is ready
,W/jxcore-log( 3858): Starting JXcore engine
,W/jxcore-log( 3858): Platform android
W/jxcore-log( 3858): 
,W/jxcore-log( 3858): Process ARCH arm
W/jxcore-log( 3858): 
,D/PMS     (  906): releaseWL(4372c8d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3858): JXcore Cordova bridge is ready!
I/jxcore-log( 3858): 
,W/jxcore-log( 3858): JXcore engine is started
,I/chromium( 3858): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3858): Error!: missing ) after argument list
E/jxcore  ( 3858): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3858): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3858): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 30ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  906): acquireWL(4367fb00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
,I/FeedHostManager( 1251): [onResume]
,I/FeedProviderManager( 1251): onResume
,I/ConnectivityHelper( 1251): [getCurrentConnectionType] no network connection
,I/SocialFeedProvider( 1251): +onResume
I/SocialFeedProvider( 1251): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1251): -onResume
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1251/10075)
,I/InputMethodManagerService(  906): Disable input method client, pid=3858
,I/InputMethodManagerService(  906): Enable input method client, pid=1251
,W/IInputConnectionWrapper( 3858): reportFullscreenMode on inactive InputConnection
,D/PMS     (  906): releaseWL(4367fb00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  906): killProcessQuiet, pid=3391
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  906): Killing 3391:com.google.android.music:main/u0a154 (adj 15): empty #17
,E/libEGL  ( 3858): call to OpenGL ES API with no current context (logged once per thread),
,I/ActivityManager(  906): Recipient 3391
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  906): Client com.google.android.music (pid 3391): Died!
,I/PMS     (  906): Going to sleep due to screen timeout...
,W/PMS     (  906): mWirelessDisplayManager is null
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/BatSI   (  906): Couldn't get kernel wake lock stats
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4224af20
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4224af20, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42396dd0
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@425db360
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 372ms
D/PMS     (  906): nativeSetInteractive:false
,D/PMS     (  906): nativeSetInteractive:false done
,D/PMS     (  906): nativeSetAutoSuspend:true
,D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
,D/PMS     (  906): OOBE c monitor 11
,I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@441eae80)
D/NfcService( 1231): ScreenObserver: OFF
,D/NfcService( 1231): applyRouting - 0
,D/NfcService( 1231): applyRouting -2
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
D/PMN     (  906): wakingUp
I/InputMethodManagerService(  906): Disable input method client, pid=1251
D/PMS     (  906): acquireWL(42b4b738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): acquireWL(42b36ea0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
,D/PMS     (  906): releaseWL(42b4b738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(42b36ea0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PMN     (  906): onScreenOn
,I/IntentController( 1112): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2207): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2207): [MTP][onReceive]-
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,W/ActivityManager(  906): Disable JIT of com.htc.bgp
D/NfcService( 1231): applyRouting - 0
,D/NfcService( 1231): applyRouting -2
D/PMS     (  906): acquireWL(42a0dd68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
D/PMS     (  906): releaseWL(42a0dd68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ActivityManager(  906): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3910 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/ClockThread( 1112): stop update clock
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  906):    returned false
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/NetworkPolicy(  906): updateScreenOn: false
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/CalendarProvider2( 3910): Created com.android.providers.calendar.CalendarAlarmManager@41b9fac8(com.android.providers.calendar.HtcCalendarProvider@41b87e50)
D/PMS     (  906): acquireWL(438a5570): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1401 10028 null
,D/PMS     (  906): releaseWL(438a5570): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/CalendarProvider2( 3910): wait start:true
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42396dd0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42396dd0, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@425db360
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(438989a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19917 mDataStallAlarmIntent=null
I/FeedHostManager( 1251): [onPause]
,I/FeedProviderManager( 1251): onPause
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906):    returned false
,I/FeedHostManager( 1251): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c72f78
I/SocialFeedProvider( 1251): +onPause
I/SocialFeedProvider( 1251): -onPause
I/AlarmManager(  906): [AlarmQueuing] wifi connection: false
D/PMS     (  906): acquireWL(43878118): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43878118): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/CalendarProvider2( 3910): wait end:false
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/NetworkPolicy(  906): updateScreenOn: false
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3929 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ContactMessageStore( 1224): start background delete task...
D/ContactMessageStore( 1224): size: 0 , 0
,D/ContactMessageStore( 1224): Background delete complete
D/PMS     (  906): releaseWL(438989a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(437ea170): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1401 10028 null
D/PMS     (  906): acquireWL(437e8880): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3929 1000 null
,D/PMS     (  906): releaseWL(437ea170): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/SmartSyncUtils( 3929): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(437e8880): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1385): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3325): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3325): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3325): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3325): Cust_ConnectToPC   : spcsc>false
D/        ( 3325): Cust_ConnectToPC   : IPT>true
D/        ( 3325): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3325): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3325): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3325): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1385): service - onCreate()
,D/AutoSetting( 1385): service - AddressCache: using context: com.htc.Weather
,I/ActivityManager(  906): Delay finish: com.android.settings/.NSReceiver
D/LocationManagerService(  906): request 42587838 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/SmartSyncUtils( 3929): getMobilePolicyEnabled, result = true
,I/PSReceiver( 3325): onReceive:android.intent.action.USER_PRESENT
I/ActivityManager(  906): Resuming delayed broadcast
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3325): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3325):  defaultType:0
I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3929): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3929): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3929): isEpsOn(), nState = 0
,D/WifiService(  906): New client listening to asynchronous messages
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425db360
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425db360, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425db360, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425db360
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425fd340 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425fd340 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/CalendarProvider2( 3910): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3910): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3701): ---------------------------------------------------
,D/ProviderChangeReceiver( 3701): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3701): start to updateAlertNotification!
,W/ContextImpl( 3715): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3701): No fired or scheduled alerts
,D/HtcAlertUtils( 3701): -- cancelReminderNotification --
,D/HtcAlertUtils( 3701): broadcastExistReminder!
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  906): killProcessQuiet, pid=3374
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3374:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3374
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3413
,I/ActivityManager(  906): Killing 3413:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3413
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1385): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1385): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1385): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{44254e80 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(43367b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=127201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43367b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4335d308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PMS     (  906): releaseWL(4335d308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1385): service - handleMessage() stop self
,D/AutoSetting( 1385): service - handleMessage() quit looper
,D/AutoSetting( 1385): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=3525
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3525:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3525
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42676f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{437e65d0: PendingIntentRecord{42466488 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140956, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{424b3348: PendingIntentRecord{4251a650 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141359, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
V/AlarmManager(  906): sending alarm PendingIntent{422ee518: PendingIntentRecord{42388c48 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146212, Int=0
,D/PMS     (  906): acquireWL(426630d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  906): [NET] getaddrinfo_proxy-
D/PMS     (  906): releaseWL(42676f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): releaseWL(426630d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(4259fec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4259fec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1224): switchBindHtcMsgCursor: null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(424ed5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=187202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(424ed5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424dc558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424dc558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  906): [NET] getaddrinfo_proxy-
D/PMS     (  906): acquireWL(424327a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{422ee518: PendingIntentRecord{42388c48 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=206240, Int=0
D/PMS     (  906): releaseWL(424327a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(423f9b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(423f9b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(41f72d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=247201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41f72d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41f14de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41f14de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(41ee65b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(41ee65b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(41e2fdf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=307202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41e2fdf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43404b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43404b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(41f69828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/PMS     (  906): releaseWL(41f69828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NotificationStore( 1342): System rebooted after Notification storage file was last written
,I/NotificationStore( 1342): Deleting the file
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 3591): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3591): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3591): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3591): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41bd0ea0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 3 10 4 12
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3591): [NET] getaddrinfo-,err=8
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3591): [NET] getaddrinfo-, 1
,D/libc    ( 3591): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3591): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3591): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  906): acquireWL(42396b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=367201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42396b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41bfbb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41bfbb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42615350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(42615350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(43265dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=427201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43265dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424f2340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(424f2340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4334e300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4334e300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43fbb578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=487201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43fbb578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c2adb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c2adb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(423dd648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(423dd648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(425542d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=547201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425542d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41df3e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41df3e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424da708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424da708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42c81168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=607201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c81168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42566e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  906): releaseWL(42566e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1224): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1224): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1224): sku_id=99
,D/ContactMessageStore( 1224): start background delete task...
,D/ContactMessageStore( 1224): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1224): size: 0 , 0
,D/ContactMessageStore( 1224): Background delete complete
,D/PMS     (  906): acquireWL(42172778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42172778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3591): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3591): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3591): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3591): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41cb04e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3591): [NET] getaddrinfo-,err=8
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3591): [NET] getaddrinfo-, 1
I/RemoteViews.Performance( 1112): com.google.android.gms 1 9 3 12
,D/libc    ( 3591): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3591): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3591): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(42679240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=667202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42679240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(441c4b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(441c4b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425aac10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=727202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425aac10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437c1480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437c1480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PowerUI ( 1112): closing low battery warning: level=100
D/HtcPowerSaver(  906): Checking...
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): >> updateStatus
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424daa98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424daa98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(431bec30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=787202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431bec30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4235b978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4235b978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42662288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/PMS     (  906): releaseWL(42662288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(431febe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=847201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431febe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427cf3a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427cf3a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(42575630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=907201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42575630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42b0f998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42b0f998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44447f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(44447f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,E/PlayEventLogger( 3591): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3591): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3591): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3591): 	at dalvik.system.NativeStart.run(Native Method)
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3591): [NET] getaddrinfo-,err=8
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3591): [NET] getaddrinfo-, 1
,D/libc    ( 3591): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41fec3c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3591): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3591): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 10 3 12
,D/PMS     (  906): acquireWL(444d8e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=967201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(444d8e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42928de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42928de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43b70a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41e785b0: PendingIntentRecord{4248bd20 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782210, Int=0
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3988 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{4245cbe8: PendingIntentRecord{42374030 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449598472845, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{420daf00: PendingIntentRecord{42390818 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449599193130, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{425f7278: PendingIntentRecord{437dd0d8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449599264008, Int=0
,W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3929): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3929): MY_DEBUG = false
,D/SmartSyncUtils( 3929): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(43b70a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424bfc98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3929 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3929): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3929): [updateNmRange] USERNIGHT_TIMESTART = 2, USERNIGHT_TIMEEND = 7, nStart = 2, nEnd = 7, bNormalRange = true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
D/SmartSyncScreenOnOffTimeReceiver( 3929): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3929): SettingOnTime = 1449640800000, randomSettingOnTime = 1449640394000
D/SmartSyncScreenOnOffTimeReceiver( 3929): SettingOffTime = 1449622800000, randomSettingOffTime = 1449623312000
D/SmartSyncScreenOnOffTimeReceiver( 3929): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3929): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3929): bNightModeTurnOffOnce = false
D/PMS     (  906): releaseWL(424bfc98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (3988/10047)
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/ActivityManager(  906): Killing 2983:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=2983
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 2983
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(432d2fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  906): releaseWL(432d2fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(427f87c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1027202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427f87c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426456c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(426456c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42467ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42467ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42090638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1087201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42090638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41fc3160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41fc3160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(41f3cf58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1147201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41f3cf58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41ed9b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(41ed9b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4238c7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4238c7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41ec6b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1207201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41ec6b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41cf7938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41cf7938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{42040218 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3591): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3591): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3591): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3591): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1112): com.google.android.gms 2 13 4 12
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3591): [NET] getaddrinfo-,err=8
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3591): [NET] getaddrinfo-, 1
,D/libc    ( 3591): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3591): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3591): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(4242de88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1267202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4242de88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(420ffcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  906): releaseWL(420ffcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41e7a6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(41e7a6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4254c9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1327202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4254c9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42432e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42432e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42612090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42612090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(423d6ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1387201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423d6ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43ff80b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ff80b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42645d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1447201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42645d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4249f070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4249f070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42bd1e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  906): releaseWL(42bd1e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(441ba898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1507201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441ba898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42637760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42637760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4252d010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4252d010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3591): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3591): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3591): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3591): 	at dalvik.system.NativeStart.run(Native Method)
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3591): [NET] getaddrinfo-,err=8
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3591): [NET] getaddrinfo-, 1
,D/libc    ( 3591): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3591): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3591): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{4209bc28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 16 4 12
,D/PMS     (  906): acquireWL(42406b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1567201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42406b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(432bdbd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(432bdbd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42360688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(42360688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(425753e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1627201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425753e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41cb4df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41cb4df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425aacb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1687201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425aacb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43feda40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43feda40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44170210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44170210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/PowerUI ( 1112): closing low battery warning: level=100
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(429a5a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1747202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429a5a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424d07a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PMS     (  906): releaseWL(424d07a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43f29038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f29038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(43f82100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1807202, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f82100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c2cd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  906): n_update end
D/PowerUI ( 1112): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(43c2cd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(4267b608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  906): releaseWL(4267b608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
I/ProcessStatsService(  906): Prepared write state in 35ms
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-07-22-16-40.bin
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1540): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
I/RemoteViews( 1112): com.google.android.gms (false,0)
,E/PlayEventLogger( 3591): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3591): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3591): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3591): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3591): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3591): [NET] getaddrinfo-,err=8
D/libc    ( 3591): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3591): [NET] getaddrinfo-, 1
,D/libc    ( 3591): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3591): [NET] getaddrinfo_proxy-
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41baae10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3591): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1112): com.google.android.gms 3 12 3 12
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,D/PMS     (  906): acquireWL(441e3370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee5718: PendingIntentRecord{41ee3628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1867201, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441e3370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(441ed2b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1540): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1540): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  906): killProcessQuiet, pid=3786
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/PMS     (  906): releaseWL(441ed2b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/ActivityManager(  906): Killing 3786:com.htc.backup/1000 (adj 15): empty for 1800s
D/Process (  906): killProcessQuiet, pid=3766
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/Process (  906): killProcessQuiet, pid=3734
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  906): Killing 3766:com.google.android.apps.docs/u0a100 (adj 15): empty for 1800s
I/ActivityManager(  906): Killing 3734:com.google.android.partnersetup/u0a31 (adj 15): empty for 1800s
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/ActivityManager(  906): Recipient 3786
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3734
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3766
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43ac4160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/Process (  906): killProcessQuiet, pid=3591
I/ActivityManager(  906): Killing 3591:com.android.vending/u0a73 (adj 15): empty for 1817s
,V/AlarmManager(  906): sending alarm PendingIntent{41e785b0: PendingIntentRecord{4248bd20 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1731228, Int=0
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=3629
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=3804
I/ActivityManager(  906): Killing 3629:com.google.android.apps.plus/u0a160 (adj 15): empty for 1831s
,I/ActivityManager(  906): Killing 3804:com.htc.providers.settings:remote/u0a17 (adj 15): empty for 1831s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=3753
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 3753:com.htc.cs.dm/u0a98 (adj 15): empty for 1831s
V/AlarmManager(  906): sending alarm PendingIntent{423b0650: PendingIntentRecord{42542dc0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820955, Int=1800000
D/PMS     (  906): acquireWL(43f3c028): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): Done.
D/ConnectivityService(  906): Setting timer for 720seconds
V/AlarmManager(  906): sending alarm PendingIntent{42623888: PendingIntentRecord{42747298 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1853250, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{420daf00: PendingIntentRecord{42390818 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449600093130, Int=900000
V/AlarmManager(  906): sending alarm PendingIntent{43809958: PendingIntentRecord{425427e0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449600156658, Int=1800000
,I/ActivityManager(  906): Recipient 3629
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3804
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3591
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(43f3c028): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/ActivityManager(  906): Recipient 3753
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1208/10028)
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(42c9ddc0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1208 10028 null
,D/PMS     (  906): releaseWL(43ac4160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(4391ff90): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1208 10028 null
,D/PMS     (  906): releaseWL(42c9ddc0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 1208): Aggregate from 1449598356622 (log), 1449598356622 (data)
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): releaseWL(4391ff90): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4036): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4036): ====startRecUseTime====
D/htc.customization.log.level( 4036):  is 
W/CustomizationLogLevel( 4036): Level value is invalid, use default level 2
D/CustomizationManager( 4036):  Read ACC file spent 0.097 (s)
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4036): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4036): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4036): Parsing tag category name = system
I/CustomizationCIDLoader( 4036): Parsing tag category name = application
I/CustomizationCIDLoader( 4036): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4036): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4036): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4036): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4036): Parsing tag category name = Settings
D/CustomizationManager( 4036):  Read CID file spent 0.150 (s)
D/CustomizationManager( 4036):  All configurations done spent 0.150 (s)
W/HtcNativeFlag( 4036): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4036): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4036): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4036): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4036, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=3858
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 3858:com.test.thalitest/u0a348 (adj 15): stop com.test.thalitest
W/asset   (  906): Copying FileAsset 0x62b8d7e8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{4225d8f0 com.example.hello/10355} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1540): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1540): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1540): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1401): Ignoring removeGeofence because network location is disabled.
I/acms    ( 1773): Unregistering com.test.thalitest
E/acms    ( 1773): Could not unregister removed application com.test.thalitest
D/PMS     (  906): acquireWL(4252ef10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1401 10028 null
D/PMS     (  906): releaseWL(4252ef10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1311): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1311): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1277): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/Launcher( 1251): Deferring update until onResume
D/Launcher( 1251): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1311): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
D/PackageBroadcastService( 1208): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
D/PMS     (  906): acquireWL(4238d2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(4238d2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/Parcel  ( 1231): Reading a NULL string not supported here.
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4051 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/MultiDex( 4051): install
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/MultiDex( 4051): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4051): loading existing secondary dex files
I/MultiDex( 4051): load found 1 secondary dex files
I/MultiDex( 4051): install done
I/ActivityManager(  906): Delaying start of: ServiceRecord{4421aea0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
E/ExternalAccountType( 1311): Unsupported attribute readOnly
D/PhoneApp( 1224): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1208): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1208, uid=10028, userID:0
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4070 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PMS     (  906): acquireWL(438a6c80): PARTIAL_WAKE_LOCK  Icing 0x1 1208 10028 null
I/ProviderInstaller( 4051): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/Icing   ( 1208): doRemovePackageData com.test.thalitest
D/PMS     (  906): releaseWL(438a6c80): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4070): install
I/MultiDex( 4070): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4070): loading existing secondary dex files
I/MultiDex( 4070): load found 1 secondary dex files
I/MultiDex( 4070): install done
I/ProviderInstaller( 4070): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1385): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1385): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4088 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
W/FileUtils( 4051): Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4088, uid=10073, userID:0
D/Finsky  ( 4088): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4088/10073)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4088/10073)
E/SQLiteLog( 4051): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4051): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca588b0
E/DriveAsyncService( 4051): disk I/O error (code 3850)
E/DriveAsyncService( 4051): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4051): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4051): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4051): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4051): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4051): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4051): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4051): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4051): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4051): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4051): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4051): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4051): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4051): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Finsky  ( 4088): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 4088): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4088): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4088): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4088): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4088): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4088): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4088): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4088): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4088): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4088): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4088): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4088): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4088): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4088): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4088): threadid=25: thread exiting with uncaught exception (group=0x41732e30)
E/AndroidRuntime( 4088): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4088): Process: com.android.vending, PID: 4088
E/AndroidRuntime( 4088): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4088): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4088): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4088): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4088): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4088): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4088): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4088): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4088): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4088): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4088): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.vending
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4088, uid=10073, userID:0
D/Process (  906): killProcessQuiet, pid=3842
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3842:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1812s
D/Prism.PackageStateRece_( 1251): action: android.intent.action.PACKAGE_REMOVED
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4088): killProcess, pid=4088
D/Process ( 4088): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  906): Recipient 3842
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/IcingCorporaProvider( 2651): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4125 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 4051): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4051): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca588b0
E/DocListDatabase( 4051): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4051): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4051): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4051): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4051): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4051): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4051): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4051): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4051): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4051): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4051): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4051): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4051): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4051): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4051): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4051): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4051): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4051): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4051): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4051): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4051): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4051): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4051): threadid=1: thread exiting with uncaught exception (group=0x41732e30)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4088
I/ActivityManager(  906): Process com.android.vending (pid 4088) has died.
E/AndroidRuntime( 4051): FATAL EXCEPTION: main
E/AndroidRuntime( 4051): Process: com.google.android.gms.drive, PID: 4051
E/AndroidRuntime( 4051): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4051): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4051): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4051): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4051): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4051): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4051): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4051): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4051): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4051): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4051): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4051): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4051): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4051): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4051): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4051): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4051): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4051): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4051): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4051): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4051): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4051): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4051): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4051): 	... 10 more
E/SQLiteLog( 2651): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2651): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5cab3a40
W/dalvikvm( 2651): threadid=14: thread exiting with uncaught exception (group=0x41732e30)
E/AndroidRuntime( 2651): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2651): Process: com.google.android.googlequicksearchbox:search, PID: 2651
E/AndroidRuntime( 2651): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2651): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2651): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2651): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2651): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2651): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2651): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2651): 	at cid.d(PG:186)
E/AndroidRuntime( 2651): 	at clo.g(PG:594)
E/AndroidRuntime( 2651): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2651): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2651): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2651): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2651): 	at clr.tL(PG:827)
E/AndroidRuntime( 2651): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2651): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2651): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2651): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2651): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2651): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/TrimMemoryManager( 1251): [trimMemory] 5
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
D/Process ( 2651): killProcess, pid=2651
D/Process ( 4051): killProcess, pid=4051
D/Process ( 4051): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/Process ( 2651): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
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
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 4051
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4051) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
I/ActivityManager(  906): Recipient 2651
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2651): Died!
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2651) has died.
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 10920ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20919ms
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1251): loadItems() com.htc.launcher.pageview.WidgetManager@41bf5050 +
I/Prism.WidgetManager( 1251): onLoadItems() +
E/SQLiteDatabase( 4125): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4125): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4125): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4125): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4125): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4125): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4125): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4125): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4125): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4125): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4125): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4125): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4125): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4125): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4125): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4125): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4125): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4125): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4125): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4125): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4125): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4125): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4125): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4125): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4125): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4125): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4125): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4125): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4125): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4125): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4125): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4125): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4125): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4125): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4125): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4125): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4125): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4125): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4125): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4125): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4125): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4125): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4125): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4125): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4125): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4125): threadid=11: thread exiting with uncaught exception (group=0x41732e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4125): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4125): Process: com.google.android.apps.docs, PID: 4125
E/AndroidRuntime( 4125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4125): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4125): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4125): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4125): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4125): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4125): killProcess, pid=4125
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4143 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/SQLiteDatabase( 4125): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4125): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4125): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4125): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4125): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4125): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4125): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4125): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4125): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4125): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4125): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4125): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4125): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4125): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4125): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4125): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4125): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4125): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4125): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4125): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4125
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4125) has died.

```
