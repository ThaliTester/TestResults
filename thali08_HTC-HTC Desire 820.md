#### Test 568182540458528_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  905): releaseWL(445c6e20): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(445b3d60): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
D/PMS     (  905): releaseWL(445b3d60): PARTIAL_WAKE_LOCK  Icing 0x1 null
,--------- beginning of /dev/log/main
E/cutils-trace( 3992): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3992): ====startRecUseTime====
D/htc.customization.log.level( 3992):  is 
W/CustomizationLogLevel( 3992): Level value is invalid, use default level 2
D/CustomizationManager( 3992):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3992): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3992): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3992): Parsing tag category name = system
I/CustomizationCIDLoader( 3992): Parsing tag category name = application
I/CustomizationCIDLoader( 3992): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3992): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3992): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3992): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3992): Parsing tag category name = Settings
D/CustomizationManager( 3992):  Read CID file spent 0.099 (s)
D/CustomizationManager( 3992):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 3992): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3992): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3992): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3992): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1136758696
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3992
D/PMS     (  905): acquireHCC(445a1bb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(44595840): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@429b4298
I/SocialFeedProvider( 1250): +onPause
I/SocialFeedProvider( 1250): -onPause
D/PMS     (  905): acquireWL(4444fd78): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4003 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1250): [trimMemory] 20
W/asset   ( 4003): Copying FileAsset 0x5c8c0428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4003): Binding Chromium to main looper Looper (main, tid 1) {424bd620}
I/LibraryLoader( 4003): Expected native library version number "",actual native library version number ""
I/chromium( 4003): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4003): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(443cd530): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(443cac78): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(443cd530): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44614990:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4003): 1112354904: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 4003): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4003): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4003): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4003): Local Branch: 
I/Adreno-EGL( 4003): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4003): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4003):                  aa63bbd948f41d15fc72f585e
W/chromium( 4003): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4003): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4003): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4003): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4003): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4003): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4003): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4003): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4003): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4003): CordovaWebView is running on device made by: HTC
,W/AwContents( 4003): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Disable input method client, pid=1250
W/ResourceType( 4003): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4003): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@425045e0, mServedView=org.apache.cordova.engine.SystemWebView{424ca370 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  905): Enable input method client, pid=4003
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4003): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +286ms
D/PMS     (  905): releaseWL(4444fd78): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4003): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4003): JniHelper::setJavaVM(0x42073010), pthread_self() = 1663184392
I/chromium( 4003): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/dalvikvm-heap( 4003): Grow heap (frag case) to 11.987MB for 63974-byte allocation
I/dalvikvm-heap( 4003): Grow heap (frag case) to 12.038MB for 95956-byte allocation
,I/dalvikvm-heap( 4003): Grow heap (frag case) to 12.117MB for 143930-byte allocation
,I/dalvikvm-heap( 4003): Grow heap (frag case) to 12.232MB for 215890-byte allocation
,I/dalvikvm-heap( 4003): Grow heap (frag case) to 12.407MB for 323830-byte allocation
,I/dalvikvm-heap( 4003): Grow heap (frag case) to 13.083MB for 728606-byte allocation
,I/dalvikvm-heap( 4003): Grow heap (frag case) to 13.679MB for 1092904-byte allocation
,I/dalvikvm-heap( 4003): Grow heap (frag case) to 14.596MB for 1639352-byte allocation
,I/dalvikvm-heap( 4003): Grow heap (frag case) to 15.848MB for 2459024-byte allocation
,I/dalvikvm-heap( 4003): Grow heap (frag case) to 18.025MB for 3688532-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(445a1bb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(44595840): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4003): Initializing JXcore engine
,W/jxcore-log( 4003): JXcore engine is ready
,W/jxcore-log( 4003): Starting JXcore engine
,W/jxcore-log( 4003): Platform android
W/jxcore-log( 4003): 
,W/jxcore-log( 4003): Process ARCH arm
W/jxcore-log( 4003): 
,I/jxcore-log( 4003): JXcore Cordova bridge is ready!
I/jxcore-log( 4003): 
,W/jxcore-log( 4003): JXcore engine is started
,E/jxcore  ( 4003): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4003): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4003): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 4003): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  905): acquireWL(4437f080): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
,I/FeedHostManager( 1250): [onResume]
,I/FeedProviderManager( 1250): onResume
I/SocialFeedProvider( 1250): +onResume
I/SocialFeedProvider( 1250): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1250): -onResume
,I/ConnectivityHelper( 1250): [getCurrentConnectionType] no network connection
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.launcher (1250/10075)
,I/InputMethodManagerService(  905): Disable input method client, pid=4003
,I/InputMethodManagerService(  905): Enable input method client, pid=1250
W/IInputConnectionWrapper( 4003): reportFullscreenMode on inactive InputConnection
,D/PMS     (  905): releaseWL(4437f080): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  905): killProcessQuiet, pid=3832
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  905): Killing 3832:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,E/libEGL  ( 4003): call to OpenGL ES API with no current context (logged once per thread)
D/PMS     (  905): releaseWL(443cac78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  905): Recipient 3832
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4049 uid=10077 gids={50077}
,D/PMS     (  905): acquireWL(44295410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
V/AlarmManager(  905): sending alarm PendingIntent{42e451e0: PendingIntentRecord{42f38238 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453856976611, Int=60000
,D/PMS     (  905): releaseWL(44295410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4049): SMSBackupAgentService started
,D/SMSBackup( 4049): Checking restore status
,D/SMSBackup( 4049): Restore complete
,D/SMSBackup( 4049): cancelCheckAlarm
,D/SMSBackup( 4049): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=3490
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3490:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3490
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.music (pid 3490): Died!
,I/SensorManager(  905): mEventCount = 900
,I/PMS     (  905): Going to sleep due to screen timeout...
,W/PMS     (  905): mWirelessDisplayManager is null
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a74398
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a74398, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426f4288
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@42f4d320
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 382ms
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/NfcService( 1232): ScreenObserver: OFF
,D/NfcService( 1232): applyRouting - 0
,D/NfcService( 1232): applyRouting -2
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43b000c0)
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
D/PMS     (  905): OOBE c monitor 11
I/InputMethodManagerService(  905): Disable input method client, pid=1250
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
D/PMS     (  905): acquireWL(43d1b018): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  905): releaseWL(43d1b018): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  905): wakingUp
D/PMS     (  905): acquireWL(43d13178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/PMS     (  905): releaseWL(43d13178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  905): No lock screen! windowToken=null
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMN     (  905): onScreenOn
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=97
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/MtpService( 2137): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2137): [MTP][onReceive]-
,D/NfcService( 1232): applyRouting - 0
,D/NfcService( 1232): applyRouting -2
I/HtcPowerSaver(  905): << updateStatus
W/ActivityManager(  905): Disable JIT of com.htc.bgp
D/PMS     (  905): acquireWL(43cfa5e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  905): releaseWL(43cfa5e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ActivityManager(  905): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4067 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
,D/qdlights(  905): [LedInfo] has indicator attribute
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  905):    returned false
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1109): stop update clock
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
I/BatteryController( 1109): status:2 level:97 unsupport:false plugged:true
D/NetworkPolicy(  905): updateScreenOn: false
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43c79b40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1412 10028 null
D/PMS     (  905): releaseWL(43c79b40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426f4288
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426f4288, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@42f4d320
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(43c6e748): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,I/FeedHostManager( 1250): [onPause]
,I/FeedProviderManager( 1250): onPause
,I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@429b4298
I/SocialFeedProvider( 1250): +onPause
,I/SocialFeedProvider( 1250): -onPause
,I/CalendarProvider2( 4067): Created com.android.providers.calendar.CalendarAlarmManager@424edc70(com.android.providers.calendar.HtcCalendarProvider@424d5ff8)
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19524 mDataStallAlarmIntent=null
,D/CalendarProvider2( 4067): wait start:true
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  905):    returned false
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: false
D/PMS     (  905): acquireWL(43c328b8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(43c328b8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/PMS     (  905): releaseWL(43c6e748): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/NetworkPolicy(  905): updateScreenOn: false
D/ContactMessageStore( 1220): start background delete task...
D/ContactMessageStore( 1220): size: 0 , 0
D/ContactMessageStore( 1220): Background delete complete
,D/CalendarProvider2( 4067): wait end:false
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4087 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1537): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  905): acquireWL(435d9a08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1412 10028 null
,D/PMS     (  905): releaseWL(435d9a08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ContextImpl( 4087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4087): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(435c2a00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4087 1000 null
,D/PMS     (  905): releaseWL(435c2a00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4087): getMobilePolicyEnabled, result = true
,D/Process (  905): killProcessQuiet, pid=3473
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Killing 3473:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/AutoSetting( 1392): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1392): service - onCreate()
,D/AutoSetting( 1392): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1392): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  905): request 42de6820 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
,D/TetherSettings( 3795): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3795): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3795): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3795): Cust_ConnectToPC   : spcsc>false
D/        ( 3795): Cust_ConnectToPC   : IPT>true
,D/        ( 3795): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3795): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3795): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3795): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3795): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3795): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 3795): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3795): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
W/Settings( 3795): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3795):  defaultType:0
I/ActivityManager(  905): Resuming delayed broadcast
,W/ContextImpl( 4087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4087): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4087): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4087): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f4d320
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  905): pid=905, uid=1000
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f4d320, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f4d320, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f4d320
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f4d7e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f4d7e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  905): Recipient 3473
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CalendarProvider2( 4067): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4067): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3859): ---------------------------------------------------
,D/ProviderChangeReceiver( 3859): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3859): start to updateAlertNotification!
,W/ContextImpl( 3874): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3859): No fired or scheduled alerts
,D/HtcAlertUtils( 3859): -- cancelReminderNotification --
,D/HtcAlertUtils( 3859): broadcastExistReminder!
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  905): killProcessQuiet, pid=3512
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3512:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3512
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1392): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1392): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1392): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{45133be0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  905): acquireWL(438c0998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=126717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(438c0998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(438a9ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(438a9ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=97
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:2 level:97 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1392): service - handleMessage() stop self
,D/AutoSetting( 1392): service - handleMessage() quit looper
,D/AutoSetting( 1392): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3677
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3677:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3677
,D/PMS     (  905): acquireWL(42f7f830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42f7f830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42f79900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028}
,V/AlarmManager(  905): sending alarm PendingIntent{44093c68: PendingIntentRecord{42e67560 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140852, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42d0c478: PendingIntentRecord{42e87fb0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140930, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
V/AlarmManager(  905): sending alarm PendingIntent{42b4bdd0: PendingIntentRecord{42d431a8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145881, Int=0
D/PMS     (  905): acquireWL(42f32010): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
,D/PMS     (  905): releaseWL(42f79900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    (  905): [NET] getaddrinfo_proxy-,
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): releaseWL(42f32010): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(42ee7f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=186717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42ee7f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42ee3520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42ee3520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=97
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:2 level:97 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42d5a950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42d5a950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=98
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  905): [NET] getaddrinfo_proxy-
D/PMS     (  905): acquireWL(428ba970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{42b4bdd0: PendingIntentRecord{42d431a8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=205911, Int=0
D/PMS     (  905): releaseWL(428ba970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(427c8898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=246717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427c8898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427223e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427223e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4291d6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=306717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4291d6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425beb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=98
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(425beb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1346): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1346): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1346): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1346): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1346): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1346): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1346): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1346): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,E/PlayEventLogger( 3738): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3738): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3738): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{424fee70 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3738): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3738): [NET] getaddrinfo-,err=8
D/libc    ( 3738): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3738): [NET] getaddrinfo-, 1
,D/libc    ( 3738): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3738): [NET] getaddrinfo_proxy-
E/PlayEventLogger( 3738): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 13 5 12,
,D/PMS     (  905): acquireWL(42e7f388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=366717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e7f388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42d597e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42d597e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(4283bd98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4283bd98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=99
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42dfc350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=426717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42dfc350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(429bab00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(429bab00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(44216d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=486718, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44216d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43142e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43142e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43f8fb58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=546718, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43f8fb58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43820600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43820600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42e4c470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderNotification, total:0
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  905): batLight: Full, plugged
D/HtcPowerSaver(  905): updateBatteryInfo
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  905): releaseWL(42e4c470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/ContextImpl( 4087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3795): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3795): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3795): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3795): Cust_ConnectToPC   : spcsc>false
D/        ( 3795): Cust_ConnectToPC   : IPT>true
,D/        ( 3795): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3795): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3795): Index of the first 1 = -1
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/Settings( 3795): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3795): hasRemovableStorageSlot: true
W/ContextImpl( 3795): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3795): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3795): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3795): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 3795): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  905): acquireWL(42f0dc18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=606717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42f0dc18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42da1740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42da1740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1220): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1220): sku_id=99
D/ContactMessageStore( 1220): start background delete task...
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1220): size: 0 , 0
,D/ContactMessageStore( 1220): Background delete complete,
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1346): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1346): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1346): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1346): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1346): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1346): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1346): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1346): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3738): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3738): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3738): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1109): com.google.android.gms (false,0)
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 3738): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3738): [NET] getaddrinfo-,err=8
D/libc    ( 3738): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3738): [NET] getaddrinfo-, 1
D/libc    ( 3738): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{42539d28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3738): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3738): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname),
,I/RemoteViews.Performance( 1109): com.google.android.gms 3 11 3 12
,D/PMS     (  905): acquireWL(42eac3b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=666717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42eac3b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4465bde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4465bde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4134 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  905): acquireWL(43d51020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10047}
,V/AlarmManager(  905): sending alarm PendingIntent{428eb020: PendingIntentRecord{42f90c58 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453857093483, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{42b52510: PendingIntentRecord{42b4c2a0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453857451811, Int=1800000
,V/AlarmManager(  905): sending alarm PendingIntent{44006288: PendingIntentRecord{42af8b48 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453857546206, Int=0
,D/PMS     (  905): acquireWL(43c1e600): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1200 10028 null
,D/PMS     (  905): acquireWL(42e350f8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1200 10028 null
,D/PMS     (  905): releaseWL(43c1e600): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1200): Aggregate from 1453855651770 (log), 1453855651770 (data)
D/PMS     (  905): releaseWL(43d51020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4134/10047)
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/EventLogAggregator( 1200): Unknown tag: install_package_attempt
W/EventLogAggregator( 1200): Unknown tag: snet
,W/EventLogAggregator( 1200): Unknown tag: snet_gcore
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
D/PMS     (  905): releaseWL(42e350f8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3738): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3738): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3738): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3738): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3738): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/Process (  905): killProcessQuiet, pid=2971
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2971:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2971
,D/PMS     (  905): acquireWL(42bf8a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10073}
,V/AlarmManager(  905): sending alarm PendingIntent{44a8c320: PendingIntentRecord{438c04d8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453857561513, Int=0
,D/PMS     (  905): releaseWL(42bf8a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3738): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  905): acquireWL(438aee48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=726718, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(438aee48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43fd6968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43fd6968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  905): acquireWL(433570f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{427b36a8: PendingIntentRecord{42df63d0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782436, Int=0
,D/PMS     (  905): releaseWL(433570f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): acquireWL(4409bb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=786717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4409bb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4300ce10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4300ce10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43366448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=846717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43366448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43a70e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43a70e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43dd2b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(43dd2b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  905): acquireWL(42cfc1b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=906717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42cfc1b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(434299e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(434299e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1346): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1346): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1346): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1346): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1346): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1346): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1346): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1346): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 3738): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3738): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3738): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{424c67e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3738): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3738): [NET] getaddrinfo-,err=8
D/libc    ( 3738): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3738): [NET] getaddrinfo-, 1
D/libc    ( 3738): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3738): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3738): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1109): com.google.android.gms 2 11 4 12
,D/PMS     (  905): acquireWL(43d387e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=966717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43d387e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44711ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44711ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,I/ActivityManager(  905): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4152 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,D/PMS     (  905): acquireWL(43c59780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10075}
,V/AlarmManager(  905): sending alarm PendingIntent{4394e8f0: PendingIntentRecord{44112430 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  905): sending alarm PendingIntent{42ec4ac8: PendingIntentRecord{42f17670 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453857813905, Int=900000
,V/AlarmManager(  905): sending alarm PendingIntent{42eea9d8: PendingIntentRecord{4441d498 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453857884434, Int=0
,W/ContextImpl( 4087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4087): call getInstance()
,D/SmartSyncUtils( 4087): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4087): MY_DEBUG = false
D/PMS     (  905): acquireWL(43008298): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4087 1000 null
D/PMS     (  905): releaseWL(43c59780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4087): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4087): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 7, bNormalRange = true
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/SmartSyncScreenOnOffTimeReceiver( 4087): [updateNmRange] new USERNIGHT_TIMESTART = 1, new USERNIGHT_TIMEEND = 7
I/ImageRamCache( 4152): create image Cache, size: 31457280.
I/ImageRamCache( 4152): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4152): create image Cache, size: 12582912.
,I/FeedSettings( 4152): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4152): GroupBudget 0.500000 0.380000
,W/ContextImpl( 4087): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
I/FeedSettings( 4152): GroupBudget 60 45 15
I/FeedHostManager( 1250): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
D/SmartSyncScreenOnOffTimeReceiver( 4087): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4087): SettingOnTime = 1453874400000, randomSettingOnTime = 1453871582000
D/SmartSyncScreenOnOffTimeReceiver( 4087): SettingOffTime = 1453939200000, randomSettingOffTime = 1453944885000
D/SmartSyncScreenOnOffTimeReceiver( 4087): bDayMode = false
I/FeedHostManager( 1250): NightMode begin at 0, end at 7
,I/Prism.ExternalStringMa_( 4152): changeLocale(): en_GB
D/SmartSyncScreenOnOffTimeReceiver( 4087): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4087): bNightModeTurnOffOnce = false
D/PMS     (  905): acquireWL(447e51c8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1250 10075 null
,I/Prism.AllAppsOptionsMa_( 4152): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4152): loadGridSize() with Alternative
D/PMS     (  905): acquireWL(4389ce88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{43f598e0: PendingIntentRecord{4441f3c0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1453857884569, Int=0
,D/PMS     (  905): releaseWL(43008298): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/FeedHostManager( 1250): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1453857884567, BeginTime: 1453849200000, EndTime: 1453874400000
,I/FeedHostManager( 1250): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
W/ContextImpl( 4087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): releaseWL(447e51c8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
V/AlarmManager(  905): sending alarm PendingIntent{44a3e6d0: PendingIntentRecord{447e7b28 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1453849200000, Int=0
D/PMS     (  905): acquireWL(435d69f0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1250 10075 null
D/SmartSyncUtils( 4087): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4087): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  905): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  905): releaseWL(435d69f0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/PMS     (  905): releaseWL(4389ce88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
D/SmartSyncUtils( 4087): isWifiHotSpotEnabled = false
D/SmartSyncDataLinkTurnOffService( 4087): turnOffMobile bCheckMobileData = false
D/LocationManagerService(  905): getProviders()=[gps, network]
D/LocationManagerService(  905): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  905): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4087): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4087): isCharging status = 5
D/SmartSyncDataLinkTurnOffService( 4087): turnOffWifi ui setting = false
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/libc    ( 4152): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4152): [NET] getaddrinfo-,err=8
D/libc    ( 4152): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4152): [NET] getaddrinfo-, 1
,D/libc    ( 4152): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 4152): [NET] getaddrinfo_proxy-
,E/[CSBICLIENT][v9][BiLogUploadService]( 4152): Exception on getConfig()
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/Process (  905): killProcessQuiet, pid=3895
,I/ActivityManager(  905): Killing 3895:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3895
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42e326f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1026717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e326f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42e727e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e727e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43783538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1086717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43783538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42d03c18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42d03c18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  905): acquireWL(4271b418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1146717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4271b418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426e28b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426e28b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42ffa448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1206717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42ffa448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(445cbdf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(445cbdf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1346): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1346): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1346): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1346): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1346): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1346): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1346): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1346): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1109): com.google.android.gms (false,0)
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{426331e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3738): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3738): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3738): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3738): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 7 4 12
,D/libc    ( 3738): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3738): [NET] getaddrinfo-,err=8
D/libc    ( 3738): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3738): [NET] getaddrinfo-, 1
,D/libc    ( 3738): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3738): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3738): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  905): acquireWL(434f38f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4255d060: PendingIntentRecord{42d13628 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1266717, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(434f38f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42e695f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42e695f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4175): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4175): ====startRecUseTime====
D/htc.customization.log.level( 4175):  is 
W/CustomizationLogLevel( 4175): Level value is invalid, use default level 2
D/CustomizationManager( 4175):  Read ACC file spent 0.093 (s)
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4175): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4175): Parsing tag category name = system
I/CustomizationCIDLoader( 4175): Parsing tag category name = application
I/CustomizationCIDLoader( 4175): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4175): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4175): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4175): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4175): Parsing tag category name = Settings
D/CustomizationManager( 4175):  Read CID file spent 0.142 (s)
D/CustomizationManager( 4175):  All configurations done spent 0.142 (s)
W/HtcNativeFlag( 4175): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4175): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4175): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4175): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4175, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=4003
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 4003:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
W/asset   (  905): Copying FileAsset 0x63cd4f98 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
I/acms    ( 1771): Unregistering com.test.thalitest
E/acms    ( 1771): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1412): Ignoring removeGeofence because network location is disabled.
D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  905): acquireWL(444a83d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1412 10028 null
I/Prism.ItemManager( 4152): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4152): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  905): releaseWL(444a83d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1310): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1310): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1276): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/Launcher( 1250): Deferring update until onResume
D/Launcher( 1250): waitUntilResume // bindAppsRemoved
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
D/AccTypeManager( 1310): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/PackageBroadcastService( 1200): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4190 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
E/ExternalAccountType( 1310): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4190): install
I/MultiDex( 4190): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  905): Delaying start of: ServiceRecord{44a94ba0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4190): loading existing secondary dex files
I/MultiDex( 4190): load found 1 secondary dex files
I/MultiDex( 4190): install done
I/PeopleContactsSync( 1200): CP2 sync disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1200, uid=10028, userID:0
D/PMS     (  905): acquireWL(42b1dd70): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
I/Icing   ( 1200): doRemovePackageData com.test.thalitest
D/PMS     (  905): releaseWL(42b1dd70): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4208 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4190): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4208): install
I/MultiDex( 4208): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4208): loading existing secondary dex files
I/MultiDex( 4208): load found 1 secondary dex files
I/MultiDex( 4208): install done
I/ActivityManager(  905): Resuming delayed broadcast
I/ProviderInstaller( 4208): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1392): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1392): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1250): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2725): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteDatabase( 4190): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4190): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4190): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4190): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4190): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4190): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4190): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4190): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4190): threadid=12: thread exiting with uncaught exception (group=0x42084e30)
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4230 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/AndroidRuntime( 4190): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4190): Process: com.google.android.gms.drive, PID: 4190
E/AndroidRuntime( 4190): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4190): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4190): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4190): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4190): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4190): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4190): 	at ctn.run(SourceFile:985)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
D/Process ( 4190): killProcess, pid=4190
D/Process ( 4190): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2725): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2725): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63c7c4a0
W/dalvikvm( 2725): threadid=14: thread exiting with uncaught exception (group=0x42084e30)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
E/AndroidRuntime( 2725): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2725): Process: com.google.android.googlequicksearchbox:search, PID: 2725
E/AndroidRuntime( 2725): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2725): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2725): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2725): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2725): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2725): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2725): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2725): 	at cid.d(PG:186)
E/AndroidRuntime( 2725): 	at clo.g(PG:594)
E/AndroidRuntime( 2725): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2725): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2725): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2725): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2725): 	at clr.tL(PG:827)
E/AndroidRuntime( 2725): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2725): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2725): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2725): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2725): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
I/ActivityManager(  905): Recipient 4190
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4190) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/Process ( 2725): killProcess, pid=2725
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
D/Process ( 2725): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
W/ContextImpl( 4230): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4245 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4230): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4230): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4230): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4230): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4230): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4230): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4230): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4230): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4230): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4230): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4230): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4230): threadid=10: thread exiting with uncaught exception (group=0x42084e30)
E/AndroidRuntime( 4230): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4230): Process: com.android.keychain, PID: 4230
E/AndroidRuntime( 4230): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4230): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4230): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4230): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4230): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4230): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4230): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4230): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4230): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4230): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Recipient 2725
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2725): Died!
D/WifiService(  905): Client connection lost with reason: 4
E/ActivityManager(  905): App crashed! Process: com.android.keychain
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2725) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4245): getInstance(Context context)
D/Process ( 4230): killProcess, pid=4230
D/Process ( 4230): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453858186640.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Recipient 4230
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4230) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10899ms
D/AppTag  ( 4245): getInstance(Context context)
D/AppTag  ( 4245): onCreate()
D/PMS     (  905): acquireWL(433facb0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3773 10160 null
I/DeviceManagement( 3912): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 3912): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
D/PMS     (  905): releaseWL(433facb0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/DeviceManagement( 3912): WorkflowService: Starting workflow service
I/DeviceManagement( 3912): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@4268e1f0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 3912): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3912): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 3912): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3912): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 3912): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4264 uid=10099 gids={50099, 3003, 5012}
E/SQLiteLog( 3912): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3912): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5c952380
W/DeviceManagement( 3912): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@4268e1f0]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 3912): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 3912): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 3912): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 3912): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 3912): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 3912): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 3912): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 3912): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 3912): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 3912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 3912): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 3912): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 3912): WorkflowService: Stopping workflow service
D/Process (  905): killProcessQuiet, pid=3945
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3945:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3945
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Documents( 4264): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4264): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4264): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4264): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4264): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4264): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4264): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4264): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4264): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4264): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4264): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4264): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4264): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4264): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4264): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4264): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4264): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4264): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4264): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4264): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4264): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4264): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4264): threadid=1: thread exiting with uncaught exception (group=0x42084e30)
D/Process (  905): killProcessQuiet, pid=3963
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3963:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
E/AndroidRuntime( 4264): FATAL EXCEPTION: main
E/AndroidRuntime( 4264): Process: com.android.documentsui, PID: 4264
E/AndroidRuntime( 4264): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4264): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4264): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4264): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4264): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4264): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4264): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4264): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4264): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4264): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4264): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4264): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4264): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4264): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4264): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4264): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4264): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4264): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4264): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4264): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4264): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4264): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4264): 	... 10 more
E/ActivityManager(  905): App crashed! Process: com.android.documentsui
D/GCM     ( 1346): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/Documents( 4264): Loading roots for com.android.externalstorage.documents
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  905): Recipient 3963
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4279 uid=10023 gids={50023, 1028, 1015, 1023}
D/GCM     ( 1346): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4292 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
D/Process (  905): killProcessQuiet, pid=4049
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  905): Killing 4049:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
I/ActivityManager(  905): Recipient 4049
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 4152): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4152): loadItems() com.htc.launcher.pageview.WidgetManager@42522a88 +
I/Prism.WidgetManager( 4152): onLoadItems() +
D/ExternalStorage( 4279): After updating volumes, found 1 active roots
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@42548e98 +
I/Prism.WidgetManager( 1250): onLoadItems() +
D/Documents( 4264): Loading roots for com.android.providers.media.documents
D/Process ( 4264): killProcess, pid=4264
D/Process ( 4264): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453858187047.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Recipient 4264
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.documentsui (pid 4264) has died.
E/SQLiteDatabase( 4292): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4292): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4292): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4292): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4292): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4292): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4292): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4292): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4292): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4292): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4292): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4292): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4292): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4292): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4292): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4292): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4292): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4292): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4292): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4292): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4292): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4292): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4292): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4292): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4292): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4292): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 4292): Opened MyDB.db in read-only mode
W/PackageManager(  905): Unable to load service info ResolveInfo{433656d8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)

```
