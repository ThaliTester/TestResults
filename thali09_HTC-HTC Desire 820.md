#### Test 50650278cc6513d_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  913): mEventCount = 900
,E/cutils-trace( 3830): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3830): ====startRecUseTime====
D/htc.customization.log.level( 3830):  is 
W/CustomizationLogLevel( 3830): Level value is invalid, use default level 2
D/CustomizationManager( 3830):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3830): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3830): Parsing tag category name = system
I/CustomizationCIDLoader( 3830): Parsing tag category name = application
I/CustomizationCIDLoader( 3830): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3830): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3830): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3830): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3830): Parsing tag category name = Settings
D/CustomizationManager( 3830):  Read CID file spent 0.087 (s)
D/CustomizationManager( 3830):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 3830): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3830): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3830): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3830): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  913): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  913): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  913): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  913): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  913): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  913): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  913): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3830
D/PMS     (  913): acquireHCC(43376570): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 913 1000 null
D/PMS     (  913): acquireHCC(43f8d7f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 913 1000 null
W/asset   (  913): Copying FileAsset 0x5cc18c00 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  913): @test_code: getHtcIntentFlag: 0 obj: 1124945008
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
D/PMS     (  913): acquireWL(430cbdd8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 913 1000 null
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bc4d88
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
I/ActivityManager(  913): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3841 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 3841): Copying FileAsset 0x5decb428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1248): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3841): Binding Chromium to main looper Looper (main, tid 1) {41a76dd0}
I/LibraryLoader( 3841): Expected native library version number "",actual native library version number ""
I/chromium( 3841): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3841): Initializing chromium process, renderers=0
W/System.err(  913): java.lang.Throwable: stack dump
D/BluetoothManagerService(  913): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  913): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4301b2a8:true
W/System.err(  913): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  913): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  913): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  913): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  913): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3841): 1101581832: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  913): acquireWL(424fa568): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): acquireWL(4301b150): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  913): releaseWL(424fa568): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3841): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3841): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3841): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3841): Local Branch: 
I/Adreno-EGL( 3841): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3841): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3841):                  aa63bbd948f41d15fc72f585e
W/chromium( 3841): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3841): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3841): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3841): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3841): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3841): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3841): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3841): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3841): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3841): CordovaWebView is running on device made by: HTC
,W/AwContents( 3841): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  913): Disable input method client, pid=1248
,W/ResourceType( 3841): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3841): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41abe390, mServedView=org.apache.cordova.engine.SystemWebView{41a84120 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  913): Enable input method client, pid=3841
,W/AwContents( 3841): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  913): Displayed com.test.thalitest/.MainActivity: +261ms
D/PMS     (  913): releaseWL(430cbdd8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3841): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3841): JniHelper::setJavaVM(0x41551048), pthread_self() = 1556144936
,D/JX-Cordova( 3841): jxcore cordova android initializing
,W/dalvikvm( 3841): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 11.525MB for 63974-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 11.630MB for 143930-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 11.745MB for 215890-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 11.919MB for 323830-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 12.192MB for 485740-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 12.595MB for 728606-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 14.032MB for 1639352-byte allocation
,E/libc    ( 3841): mmap fail (pid 3841, tid 3841, size 0, flags 0x1, errno 22(Invalid argument))
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 15.437MB for 2459024-byte allocation
,W/PluginManager( 3841): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 33ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 17.463MB for 3688532-byte allocation
,W/jxcore-log( 3841): Initializing JXcore engine
,W/jxcore-log( 3841): JXcore engine is ready
,W/CpuWake (  913): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  913): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  913): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  913): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  913): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  913): <<release mCpuPerf_Freq wakelock
,D/PMS     (  913): releaseHCC(43376570): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  913): releaseHCC(43f8d7f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3841): Starting JXcore engine
,W/jxcore-log( 3841): Platform android
W/jxcore-log( 3841): 
,W/jxcore-log( 3841): Process ARCH arm
W/jxcore-log( 3841): 
,D/PMS     (  913): acquireWL(42541380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10074}
,V/AlarmManager(  913): sending alarm PendingIntent{438455c0: PendingIntentRecord{4241d238 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449586591425, Int=0
,I/ActivityManager(  913): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3885 uid=10078 gids={50078}
,V/AlarmManager(  913): sending alarm PendingIntent{41b536c8: PendingIntentRecord{4262dfb0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449586593237, Int=60000
,D/PMS     (  913): releaseWL(42541380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3885): SMSBackupAgentService started
,D/SMSBackup( 3885): Checking restore status
,D/SMSBackup( 3885): Restore complete
,D/SMSBackup( 3885): cancelCheckAlarm
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026442
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026796
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027067
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027176
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027197
,D/SMSBackup( 3885): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360031644
,D/Finsky  ( 3489): [359] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3489): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  913): killProcessQuiet, pid=3623
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3623:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3623
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3841): JXcore Cordova bridge is ready!
I/jxcore-log( 3841): 
,W/jxcore-log( 3841): JXcore engine is started
,I/chromium( 3841): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3841): Error!: missing ) after argument list
E/jxcore  ( 3841): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3841): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  913): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3841): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  913): acquireWL(4384e8b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 913 1000 null
,I/FeedHostManager( 1248): [onResume]
,I/FeedProviderManager( 1248): onResume
I/SocialFeedProvider( 1248): +onResume
I/SocialFeedProvider( 1248): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1248): -onResume
,I/ConnectivityHelper( 1248): [getCurrentConnectionType] no network connection
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.launcher (1248/10076)
,I/InputMethodManagerService(  913): Disable input method client, pid=3841
,I/InputMethodManagerService(  913): Enable input method client, pid=1248
,W/IInputConnectionWrapper( 3841): reportFullscreenMode on inactive InputConnection
,D/PMS     (  913): releaseWL(4384e8b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  913): killProcessQuiet, pid=3654
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  913): Killing 3654:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/PMS     (  913): releaseWL(4301b150): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  913): Recipient 3654
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/libEGL  ( 3841): call to OpenGL ES API with no current context (logged once per thread)
,V/LightsService(  913): setLight #0: color=#26
,V/LightsService(  913): setLight #0: color=#23
,V/LightsService(  913): setLight #0: color=#1c
,V/LightsService(  913): setLight #0: color=#16
,V/LightsService(  913): setLight #0: color=#14
,I/SensorManager(  913): mEventCount = 1050
,I/PMS     (  913): Going to sleep due to screen timeout...
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421228d8
W/PMS     (  913): mWirelessDisplayManager is null
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  913): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  913): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421228d8, eanble = 0, strlen(mName) = 59
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  913): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42356020
W/SensorService(  913): Listener[1] = com.htc.smartdim.sensor_eye@44177920
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  913): Couldn't get kernel wake lock stats
V/LightsService(  913): setLight #2: color=#0
D/qdlights(  913): set_light_buttons_func: on=0 brightness=0
V/LightsService(  913): setLight #0: color=#0
,D/SurfaceControl(  913): Excessive delay in blankDisplay() while turning screen off: 337ms
D/PMS     (  913): nativeSetInteractive:false
D/PMS     (  913): nativeSetInteractive:false done
D/PMS     (  913): nativeSetAutoSuspend:true
D/PMS     (  913): nativeSetAutoSuspend:true done
I/InputManager(  913): Cancel all due to getting PMS screen off broadcast
D/HABCtrl (  913): TPE algorithm. remove timeout.
D/PMS     (  913): OOBE c monitor 11
,V/KeyguardServiceDelegate(  913): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4257df68)
D/NfcService( 1231): ScreenObserver: OFF
D/NfcService( 1231): applyRouting - 0
,I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  913): screenObserver, isScreenOn=false
D/PMN     (  913): wakingUp
I/InputMethodManagerService(  913): Disable input method client, pid=1248
,D/NfcService( 1231): applyRouting -2
,V/KeyguardServiceDelegate(  913): **** SHOWN CALLED ****
D/PMS     (  913): acquireWL(43380b38): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
I/WindowManager(  913): No lock screen! windowToken=null
D/PMN     (  913): onScreenOn
D/PMS     (  913): acquireWL(43489298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
D/PMS     (  913): releaseWL(43489298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): releaseWL(43380b38): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WirelessDisplayService(  913): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2169): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2169): [MTP][onReceive]-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
,D/NfcService( 1231): applyRouting - 0
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1231): applyRouting -2
,D/AutoSetting( 1297): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  913): ACTION_SCREEN_ON
I/AlarmManager(  913): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  913): [AlarmQueuing] done recovering
I/AlarmManager(  913): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  913): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  913): acquireWL(4249e100): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
D/PMS     (  913): releaseWL(4249e100): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/AutoSetting( 1297): service - onCreate()
I/ClockThread( 1109): stop update clock
,D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_ON
D/TetherSettings( 3278): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 1
D/        ( 3278): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3278): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3278): Cust_ConnectToPC   : spcsc>false
D/        ( 3278): Cust_ConnectToPC   : IPT>true
D/        ( 3278): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3278): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3278): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3278): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3278): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1297): service - AddressCache: using context: com.htc.Weather
,D/WifiNative-wlan0(  913):    returned false
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
I/PSReceiver( 3278): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1297): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  913): request 423244f8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  913): provider request: passive ProviderRequest[ON interval=0]
W/ContextImpl( 3278): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0,
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/SmartNS_PSService( 3278): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3278): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3278):  defaultType:0
V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  913): updateScreenOn: false
,W/ActivityManager(  913): Disable JIT of com.htc.bgp
,I/ActivityManager(  913): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3910 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  913): acquireWL(424f7760): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(424f7760): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(41ddb258): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(41ddb258): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42356020
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42356020, eanble = 0, strlen(mName) = 91
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  913): Listener[0] = com.htc.smartdim.sensor_eye@44177920
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  913): goingToSleep
D/PMS     (  913): acquireWL(43ac6148): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 913 1000 null
,I/FeedHostManager( 1248): [onPause]
,I/FeedProviderManager( 1248): onPause
,I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bc4d88
,I/SocialFeedProvider( 1248): +onPause
,I/SocialFeedProvider( 1248): -onPause
D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  913): stopDataStallAlarm: current tag=23258 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  913):    returned false
D/AlarmManager(  913): ACTION_SCREEN_OFF
I/AlarmManager(  913): [AlarmQueuing] screen off now: 
I/AlarmManager(  913): [AlarmQueuing] data connection: true
I/AlarmManager(  913): [AlarmQueuing] wifi connection: false
D/PMS     (  913): acquireWL(42379d48): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 913 1000 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,I/CalendarProvider2( 3910): Created com.android.providers.calendar.CalendarAlarmManager@41ab2a58(com.android.providers.calendar.HtcCalendarProvider@41a9ade0)
D/PMS     (  913): releaseWL(42379d48): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/NetworkPolicy(  913): updateScreenOn: false
,D/CalendarProvider2( 3910): wait start:true
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
D/PMS     (  913): releaseWL(43ac6148): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/CalendarProvider2( 3910): wait end:false
,I/ActivityManager(  913): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3931 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  913): acquireWL(43385738): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43385738): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  913): acquireWL(43a500b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43a500b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1297): service - mHandler: cancel location update
,D/AutoSetting( 1297): service -           changes count: 0
,D/SmartSyncUtils( 3931): isEpsOn(), nState = 0
D/PMS     (  913): acquireWL(4337b480): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3931 1000 null
,D/PMS     (  913): releaseWL(4337b480): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 3931): getMobilePolicyEnabled, result = true
,W/ContextImpl( 3931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3931): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3931): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3931): isEpsOn(), nState = 0
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@44177920
,D/WifiService(  913): New client listening to asynchronous messages
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 1
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@44177920, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 0
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@44177920, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@44177920
,E/ActivityThread(  913): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@43f949a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@43f949a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  913): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  913): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  913): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  913): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  913): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  913): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  913): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 3910): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3910): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3783): ---------------------------------------------------
,D/ProviderChangeReceiver( 3783): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3783): start to updateAlertNotification!
,W/ContextImpl( 3797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3783): No fired or scheduled alerts
,D/HtcAlertUtils( 3783): -- cancelReminderNotification --
,D/HtcAlertUtils( 3783): broadcastExistReminder!
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  913): killProcessQuiet, pid=3675
,I/ActivityManager(  913): Killing 3675:com.htc.backup/1000 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  913): Recipient 3675
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  913): killProcessQuiet, pid=3353
,I/ActivityManager(  913): Killing 3353:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  913): Recipient 3353
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(430beb18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{422819a0: PendingIntentRecord{42443468 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=128048, Int=0
,D/PMS     (  913): releaseWL(430beb18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(43fbfa90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1343/10029)
,D/PMS     (  913): releaseWL(43fbfa90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4384e5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4384e5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{4337b058 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(43482578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ea8958: PendingIntentRecord{41ea88d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=132918, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43482578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1297): service - handleMessage() stop self
,D/AutoSetting( 1297): service - handleMessage() quit looper
,D/AutoSetting( 1297): service - onDestroy() END
,I/ActivityManager(  913): Killing 3693:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  913): killProcessQuiet, pid=3693
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  913): Recipient 3693
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  913): acquireWL(43f9a918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,D/GpsLocationProvider(  913): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  913): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  913): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  913): sending alarm PendingIntent{42040078: PendingIntentRecord{4203fff8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=144739, Int=0
D/PMS     (  913): acquireWL(436f3c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
V/AlarmManager(  913): sending alarm PendingIntent{4359ee48: PendingIntentRecord{424b3c48 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=147956, Int=0
V/AlarmManager(  913): sending alarm PendingIntent{42244170: PendingIntentRecord{42389a90 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=148838, Int=0
D/PMS     (  913): releaseWL(436f3c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/libc    (  913): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-,err=8
,D/libc    (  913): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  913): [NET] getaddrinfo-, 1
,D/libc    (  913): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/PMS     (  913): releaseWL(43f9a918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  913): [NET] getaddrinfo_proxy-
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(432078d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
I/BatteryService(  913): n_update end
D/PMS     (  913): releaseWL(432078d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  913): acquireWL(43815d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43815d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(43b5bc98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ea8958: PendingIntentRecord{41ea88d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=192918, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43b5bc98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(4361a990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{43f8c5e0: PendingIntentRecord{42443468 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=187665, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{42244170: PendingIntentRecord{42389a90 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=208861, Int=0
,D/libc    (  913): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-,err=8
D/libc    (  913): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  913): [NET] getaddrinfo-, 1
D/libc    (  913): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/PMS     (  913): releaseWL(4361a990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  913): [NET] getaddrinfo_proxy-
D/PMS     (  913): acquireWL(43fc2230): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1343/10029)
,D/PMS     (  913): releaseWL(43fc2230): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(42eaef40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
D/UsbnetService(  913): BroadcastReceiver::onReceive+
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): releaseWL(42eaef40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(439c54e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(439c54e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(43b2ecb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ea8958: PendingIntentRecord{41ea88d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=252918, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43b2ecb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(43a9e418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
,D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): releaseWL(43a9e418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(425c3530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
,D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(425c3530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(431cec78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ea8958: PendingIntentRecord{41ea88d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=312917, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(431cec78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(4306e5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4306e5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3489): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3489): [NET] getaddrinfo-,err=8
D/libc    ( 3489): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3489): [NET] getaddrinfo-, 1
,D/libc    ( 3489): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3489): [NET] getaddrinfo_proxy-
,D/PMS     (  913): acquireWL(425fb598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(425fb598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(43afcc10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ea8958: PendingIntentRecord{41ea88d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=372917, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43afcc10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(425bf4a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): releaseWL(425bf4a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): runPSCheck
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(424d19a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(424d19a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42616eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41ea8958: PendingIntentRecord{41ea88d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=432917, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42616eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}

```
