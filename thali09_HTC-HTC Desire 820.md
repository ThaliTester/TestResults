#### Test 568182540458528_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  911): acquireWL(42e7d960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10074}
V/AlarmManager(  911): sending alarm PendingIntent{42bd0d88: PendingIntentRecord{428e8370 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453856964763, Int=0
I/ActivityManager(  911): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4094 uid=10078 gids={50078}
V/AlarmManager(  911): sending alarm PendingIntent{42c7c5f8: PendingIntentRecord{42ca0428 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453856973440, Int=60000
D/PMS     (  911): releaseWL(42e7d960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,--------- beginning of /dev/log/main
D/SMSBackup( 4094): SMSBackupAgentService started
D/SMSBackup( 4094): Checking restore status
D/SMSBackup( 4094): Restore complete
D/SMSBackup( 4094): cancelCheckAlarm
D/SMSBackup( 4094): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024226
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024291
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024295
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024299
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025528
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025543
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028509
D/Finsky  ( 3711): [386] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3711): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  911): killProcessQuiet, pid=3481
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3481:com.google.android.music:main/u0a154 (adj 15): empty #17
E/cutils-trace( 4109): Error opening trace file: No such file or directory (2)
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3481
D/MediaRouterService(  911): Client com.google.android.music (pid 3481): Died!
D/CustomizationManager( 4109): ====startRecUseTime====
D/htc.customization.log.level( 4109):  is 
W/CustomizationLogLevel( 4109): Level value is invalid, use default level 2
D/CustomizationManager( 4109):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4109): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4109): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4109): Parsing tag category name = system
I/CustomizationCIDLoader( 4109): Parsing tag category name = application
I/CustomizationCIDLoader( 4109): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4109): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4109): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4109): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4109): Parsing tag category name = Settings
D/CustomizationManager( 4109):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4109):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 4109): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4109): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4109): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4109): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4109
D/PMS     (  911): acquireHCC(43ee80f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(449b8170): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
W/asset   (  911): Copying FileAsset 0x6dd092a8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1146811720
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42380748
I/SocialFeedProvider( 1250): +onPause
I/SocialFeedProvider( 1250): -onPause
D/PMS     (  911): acquireWL(43ddb530): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/ActivityManager(  911): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4120 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1250): [trimMemory] 20
I/SensorManager(  911): mEventCount = 750
W/asset   ( 4120): Copying FileAsset 0x5c703428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4120): Binding Chromium to main looper Looper (main, tid 1) {4226d2d8}
I/LibraryLoader( 4120): Expected native library version number "",actual native library version number ""
I/chromium( 4120): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4120): Initializing chromium process, renderers=0
,D/PMS     (  911): acquireWL(44a19740): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  911): releaseWL(44a19740): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@449a8558:true
D/PMS     (  911): acquireWL(44982208): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/BluetoothAdapter( 4120): 1109929232: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 4120): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4120): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4120): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4120): Local Branch: 
I/Adreno-EGL( 4120): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4120): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4120):                  aa63bbd948f41d15fc72f585e
W/chromium( 4120): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4120): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4120): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4120): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4120): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4120): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4120): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4120): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4120): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4120): CordovaWebView is running on device made by: HTC
W/AwContents( 4120): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  911): Disable input method client, pid=1250
I/ActivityManager(  911): Displayed com.test.thalitest/.MainActivity: +419ms
W/ResourceType( 4120): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4120): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@422b4298, mServedView=org.apache.cordova.engine.SystemWebView{4227a028 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  911): Enable input method client, pid=4120
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4120): nativeOnDraw failed; clearing to background color.
D/PMS     (  911): releaseWL(43ddb530): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4120): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4120): JniHelper::setJavaVM(0x41e24010), pthread_self() = 1663063064
I/chromium( 4120): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 11.996MB for 63974-byte allocation
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 12.050MB for 95956-byte allocation
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 12.132MB for 143930-byte allocation
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 12.251MB for 215890-byte allocation
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 12.424MB for 323830-byte allocation
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 13.075MB for 728606-byte allocation
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 13.671MB for 1092904-byte allocation
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 14.585MB for 1639352-byte allocation
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 15.837MB for 2459024-byte allocation
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
,D/PMS     (  911): releaseHCC(43ee80f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  911): releaseHCC(449b8170): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4120): Grow heap (frag case) to 18.022MB for 3688532-byte allocation
,W/jxcore-log( 4120): Initializing JXcore engine
,W/jxcore-log( 4120): JXcore engine is ready
,W/jxcore-log( 4120): Starting JXcore engine
,W/jxcore-log( 4120): Platform android
W/jxcore-log( 4120): 
,W/jxcore-log( 4120): Process ARCH arm
W/jxcore-log( 4120): 
,D/PMS     (  911): releaseWL(44982208): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/LightsService(  911): setLight #0: color=#24
,V/LightsService(  911): setLight #0: color=#21
,I/jxcore-log( 4120): JXcore Cordova bridge is ready!
I/jxcore-log( 4120): 
,W/jxcore-log( 4120): JXcore engine is started
V/LightsService(  911): setLight #0: color=#1a
,E/jxcore  ( 4120): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4120): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4120): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,V/LightsService(  911): setLight #0: color=#14
I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4120): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  911): acquireWL(44071488): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
,I/FeedHostManager( 1250): [onResume]
,I/FeedProviderManager( 1250): onResume
,I/ConnectivityHelper( 1250): [getCurrentConnectionType] no network connection
I/SocialFeedProvider( 1250): +onResume
I/SocialFeedProvider( 1250): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1250): -onResume
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.launcher (1250/10076)
,I/InputMethodManagerService(  911): Disable input method client, pid=4120
,W/IInputConnectionWrapper( 4120): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  911): Enable input method client, pid=1250
,D/PMS     (  911): releaseWL(44071488): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  911): killProcessQuiet, pid=3921
,I/ActivityManager(  911): Killing 3921:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,E/libEGL  ( 4120): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  911): Recipient 3921
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  911): Client connection lost with reason: 4
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42945c00
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42945c00, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42878038
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@42de13f8
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  911): Going to sleep due to screen timeout...
W/BatSI   (  911): Couldn't get kernel wake lock stats
W/PMS     (  911): mWirelessDisplayManager is null
D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 343ms
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
D/NfcService( 1230): ScreenObserver: OFF
,D/NfcService( 1230): applyRouting - 0
,D/NfcService( 1230): applyRouting -2
D/PMS     (  911): OOBE c monitor 11
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
I/InputMethodManagerService(  911): Disable input method client, pid=1250
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
D/PMS     (  911): acquireWL(42bb89d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43ddf3f0)
,I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  911): releaseWL(42bb89d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  911): wakingUp
,D/PMS     (  911): acquireWL(43f19050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  911): No lock screen! windowToken=null
D/PMN     (  911): onScreenOn
D/PMS     (  911): releaseWL(43f19050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  911): updateBatteryInfo
W/ActivityManager(  911): Disable JIT of com.htc.bgp
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 2027): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2027): [MTP][onReceive]-
,D/NfcService( 1230): applyRouting - 0
,D/NfcService( 1230): applyRouting -2
I/ActivityManager(  911): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4172 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
D/PMS     (  911): acquireWL(43588180): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
,I/ClockThread( 1109): stop update clock
D/PMS     (  911): releaseWL(43588180): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  911):    returned false
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  911): updateScreenOn: false
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/SensorManager(  911): mEventCount = 900
,I/CalendarProvider2( 4172): Created com.android.providers.calendar.CalendarAlarmManager@4229cc58(com.android.providers.calendar.HtcCalendarProvider@42284fe0)
D/PMS     (  911): acquireWL(43d79fc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(43d79fc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(4260a6f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/CalendarProvider2( 4172): wait start:true
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42878038
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,D/PMS     (  911): releaseWL(4260a6f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42878038, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@42de13f8
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  911): goingToSleep
,D/PMS     (  911): acquireWL(42bf1270): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
,D/CalendarProvider2( 4172): wait end:false
,I/FeedHostManager( 1250): [onPause]
,I/FeedProviderManager( 1250): onPause
,I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42380748
,I/SocialFeedProvider( 1250): +onPause
,I/SocialFeedProvider( 1250): -onPause
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20113 mDataStallAlarmIntent=null
D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
I/AlarmManager(  911): [AlarmQueuing] wifi connection: false
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  911):    returned false
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  911): acquireWL(428cc648): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/PMS     (  911): releaseWL(428cc648): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4194 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  911): releaseWL(42bf1270): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/NetworkPolicy(  911): updateScreenOn: false
D/ContactMessageStore( 1219): start background delete task...
D/ContactMessageStore( 1219): size: 0 , 0
D/ContactMessageStore( 1219): Background delete complete
,W/ContextImpl( 4194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  911): acquireWL(44685bd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(44685bd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44930a08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4194 1000 null
,D/SmartSyncUtils( 4194): isEpsOn(), nState = 0
D/PMS     (  911): acquireWL(42de04b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42de04b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(44930a08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4194): getMobilePolicyEnabled, result = true
,D/Process (  911): killProcessQuiet, pid=3463
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3463:com.htc.mediamanager/u0a34 (adj 15): empty #17
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1301): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1301): service - onCreate()
D/TetherSettings( 3428): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3428): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3428): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3428): Cust_ConnectToPC   : spcsc>false
D/        ( 3428): Cust_ConnectToPC   : IPT>true
D/        ( 3428): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3428): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AutoSetting( 1301): service - AddressCache: using context: com.htc.Weather
E/SmartNS_Utility( 3428): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3428): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3428): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3428): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  911): Recipient 3463
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 3428): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/LocationManagerService(  911): request 42ae09b0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
I/SmartNS_PSService( 3428): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3428): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3428):  defaultType:0
I/ActivityManager(  911): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,W/ContextImpl( 4194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4194): isEpsOn(), nState = 0
D/SmartSyncUtils( 4194): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4194): getMobilePolicyEnabled, result = true
D/WifiService(  911): New client listening to asynchronous messages
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42de13f8
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42de13f8, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42de13f8, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42de13f8
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42de1940 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42de1940 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/CalendarProvider2( 4172): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4172): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 4060): ---------------------------------------------------
,D/ProviderChangeReceiver( 4060): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4060): start to updateAlertNotification!
,W/ContextImpl( 4075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 4060): No fired or scheduled alerts
,D/HtcAlertUtils( 4060): -- cancelReminderNotification --
,D/HtcAlertUtils( 4060): broadcastExistReminder!
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  911): killProcessQuiet, pid=3506
,I/ActivityManager(  911): Killing 3506:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 3506
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1301): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1301): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1301): service - requestNLP() NetworkLocationProvider not enabled
,D/PMS     (  911): acquireWL(42c9f338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=121788, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42c9f338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{43fc4c40 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(449567c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(449567c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
,D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(4422fbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{43d8b040: PendingIntentRecord{43f416f0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137161, Int=0
,D/PMS     (  911): releaseWL(4422fbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1301): service - handleMessage() stop self
,D/AutoSetting( 1301): service - handleMessage() quit looper
,D/AutoSetting( 1301): service - onDestroy() END
,D/Process (  911): killProcessQuiet, pid=3777
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3777:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3777
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(44541340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{42c96380: PendingIntentRecord{442aa1d8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124108, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{42ad78c8: PendingIntentRecord{42befcc8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141538, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{42b91060: PendingIntentRecord{42b90fe0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141552, Int=0
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  911): [NET] getaddrinfo_proxy-
D/PMS     (  911): acquireWL(42c2ffb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2365 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2365/10029)
,D/PMS     (  911): releaseWL(42c2ffb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(42bac010): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(44541340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  911): releaseWL(42bac010): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  911): acquireWL(4499fcb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(4499fcb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1219): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(42924098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=181789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42924098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClearcutLoggerApiImpl( 2365): disconnect managed GoogleApiClient
,D/PMS     (  911): acquireWL(42dfa560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/PMS     (  911): releaseWL(42dfa560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): onReceive BATTERY_CHANGED
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(43eca730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{441f6fa0: PendingIntentRecord{442aa1d8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=183788, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{42ad78c8: PendingIntentRecord{42befcc8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201570, Int=0
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/PMS     (  911): acquireWL(4483a9b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2365 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(43eca730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2365/10029)
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    (  911): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(43de3ef0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4483a9b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43de3ef0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(44a1dd28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024111
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024226
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024291
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024295
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024299
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025528
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025543
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028509
,D/PMS     (  911): releaseWL(44a1dd28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42cdbc60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2365/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024226
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024291
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024295
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024299
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025528
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025543
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028509
,D/PMS     (  911): acquireWL(43e267b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2365 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1199): Vacuum at: now=1453857080101 tag=VacuumService
,D/PMS     (  911): releaseWL(42cdbc60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43e267b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42ca1198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024111
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024226
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024291
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024295
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024299
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025528
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025543
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028509
,D/PMS     (  911): releaseWL(42ca1198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43ecaa88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2365/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024111
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024226
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024291
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024295
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024299
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024305
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025528
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025543
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028509
,D/PMS     (  911): releaseWL(43ecaa88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4374fcb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(4374fcb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(438c6df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=241788, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(438c6df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(449c6898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(449c6898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(431c0518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(431c0518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  911): updateBatteryInfo
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(432ade60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=301789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(432ade60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4376a8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(4376a8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/PowerUI ( 1109): closing low battery warning: level=100
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43d35318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(43d35318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(436de250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=361789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(436de250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(44009ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44009ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(43d738f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/PMS     (  911): releaseWL(43d738f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): >> updateStatus
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(449dace8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=421789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(449dace8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43d742f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43d742f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(445ec260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=481789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(445ec260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42e19918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(42e19918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(42264058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=541789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42264058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(449ffc48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(449ffc48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(449babd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=601789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(449babd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(445687a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
I/BatteryService(  911): n_update end
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(445687a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1219): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1219): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1219): sku_id=99
,D/ContactMessageStore( 1219): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1219): start background delete task...
D/ContactMessageStore( 1219): size: 0 , 0
,D/ContactMessageStore( 1219): Background delete complete
,D/Process (  911): killProcessQuiet, pid=3957
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3957:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3957
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(443ed600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): releaseWL(443ed600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42923690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=661789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42923690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(44a00188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44a00188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42b42e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): releaseWL(42b42e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(447f7d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=721789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(447f7d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43293eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43293eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(43de90a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(43de90a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(449bff30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=781789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(449bff30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(44490f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44490f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42d00660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=841789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42d00660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(44003130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(44003130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(441cbe40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=901789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(441cbe40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(449c7740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(449c7740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(441e9f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(441e9f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderNotification, total:1
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
V/NotificationService(  911): batLight: plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c80000
D/qdlights(  911): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=98
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
W/ContextImpl( 4194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3428): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3428): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3428): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3428): Cust_ConnectToPC   : spcsc>false
D/        ( 3428): Cust_ConnectToPC   : IPT>true
,D/        ( 3428): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3428): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3428): Index of the first 1 = -1
,W/Settings( 3428): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3428): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3428): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
W/ContextImpl( 3428): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3428): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_NSReceiver( 3428): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3428): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(440b6790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=961789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(440b6790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(42469fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
,D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/BatteryService(  911): n_update end
D/PowerUI ( 1109): closing low battery warning: level=98
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(42469fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43e90090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  911): releaseWL(43e90090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=98
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42e0c2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  911): sending alarm PendingIntent{42522860: PendingIntentRecord{42bfa988 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784289, Int=0
,D/ConnectivityService(  911): Done.
,D/ConnectivityService(  911): Setting timer for 720seconds
,I/ActivityManager(  911): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4263 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  911): sending alarm PendingIntent{43c961c8: PendingIntentRecord{446af4a0 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,I/ActivityManager(  911): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4275 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  911): sending alarm PendingIntent{42dd8ed8: PendingIntentRecord{42d82bd0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453857089466, Int=10800000
,D/Finsky  ( 3711): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  911): sending alarm PendingIntent{444eae58: PendingIntentRecord{43bdf398 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453857590323, Int=0
V/AlarmManager(  911): sending alarm PendingIntent{4260a8f8: PendingIntentRecord{42d303d0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453857809723, Int=900000
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,V/AlarmManager(  911): sending alarm PendingIntent{43fac480: PendingIntentRecord{449a6618 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453857885484, Int=0
,W/ContextImpl( 4194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4194): call getInstance()
,D/SmartSyncUtils( 4194): isEpsOn(), nState = 0
,D/PMS     (  911): acquireWL(444ea440): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4194 1000 null
,D/PowerUsageList:PowerUsageHelper( 4194): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4194): [updateNmRange] bManual = false
I/ImageRamCache( 4263): create image Cache, size: 31457280.
,D/PMS     (  911): releaseWL(42e0c2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/ImageRamCache( 4263): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 4263): create image Cache, size: 12582912.
D/SmartSyncScreenOnOffTimeReceiver( 4194): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4194): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4194): SettingOnTime = 1453874400000, randomSettingOnTime = 1453871882000
D/SmartSyncScreenOnOffTimeReceiver( 4194): SettingOffTime = 1453860000000, randomSettingOffTime = 1453862383000
I/FeedSettings( 4263): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
D/SmartSyncScreenOnOffTimeReceiver( 4194): bDayMode = false
I/FeedSettings( 4263): GroupBudget 0.500000 0.380000
I/FeedSettings( 4263): GroupBudget 60 45 15
D/SmartSyncScreenOnOffTimeReceiver( 4194): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4194): bNightModeTurnOffOnce = false
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.aurora (4275/10049)
,I/Prism.ExternalStringMa_( 4263): changeLocale(): en_GB
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  911): releaseWL(444ea440): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  911): Couldn't get kernel wake lock stats
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Prism.AllAppsOptionsMa_( 4263): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4263): loadGridSize() with Alternative
,D/libc    ( 4263): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4263): [NET] getaddrinfo-,err=8
D/libc    ( 4263): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4263): [NET] getaddrinfo-, 1
,D/libc    ( 4263): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 4263): [NET] getaddrinfo_proxy-
,E/[CSBICLIENT][v9][BiLogUploadService]( 4263): Exception on getConfig()
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3711): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3711): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/Process (  911): killProcessQuiet, pid=3987
,I/ActivityManager(  911): Killing 3987:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 3987
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3711): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
D/Finsky  ( 3711): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  911): acquireWL(43e34f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10074}
,V/AlarmManager(  911): sending alarm PendingIntent{42620868: PendingIntentRecord{44195488 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1453857886735, Int=0,
D/Finsky  ( 3711): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/WearableService( 1199): callingUid 10029, callindPid: 1199
,D/DeviceConnectionService( 1199): client connected with version: 8296000
D/PMS     (  911): acquireWL(43d890f8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3711 10074 null
D/PMS     (  911): releaseWL(43e34f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3711): [402] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
D/Finsky  ( 3711): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3711): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3711): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
D/PMS     (  911): releaseWL(43d890f8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/Process (  911): killProcessQuiet, pid=4007
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4007:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4007
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(44119b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1021788, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(44119b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(444a3340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10074}
,V/AlarmManager(  911): sending alarm PendingIntent{42cfb128: PendingIntentRecord{428e8370 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453857900966, Int=0
,D/PMS     (  911): releaseWL(444a3340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3711): [386] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3711): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PMS     (  911): acquireWL(44a09d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(44a09d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
,I/HtcPowerSaver(  911): >> updateStatus
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=98
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(433b2790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(433b2790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42db92b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1081788, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42db92b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43dd44d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43dd44d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(445d4360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  911): releaseWL(445d4360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=98
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  911): updateBatteryInfo
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(447973d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1141788, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(447973d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(445b4268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): releaseWL(445b4268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=98
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(43bb61d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): releaseWL(43bb61d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/PowerUI ( 1109): closing low battery warning: level=99
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(431a3ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1201789, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(431a3ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(43c7a8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(43c7a8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  911): acquireWL(4453e370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{423218d0: PendingIntentRecord{426f9298 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1261788, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4453e370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,D/PMS     (  911): acquireWL(431fb550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(431fb550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(42fdeb10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): releaseWL(42fdeb10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/PowerUI ( 1109): closing low battery warning: level=99
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1109): status:2 level:99 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),D/CustomizationManager( 4312): ====startRecUseTime====
D/htc.customization.log.level( 4312):  is 
W/CustomizationLogLevel( 4312): Level value is invalid, use default level 2
D/CustomizationManager( 4312):  Read ACC file spent 0.135 (s)
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4312): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4312): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4312): Parsing tag category name = system
I/CustomizationCIDLoader( 4312): Parsing tag category name = application
I/CustomizationCIDLoader( 4312): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4312): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4312): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4312): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4312): Parsing tag category name = Settings
D/CustomizationManager( 4312):  Read CID file spent 0.190 (s)
D/CustomizationManager( 4312):  All configurations done spent 0.191 (s)
W/HtcNativeFlag( 4312): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4312): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4312): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4312): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4312, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  911): killProcessQuiet, pid=4120
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  911): Killing 4120:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
W/asset   (  911): Copying FileAsset 0x63394bd0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  911): Skipping PackageSetting{42a4acc8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/AccTypeManager( 1320): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1556): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1556): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1556): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Launcher( 1250): Deferring update until onResume
D/Launcher( 1250): waitUntilResume // bindAppsRemoved
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/Prism.ItemManager( 4263): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4263): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  911):   Scheme: "sms"
W/GeofencerStateMachine( 1199): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
D/PMS     (  911): acquireWL(43e7c108): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(43e7c108): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
W/AccTypeManager( 1320): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1320): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
E/cutils-trace( 4312): Error opening trace file: No such file or directory (2)
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
D/VoicemailCleanupService( 1276): Cleaning up data for package: com.test.thalitest
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/Prism.PackageStateRece_( 1250): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
E/ExternalAccountType( 1320): Unsupported attribute readOnly
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/IcingCorporaProvider( 2668): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/PhoneApp( 1219): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4329 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDBG( 2668): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x6441cab8
W/dalvikvm( 2668): threadid=14: thread exiting with uncaught exception (group=0x41e35e30)
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/ActivityManager(  911): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2668): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2668): Process: com.google.android.googlequicksearchbox:search, PID: 2668
E/AndroidRuntime( 2668): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 2668): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2668): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2668): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 2668): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 2668): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
E/AndroidRuntime( 2668): 	at cid.d(PG:192)
E/AndroidRuntime( 2668): 	at clo.g(PG:594)
E/AndroidRuntime( 2668): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2668): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2668): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2668): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2668): 	at clr.tL(PG:827)
E/AndroidRuntime( 2668): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2668): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2668): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2668): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2668): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2668): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2668): killProcess, pid=2668
D/Process ( 2668): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
I/ActivityManager(  911): Recipient 2668
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.googlequicksearchbox:search (pid 2668) has died.
D/WifiService(  911): Client connection lost with reason: 4
D/MediaRouterService(  911): Client com.google.android.googlequicksearchbox (pid 2668): Died!
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
E/SQLiteDatabase( 4329): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4329): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4329): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4329): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4329): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4329): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4329): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4329): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4329): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4329): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4329): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4329): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4329): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4329): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4329): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4329): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4329): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4329): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4329): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4329): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4329): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4329): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4329): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4329): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4329): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4329): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4329): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4329): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4329): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4329): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4329): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4329): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4329): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4329): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4329): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4329): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4329): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4329): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4329): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4329): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4329): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4329): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4329): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4329): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4329): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4329): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4329): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4329): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4329): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4329): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4329): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4329): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4329): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4329): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4329): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4329): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4329): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4329): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4329): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4329): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4329): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4329): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4329): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4329): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4329): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4329): threadid=11: thread exiting with uncaught exception (group=0x41e35e30)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4329): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4329): Process: com.google.android.apps.docs, PID: 4329
E/AndroidRuntime( 4329): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4329): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4329): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4329): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4329): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4329): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4329): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4329): 	at aho.run(AbstractDatabaseInstance.java:455)
D/Process ( 4329): killProcess, pid=4329
D/Process ( 4329): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4346 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
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
I/ActivityManager(  911): Recipient 4329
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4329) has died.
W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4359 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4346): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4346): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4346): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4346): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4346): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4346): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4346): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4346): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4346): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4346): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4346): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4346): threadid=10: thread exiting with uncaught exception (group=0x41e35e30)
W/PackageManager(  911): Unable to load service info ResolveInfo{43e2f668 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/AndroidRuntime( 4346): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4346): Process: com.android.keychain, PID: 4346
E/AndroidRuntime( 4346): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4346): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4346): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4346): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4346): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4346): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4346): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4346): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4346): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4346): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  911): App crashed! Process: com.android.keychain
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4346): killProcess, pid=4346
D/Process ( 4346): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453858187673.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 4359): getInstance(Context context)
D/AppTag  ( 4359): getInstance(Context context)
D/AppTag  ( 4359): onCreate()
I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  911): Recipient 4346
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.android.keychain (pid 4346) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10466ms
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(43733aa0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3679 10160 null
D/PMS     (  911): releaseWL(43733aa0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 3711): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1976): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1976): Clearing selected account for com.test.thalitest
I/Prism.ItemManager( 4263): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4263): loadItems() com.htc.launcher.pageview.WidgetManager@422d0ad0 +
I/Prism.WidgetManager( 4263): onLoadItems() +
D/ChimeraCfgMgr( 1976): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1976): Module APK com.google.android.play.games already loaded
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
D/ChimeraCfgMgr( 1976): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1976): Module APK com.google.android.play.games already loaded
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@422f7e10 +
I/Prism.WidgetManager( 1250): onLoadItems() +
I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 1976): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1976): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1976): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d908ba8
W/dalvikvm( 1976): threadid=34: thread exiting with uncaught exception (group=0x41e35e30)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 1976): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1976): Process: com.google.android.gms, PID: 1976
E/AndroidRuntime( 1976): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1976): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1976): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1976): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1976): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1976): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1976): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1976): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1976): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1976): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1976): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1976): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1976): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1976): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1976): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1976): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1976): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1976): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1976): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 1976): killProcess, pid=1976
D/Process ( 1976): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 1976
I/ActivityManager(  911): Process com.google.android.gms (pid 1976) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10250ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10249ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10249ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10249ms
I/ActivityManager(  911): Resuming delayed broadcast
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10245ms
E/SQLiteLog( 2365): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 2365): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fb1038
W/dalvikvm( 2365): threadid=1: thread exiting with uncaught exception (group=0x41e35e30)
E/AndroidRuntime( 2365): FATAL EXCEPTION: main
E/AndroidRuntime( 2365): Process: com.google.process.gapps, PID: 2365
E/AndroidRuntime( 2365): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2365): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2365): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 2365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 2365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2365): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2365): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 2365): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2365): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 2365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 2365): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2365): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2365): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2365): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2365): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2365): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2365): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2365): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2365): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2365): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2365): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 2365): 	... 10 more
E/ActivityManager(  911): App crashed! Process: com.google.process.gapps
D/Process ( 2365): killProcess, pid=2365
D/Process ( 2365): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
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
I/DeviceManagement( 3974): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 3974): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 3974): WorkflowService: Starting workflow service
I/ActivityManager(  911): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4388 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 3974): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@4243af98] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 3974): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3974): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 3974): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3974): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 3974): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 3974): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3974): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5ca09fb8
W/DeviceManagement( 3974): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@4243af98]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 3974): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 3974): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 3974): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 3974): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 3974): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 3974): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 3974): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 3974): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 3974): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 3974): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 3974): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 3974): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 3974): WorkflowService: Stopping workflow service
D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  911): start
W/AtomicFile(  911): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  911): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/Documents( 4388): Loading roots for com.android.providers.downloads.documents
D/Documents( 4388): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4388): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4388): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4388): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4388): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4388): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4388): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4388): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4388): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4388): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4388): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4388): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4388): threadid=1: thread exiting with uncaught exception (group=0x41e35e30)
E/AndroidRuntime( 4388): FATAL EXCEPTION: main
E/AndroidRuntime( 4388): Process: com.android.documentsui, PID: 4388
E/AndroidRuntime( 4388): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4388): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4388): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4388): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4388): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4388): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4388): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4388): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4388): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4388): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4388): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4388): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4388): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4388): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4388): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4388): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4388): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4388): 	... 10 more
I/ActivityManager(  911): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4403 uid=10023 gids={50023, 1028, 1015, 1023}

```
