#### Test 50650278b1aec71_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
,I/SensorManager(  902): mEventCount = 900
E/cutils-trace( 3802): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3802): ====startRecUseTime====
D/htc.customization.log.level( 3802):  is 
W/CustomizationLogLevel( 3802): Level value is invalid, use default level 2
D/CustomizationManager( 3802):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3802): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3802): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3802): Parsing tag category name = system
I/CustomizationCIDLoader( 3802): Parsing tag category name = application
I/CustomizationCIDLoader( 3802): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3802): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3802): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3802): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3802): Parsing tag category name = Settings
D/CustomizationManager( 3802):  Read CID file spent 0.092 (s)
D/CustomizationManager( 3802):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 3802): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3802): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3802): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3802): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  902): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  902): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  902): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  902): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3802
D/PMS     (  902): acquireHCC(43823e30): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 902 1000 null
D/PMS     (  902): acquireHCC(4285d6f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 902 1000 null
W/asset   (  902): Copying FileAsset 0x6bb2c600 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  902): @test_code: getHtcIntentFlag: 0 obj: 1114952320
I/FeedHostManager( 1246): [onPause]
I/FeedProviderManager( 1246): onPause
I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42460170
I/SocialFeedProvider( 1246): +onPause
I/SocialFeedProvider( 1246): -onPause
D/PMS     (  902): acquireWL(4233e190): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 902 1000 null
I/ActivityManager(  902): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3813 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1246): [trimMemory] 20
W/asset   ( 3813): Copying FileAsset 0x5c7c44f0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3813): Binding Chromium to main looper Looper (main, tid 1) {41d93de8}
I/LibraryLoader( 3813): Expected native library version number "",actual native library version number ""
I/chromium( 3813): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3813): Initializing chromium process, renderers=0
D/BluetoothManagerService(  902): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  902): java.lang.Throwable: stack dump
D/BluetoothManagerService(  902): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425ff828:true
W/System.err(  902): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  902): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  902): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  902): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  902): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3813): 1104846264: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  902): acquireWL(427bc4c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  902): acquireWL(427652e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  902): releaseWL(427bc4c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3813): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3813): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3813): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3813): Local Branch: 
I/Adreno-EGL( 3813): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3813): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3813):                  aa63bbd948f41d15fc72f585e
W/chromium( 3813): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3813): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3813): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3813): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3813): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3813): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3813): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3813): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3813): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3813): CordovaWebView is running on device made by: HTC
,W/AwContents( 3813): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  902): Disable input method client, pid=1246
,W/ResourceType( 3813): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3813): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ddb340, mServedView=org.apache.cordova.engine.SystemWebView{41da10d0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1179): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1179): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1179): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1179): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  902): Enable input method client, pid=3813
I/ActivityManager(  902): Displayed com.test.thalitest/.MainActivity: +265ms
W/AwContents( 3813): nativeOnDraw failed; clearing to background color.
,D/PMS     (  902): releaseWL(4233e190): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3813): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3813): JniHelper::setJavaVM(0x41955010), pthread_self() = 1663286880
,D/JX-Cordova( 3813): jxcore cordova android initializing
,W/dalvikvm( 3813): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 11.524MB for 63974-byte allocation
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 11.559MB for 95956-byte allocation
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 11.630MB for 143930-byte allocation
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 11.745MB for 215890-byte allocation
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 11.919MB for 323830-byte allocation
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 12.595MB for 728606-byte allocation
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 13.193MB for 1092904-byte allocation
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 14.059MB for 1639352-byte allocation
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 15.438MB for 2459024-byte allocation
,V/LightsService(  902): setLight #0: color=#24
,I/dalvikvm-heap( 3813): Grow heap (frag case) to 17.451MB for 3688532-byte allocation
,V/LightsService(  902): setLight #0: color=#21
,V/LightsService(  902): setLight #0: color=#1a
,V/LightsService(  902): setLight #0: color=#14
,W/jxcore-log( 3813): Initializing JXcore engine
,W/jxcore-log( 3813): JXcore engine is ready
,W/jxcore-log( 3813): Starting JXcore engine
,W/CpuWake (  902): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  902): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  902): <<release mCpuPerf_Freq wakelock
,D/PMS     (  902): releaseHCC(43823e30): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  902): releaseHCC(4285d6f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3813): Platform android
W/jxcore-log( 3813): 
,W/jxcore-log( 3813): Process ARCH arm
W/jxcore-log( 3813): 
,I/jxcore-log( 3813): JXcore Cordova bridge is ready!
I/jxcore-log( 3813): 
,W/jxcore-log( 3813): JXcore engine is started
,I/chromium( 3813): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3813): Error!: missing ) after argument list
E/jxcore  ( 3813): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/ActivityManager(  902): mThumbnailWidth=360, mThumbnailHeight=640
,I/chromium( 3813): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,W/PluginManager( 3813): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().,
D/PMS     (  902): acquireWL(426c4a50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 902 1000 null
,I/FeedHostManager( 1246): [onResume]
,I/FeedProviderManager( 1246): onResume
I/SocialFeedProvider( 1246): +onResume
I/SocialFeedProvider( 1246): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1246): -onResume
,I/ConnectivityHelper( 1246): [getCurrentConnectionType] no network connection
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.launcher (1246/10076)
,I/InputMethodManagerService(  902): Disable input method client, pid=3813
,I/InputMethodManagerService(  902): Enable input method client, pid=1246
,W/IInputConnectionWrapper( 3813): reportFullscreenMode on inactive InputConnection
,D/PMS     (  902): releaseWL(426c4a50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  902): killProcessQuiet, pid=3296
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  902): Killing 3296:com.htc.mediamanager/u0a34 (adj 15): empty #17
,E/libEGL  ( 3813): call to OpenGL ES API with no current context (logged once per thread)
,D/PMS     (  902): releaseWL(427652e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  902): acquireWL(42624b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10074}
,V/AlarmManager(  902): sending alarm PendingIntent{427a3010: PendingIntentRecord{43f17ec8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449595628592, Int=0
,I/ActivityManager(  902): Recipient 3296
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3860 uid=10078 gids={50078}
,V/AlarmManager(  902): sending alarm PendingIntent{42678928: PendingIntentRecord{428bf0c0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449595634495, Int=60000
,D/PMS     (  902): releaseWL(42624b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3860): SMSBackupAgentService started
,D/SMSBackup( 3860): Checking restore status
,D/SMSBackup( 3860): Restore complete
,D/SMSBackup( 3860): cancelCheckAlarm
,D/SMSBackup( 3860): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360022966
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023404
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023500
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023503
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360027521
,D/Finsky  ( 3474): [362] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3474): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  902): killProcessQuiet, pid=3524
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3524:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3524
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PMS     (  902): Going to sleep due to screen timeout...
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42408180
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = CM36282 Light sensor
,D/WirelessDisplayService(  902): Screen File Receiver; callOnGoing: false, Screen On: false
W/PMS     (  902): mWirelessDisplayManager is null
W/BatSI   (  902): Couldn't get kernel wake lock stats
V/LightsService(  902): setLight #2: color=#0
D/qdlights(  902): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  902): setLight #0: color=#0
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42408180, eanble = 0, strlen(mName) = 59
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  902): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4235f1a0
W/SensorService(  902): Listener[1] = com.htc.smartdim.sensor_eye@425ffbb0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  902): Excessive delay in blankDisplay() while turning screen off: 317ms
D/PMS     (  902): nativeSetInteractive:false
D/NfcService( 1226): ScreenObserver: OFF
,D/NfcService( 1226): applyRouting - 0
D/PMS     (  902): nativeSetInteractive:false done
D/PMS     (  902): nativeSetAutoSuspend:true
D/PMS     (  902): nativeSetAutoSuspend:true done
D/HABCtrl (  902): TPE algorithm. remove timeout.
I/InputManager(  902): Cancel all due to getting PMS screen off broadcast
D/PMS     (  902): OOBE c monitor 11
I/InputMethodManagerService(  902): screenObserver, isScreenOn=false
I/InputMethodManagerService(  902): Disable input method client, pid=1246
,D/NfcService( 1226): applyRouting -2,
V/KeyguardServiceDelegate(  902): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43e11e48)
,I/IntentController( 1102): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  902): **** SHOWN CALLED ****
D/PMS     (  902): acquireWL(438b8d00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1226 1027 null
D/PMN     (  902): wakingUp
,D/WirelessDisplayService(  902): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  902): No lock screen! windowToken=null
D/PMS     (  902): releaseWL(438b8d00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  902): acquireWL(426fe520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  902): onScreenOn
I/BatteryService(  902): n_update end
D/PMS     (  902): releaseWL(426fe520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NfcService( 1226): applyRouting - 0
,D/MtpService( 2154): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2154): [MTP][onReceive]-
,D/NfcService( 1226): applyRouting -2
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_ON
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/AutoSetting( 1292): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  902): ACTION_SCREEN_ON
I/AlarmManager(  902): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  902): [AlarmQueuing] done recovering
I/AlarmManager(  902): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  902): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  902): acquireWL(43786ea8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1226 1027 null
D/PMS     (  902): releaseWL(43786ea8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/TetherSettings( 3260): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3260): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3260): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3260): Cust_ConnectToPC   : spcsc>false
D/        ( 3260): Cust_ConnectToPC   : IPT>true
D/        ( 3260): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3260): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3260): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3260): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3260): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 1
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1292): service - onCreate()
,D/WifiNative-wlan0(  902):    returned false
,D/AutoSetting( 1292): service - AddressCache: using context: com.htc.Weather
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
I/PSReceiver( 3260): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1292): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  902): request 421e03d8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  902): provider request: passive ProviderRequest[ON interval=0]
,I/ClockThread( 1102): stop update clock
V/SRS_Proc(  371): ParamSet string: screen_state=on
,I/SmartNS_PSService( 3260): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3260): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3260):  defaultType:0
,D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/ContextImpl( 3260): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  902): updateScreenOn: false
,W/ActivityManager(  902): Disable JIT of com.htc.bgp
,I/ActivityManager(  902): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3882 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  902): acquireWL(4358daa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1192 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): releaseWL(4358daa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): acquireWL(4393a280): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1192 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): releaseWL(4393a280): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4235f1a0
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4235f1a0, eanble = 0, strlen(mName) = 91
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  902): Listener[0] = com.htc.smartdim.sensor_eye@425ffbb0
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  902): goingToSleep
I/FeedHostManager( 1246): [onPause]
I/FeedProviderManager( 1246): onPause
,I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42460170
I/SocialFeedProvider( 1246): +onPause
,I/SocialFeedProvider( 1246): -onPause
D/PMS     (  902): acquireWL(43950fd0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 902 1000 null
D/AlarmManager(  902): ACTION_SCREEN_OFF
I/AlarmManager(  902): [AlarmQueuing] screen off now: 
I/AlarmManager(  902): [AlarmQueuing] data connection: true
,I/AlarmManager(  902): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  902): stopDataStallAlarm: current tag=19595 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  902):    returned false
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  902): acquireWL(439037c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 902 1000 null
D/PMS     (  902): releaseWL(439037c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  902): releaseWL(43950fd0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/ContactMessageStore( 1209): start background delete task...
D/ContactMessageStore( 1209): size: 0 , 0
,D/ContactMessageStore( 1209): Background delete complete
D/NetworkPolicy(  902): updateScreenOn: false
,I/CalendarProvider2( 3882): Created com.android.providers.calendar.CalendarAlarmManager@41dcfb40(com.android.providers.calendar.HtcCalendarProvider@41db7ec8)
,D/CalendarProvider2( 3882): wait start:true
,D/CalendarProvider2( 3882): wait end:false
,I/ActivityManager(  902): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3901 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] getTotalRam: 1873 Mb
D/PMS     (  902): acquireWL(441bae70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1192 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): releaseWL(441bae70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): acquireWL(43a4a9d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1192 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  902): releaseWL(43a4a9d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1292): service - mHandler: cancel location update
,D/AutoSetting( 1292): service -           changes count: 0
W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3901): isEpsOn(), nState = 0
D/PMS     (  902): acquireWL(43b7bd00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3901 1000 null
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3901): getMobilePolicyEnabled, result = true
D/PMS     (  902): releaseWL(43b7bd00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3901): isEpsOn(), nState = 0
D/SmartSyncUtils( 3901): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3901): isEpsOn(), nState = 0
D/WifiService(  902): New client listening to asynchronous messages
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425ffbb0
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 1
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425ffbb0, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = CM36282 Proximity sensor
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 0
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425ffbb0, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425ffbb0
E/ActivityThread(  902): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@420fd0e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@420fd0e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  902): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  902): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  902): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  902): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  902): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  902): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  902): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  902): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 3882): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3882): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3755): ---------------------------------------------------
,D/ProviderChangeReceiver( 3755): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3755): start to updateAlertNotification!
,W/ContextImpl( 3769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3755): No fired or scheduled alerts
,D/HtcAlertUtils( 3755): -- cancelReminderNotification --
,D/HtcAlertUtils( 3755): broadcastExistReminder!
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  902): killProcessQuiet, pid=2661
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 2661:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 2661
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  902): killProcessQuiet, pid=3336
,I/ActivityManager(  902): Killing 3336:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  902): Recipient 3336
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(428259b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  902): sending alarm PendingIntent{43e57e40: PendingIntentRecord{42829618 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121276, Int=0
,D/PMS     (  902): releaseWL(428259b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  902): acquireWL(433c1d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1328 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1328/10029)
,D/PMS     (  902): releaseWL(433c1d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{42cfc3b0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  902): acquireWL(43956d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(43956d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1292): service - handleMessage() stop self
,D/AutoSetting( 1292): service - onDestroy() END
,D/AutoSetting( 1292): service - handleMessage() quit looper
,D/Process (  902): killProcessQuiet, pid=3557
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3557:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3557
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(43c27fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  902): sending alarm PendingIntent{420d9a70: PendingIntentRecord{4285a8d8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138800, Int=0
,V/AlarmManager(  902): sending alarm PendingIntent{4260baa8: PendingIntentRecord{426159d8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140947, Int=0
,D/GpsLocationProvider(  902): ALARM_XTRA_TIMEOUT
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
V/AlarmManager(  902): sending alarm PendingIntent{42488fc8: PendingIntentRecord{426647b0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=140972, Int=0
,D/PMS     (  902): acquireWL(4393acb8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
D/PMS     (  902): releaseWL(43c27fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/GpsLocationProvider(  902): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  902): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  902): releaseWL(4393acb8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(43b7aa18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=147893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43b7aa18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  902): acquireWL(438a2a98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(438a2a98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1209): switchBindHtcMsgCursor: null
,D/PMS     (  902): acquireWL(44320c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(44320c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(43a8e368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  902): sending alarm PendingIntent{425f0058: PendingIntentRecord{42829618 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=181026, Int=0
,D/PMS     (  902): acquireWL(434ebc78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1328 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
V/AlarmManager(  902): sending alarm PendingIntent{42488fc8: PendingIntentRecord{426647b0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=200993, Int=0
D/PMS     (  902): releaseWL(43a8e368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1328/10029)
,D/PMS     (  902): releaseWL(434ebc78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  902): acquireWL(43365a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=207893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43365a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(438d2560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1102): closing low battery warning: level=100
,D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(438d2560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(433c19d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=267893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(433c19d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  902): acquireWL(442d75e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(442d75e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(4332f008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4332f008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(442e4518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=327893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(442e4518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  902): acquireWL(433935f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
,D/PMS     (  902): releaseWL(433935f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3474): [NET] getaddrinfo-,err=8
D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3474): [NET] getaddrinfo-, 1
D/libc    ( 3474): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3474): [NET] getaddrinfo_proxy-
,D/PMS     (  902): acquireWL(4437fab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4437fab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(44368120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=387893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(44368120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(44367d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(44367d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(44324b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=447893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(44324b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  902): acquireWL(44313650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(44313650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(4426e560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(4426e560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(43efb558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=507893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43efb558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  902): acquireWL(43efb3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43efb3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(43eea490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43eea490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43ea6958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=567893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43ea6958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43ea4eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
I/BatteryService(  902): n_update end
D/HtcPowerSaver(  902): updateBatteryInfo
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): releaseWL(43ea4eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43e05e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43e05e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1209): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1209): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1209): sku_id=99
D/ContactMessageStore( 1209): start background delete task...
,D/ContactMessageStore( 1209): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1209): size: 0 , 0
,D/ContactMessageStore( 1209): Background delete complete
,D/PMS     (  902): acquireWL(43a3df28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=627894, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43a3df28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4360eae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
D/PMS     (  902): releaseWL(4360eae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3474): [NET] getaddrinfo-,err=8
D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3474): [NET] getaddrinfo-, 1
,D/libc    ( 3474): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3474): [NET] getaddrinfo_proxy-
,D/PMS     (  902): acquireWL(423f1918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(423f1918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(4219f258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=687893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4219f258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(427cbdb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  902): updateBatteryInfo
,D/PMS     (  902): releaseWL(427cbdb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(421b3268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=747893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(421b3268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43e0b908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(43e0b908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(426cf6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=807893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(426cf6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(42595e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42595e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(436efb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(436efb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1102): closing low battery warning: level=100
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42043e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=867893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42043e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(426d0df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(426d0df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42332138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42332138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4263d6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=927893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4263d6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(428d2320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(428d2320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3474): [NET] getaddrinfo-,err=8
,D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3474): [NET] getaddrinfo-, 1
,D/libc    ( 3474): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3474): [NET] getaddrinfo_proxy-
,D/PMS     (  902): acquireWL(4267d5c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4267d5c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(428796f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=987894, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(428796f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): Sampling interval elapsed, updating statistics ..
,D/PMS     (  902): acquireWL(43011398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{4204f4e8: PendingIntentRecord{4262c890 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781324, Int=0
,D/ConnectivityService(  902): Done.
,D/ConnectivityService(  902): Setting timer for 720seconds
,I/ActivityManager(  902): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3954 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  902): sending alarm PendingIntent{425c7318: PendingIntentRecord{425a8cc0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449595742718, Int=10800000
,V/AlarmManager(  902): sending alarm PendingIntent{41da51d8: PendingIntentRecord{42ed8a50 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449595759240, Int=1800000
,V/AlarmManager(  902): sending alarm PendingIntent{41e82188: PendingIntentRecord{427168f8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449596463129, Int=900000
,V/AlarmManager(  902): sending alarm PendingIntent{43aca638: PendingIntentRecord{42e4b9f8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449596540972, Int=0
,D/PMS     (  902): acquireWL(426530e0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1947 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  902): acquireWL(442adfb0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1947 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  902): releaseWL(426530e0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 3901): call getInstance()
,D/SmartSyncUtils( 3901): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3901): MY_DEBUG = false
D/PMS     (  902): releaseWL(43011398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  902): acquireWL(4256eed8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3901 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3901): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3901): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3901): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 3901): SettingOnTime = 1449640800000, randomSettingOnTime = 1449639403000
,D/SmartSyncScreenOnOffTimeReceiver( 3901): SettingOffTime = 1449626400000, randomSettingOffTime = 1449626909000
,D/SmartSyncScreenOnOffTimeReceiver( 3901): bDayMode = false
,I/EventLogService( 1947): Aggregate from 1449594268094 (log), 1449593959213 (data)
D/SmartSyncScreenOnOffTimeReceiver( 3901): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3901): bNightModeTurnOffOnce = false
W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.aurora (3954/10049)
,D/PMS     (  902): releaseWL(4256eed8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360022966
,W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023404
,W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023500
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023503
,W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360027521
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/PMS     (  902): releaseWL(442adfb0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/Process (  902): killProcessQuiet, pid=3655
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3655:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3655
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(42896eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(42896eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(433fb8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(433fb8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(4433ab00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1047893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4433ab00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43a0d2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43a0d2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43872be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1107894, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43872be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(435cf578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/BatteryService(  902): n_update end
I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/PMS     (  902): releaseWL(435cf578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43a6c0c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43a6c0c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43e82380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1167893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43e82380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4381ab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4381ab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  902): acquireWL(43936248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1227893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43936248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43b6b610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(43b6b610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3474): [NET] getaddrinfo-,err=8
D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3474): [NET] getaddrinfo-, 1
,D/libc    ( 3474): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3474): [NET] getaddrinfo_proxy-
,D/PMS     (  902): acquireWL(42c8b150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42c8b150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(435cece0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1287893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(435cece0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(438f40e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(438f40e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(438a02a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1347893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(438a02a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(44293aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): releaseWL(44293aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(433873e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(433873e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43b6ea98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1407893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43b6ea98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43b177d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43b177d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(4382a3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1467894, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4382a3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(438f99d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
,I/BatteryService(  902): n_update end
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(438f99d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4395bc48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4395bc48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(438cc7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1527893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(438cc7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3474): [NET] getaddrinfo-,err=8
D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3474): [NET] getaddrinfo-, 1
,D/libc    ( 3474): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3474): [NET] getaddrinfo_proxy-
,D/PMS     (  902): acquireWL(438433a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(438433a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(43e98040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1587894, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43e98040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43a756d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43a756d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43887490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): releaseWL(43887490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(438e8830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1647894, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(438e8830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4394afc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4394afc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43816bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43816bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/PowerUI ( 1102): closing low battery warning: level=100
,D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(438f2508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1707893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(438f2508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(442d0498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(442d0498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(42741f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42741f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(43831bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1767893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43831bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(42fcb668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42fcb668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1102): closing low battery warning: level=100
,D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/PMS     (  902): acquireWL(43d9cf48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(43d9cf48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  902): acquireWL(43eaf5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1827893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  902): Prepared write state in 27ms
,I/ProcessStatsService(  902): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-13-00.bin
,D/PMS     (  902): releaseWL(43eaf5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4383c9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{4204f4e8: PendingIntentRecord{4262c890 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1728888, Int=0
,D/ConnectivityService(  902): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  902): sending alarm PendingIntent{422ab688: PendingIntentRecord{4284bab0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820482, Int=1800000
,D/PMS     (  902): acquireWL(43b2a310): PARTIAL_WAKE_LOCK  NetworkStats 0x1 902 1000 null
,V/AlarmManager(  902): sending alarm PendingIntent{43c03f68: PendingIntentRecord{43bfe138 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1849201, Int=0
V/AlarmManager(  902): sending alarm PendingIntent{43e86a30: PendingIntentRecord{43e86da0 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1861139, Int=0
,V/AlarmManager(  902): sending alarm PendingIntent{41e82188: PendingIntentRecord{427168f8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449597363129, Int=900000
,D/ConnectivityService(  902): Done.
,D/ConnectivityService(  902): Setting timer for 720seconds
,D/PMS     (  902): releaseWL(43b2a310): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  902): getAllProviders()=[passive, gps, network]
,W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  902): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1947/10029)
,I/ActivityManager(  902): Resuming delayed broadcast
,D/PMS     (  902): releaseWL(4383c9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3474): [NET] getaddrinfo-,err=8
D/libc    ( 3474): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3474): [NET] getaddrinfo-, 1
,D/libc    ( 3474): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3474): [NET] getaddrinfo_proxy-
W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/dalvikvm( 1328): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/libc    ( 1328): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1328): [NET] getaddrinfo-,err=8
D/libc    ( 1328): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1328): [NET] getaddrinfo-, 1
,D/libc    ( 1328): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 1328): [NET] getaddrinfo_proxy-
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/Process (  902): killProcessQuiet, pid=3442
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  902): killProcessQuiet, pid=3727
I/ActivityManager(  902): Killing 3442:com.google.android.apps.plus/u0a160 (adj 15): empty for 1800s
,I/ActivityManager(  902): Killing 3727:com.htc.providers.settings:remote/u0a17 (adj 15): empty for 1800s
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  902): killProcessQuiet, pid=3674
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  902): killProcessQuiet, pid=3707
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/Process (  902): killProcessQuiet, pid=3687
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3674:com.htc.cs.dm/u0a98 (adj 15): empty for 1800s
I/ActivityManager(  902): Killing 3707:com.htc.backup/1000 (adj 15): empty for 1801s
I/ActivityManager(  902): Killing 3687:com.google.android.apps.docs/u0a100 (adj 15): empty for 1801s
,I/ActivityManager(  902): Recipient 3442
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3727
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3707
I/ActivityManager(  902): Recipient 3674
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 3687
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(41ffe620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(41ffe620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
,I/IntentController( 1102): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1515): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1515): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1102): closing low battery warning: level=100
D/PowerUI ( 1102): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,I/BatteryController( 1102): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(44335b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{421dba90: PendingIntentRecord{4259ee70 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1887893, Int=0
,I/IntentController( 1102): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(44335b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4003): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4003): ====startRecUseTime====
D/htc.customization.log.level( 4003):  is 
W/CustomizationLogLevel( 4003): Level value is invalid, use default level 2
D/CustomizationManager( 4003):  Read ACC file spent 0.092 (s)
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
D/CustomizationManager( 4003):  Read CID file spent 0.143 (s)
D/CustomizationManager( 4003):  All configurations done spent 0.143 (s)
W/HtcNativeFlag( 4003): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4003): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4003): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4003): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  902): deletePackageAsUser: pkg=com.test.thalitest, pid=4003, uid=2000 user=0
D/Process (  902): killProcessQuiet, pid=3813
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
I/ActivityManager(  902): Killing 3813:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
D/Process (  902): killProcessQuiet, pid=3474
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  902): Killing 3474:com.android.vending/u0a74 (adj 15): empty for 1807s
W/asset   (  902): Copying FileAsset 0x6437d858 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 3474
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  902): Skipping PackageSetting{42423918 com.example.hello/10396} due to missing metadata
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1515): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1515): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1515): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1102): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1102): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1102): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1311): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1192): Ignoring removeGeofence because network location is disabled.
D/PMS     (  902): acquireWL(428b4968): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1192 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): releaseWL(428b4968): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1258): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/Launcher( 1246): Deferring update until onResume
D/Launcher( 1246): waitUntilResume // bindAppsRemoved
W/AccTypeManager( 1311): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1311): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1226): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/Prism.PackageStateRece_( 1246): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1292): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1292): handle notify Blinkfeed plugin client changed
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/IcingCorporaProvider( 2545): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ExternalAccountType( 1311): Unsupported attribute readOnly
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/ActivityManager(  902): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4018 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/InputMethodManagerService(  902): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
D/PMS     (  902): acquireWL(4426bdc0): PARTIAL_WAKE_LOCK  Icing 0x1 1947 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): releaseWL(4426bdc0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
D/PhoneApp( 1209): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  902): acquireWL(43e22a58): PARTIAL_WAKE_LOCK  Icing 0x1 1947 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2545): UpdateCorporaTask done [took 442 ms] updated apps [took 442 ms] 
E/SQLiteDatabase( 4018): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4018): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4018): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4018): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4018): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4018): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4018): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4018): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4018): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4018): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4018): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4018): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4018): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4018): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4018): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4018): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4018): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4018): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4018): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4018): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4018): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4018): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4018): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4018): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4018): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4018): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4018): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4018): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4018): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4018): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4018): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4018): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4018): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4018): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4018): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4018): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4018): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4018): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4018): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4018): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4018): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4018): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4018): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4018): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4018): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4018): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4018): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4018): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4018): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4018): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4018): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4018): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4018): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4018): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4018): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4018): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4018): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4018): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4018): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4018): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4018): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4018): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4018): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4018): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4018): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4018): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4018): threadid=11: thread exiting with uncaught exception (group=0x41966e30)
E/ActivityManager(  902): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4018): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4018): Process: com.google.android.apps.docs, PID: 4018
E/AndroidRuntime( 4018): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4018): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4018): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4018): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4018): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4018): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4018): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4018): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4018): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
D/Process ( 4018): killProcess, pid=4018
D/Process ( 4018): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  902): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4036 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 4018
I/ActivityManager(  902): Process com.google.android.apps.docs (pid 4018) has died.
I/TrimMemoryManager( 1246): [trimMemory] 5
W/ContextImpl( 4036): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  902): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4049 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4036): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4036): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4036): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4036): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4036): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4036): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4036): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4036): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4036): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4036): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4036): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4036): threadid=10: thread exiting with uncaught exception (group=0x41966e30)
E/AndroidRuntime( 4036): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4036): Process: com.android.keychain, PID: 4036
E/AndroidRuntime( 4036): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4036): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4036): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4036): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4036): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4036): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4036): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4036): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4036): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  902): App crashed! Process: com.android.keychain
D/ErrorReport(  902): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4049): getInstance(Context context)
D/AppTag  ( 4049): getInstance(Context context)
D/AppTag  ( 4049): onCreate()
D/Process ( 4036): killProcess, pid=4036
D/Process ( 4036): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  902): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4064 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
E/ErrorReport(  902): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  902): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449597444038.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  902): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  902): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  902): 	... 4 more
I/ActivityManager(  902): Recipient 4036
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41e28f90 +
I/Prism.WidgetManager( 1246): onLoadItems() +
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Process com.android.keychain (pid 4036) has died.
W/ActivityManager(  902): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/Icing   ( 1947): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
E/Icing   ( 1947): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1947): Could not init tag ds.tag.deleted
I/ActivityManager(  902): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
E/SQLiteDatabase( 4064): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4064): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4064): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4064): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4064): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4064): 	at del.a(PG:264)
E/SQLiteDatabase( 4064): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4064): 	at java.lang.Thread.run(Thread.java:864)
D/PackageBroadcastService( 1947): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1947): Clearing selected account for com.test.thalitest
E/SQLiteDatabase( 4064): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4064): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4064): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4064): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4064): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4064): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4064): 	at del.a(PG:264)
E/SQLiteDatabase( 4064): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4064): 	at java.lang.Thread.run(Thread.java:864)
E/EsApplication( 4064): Failed app initialization
E/EsApplication( 4064): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4064): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4064): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4064): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4064): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4064): 	at del.a(PG:264)
E/EsApplication( 4064): 	at eeq.run(PG:187)
E/EsApplication( 4064): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  902): acquireWL(42800100): PARTIAL_WAKE_LOCK  AsyncService 0x1 4064 10160 null

```
