#### Test 5065027873d6a28_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  904): acquireWL(42558688): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
,D/PMS     (  904): releaseWL(42558688): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  904): acquireWL(42543848): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
D/PMS     (  904): releaseWL(42543848): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  904): acquireWL(4253aef0): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
D/PMS     (  904): releaseWL(4253aef0): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of /dev/log/main
E/cutils-trace( 3847): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3847): ====startRecUseTime====
D/htc.customization.log.level( 3847):  is 
W/CustomizationLogLevel( 3847): Level value is invalid, use default level 2
D/CustomizationManager( 3847):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3847): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3847): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3847): Parsing tag category name = system
I/CustomizationCIDLoader( 3847): Parsing tag category name = application
I/CustomizationCIDLoader( 3847): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3847): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3847): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3847): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3847): Parsing tag category name = Settings
D/CustomizationManager( 3847):  Read CID file spent 0.105 (s)
D/CustomizationManager( 3847):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 3847): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3847): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3847): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3847): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3847
D/PMS     (  904): acquireHCC(421034d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(41fea518): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x62e45598 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1112427680
I/FeedHostManager( 1246): [onPause]
I/FeedProviderManager( 1246): onPause
I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cd31d8
I/SocialFeedProvider( 1246): +onPause
I/SocialFeedProvider( 1246): -onPause
D/PMS     (  904): acquireWL(41c3c728): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3860 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1246): [trimMemory] 20
W/asset   ( 3860): Copying FileAsset 0x5c6fe990 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3860): Binding Chromium to main looper Looper (main, tid 1) {41a8a710}
I/LibraryLoader( 3860): Expected native library version number "",actual native library version number ""
I/chromium( 3860): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3860): Initializing chromium process, renderers=0
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@421366b0:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3860): 1101660488: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  904): acquireWL(41d8fdd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): acquireWL(4258e3b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(41d8fdd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3860): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3860): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3860): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3860): Local Branch: 
I/Adreno-EGL( 3860): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3860): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3860):                  aa63bbd948f41d15fc72f585e
W/chromium( 3860): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3860): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3860): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3860): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3860): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3860): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3860): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3860): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3860): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3860): CordovaWebView is running on device made by: HTC
,W/AwContents( 3860): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  904): Disable input method client, pid=1246
W/ResourceType( 3860): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3860): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ad16d0, mServedView=org.apache.cordova.engine.SystemWebView{41a97460 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  904): Enable input method client, pid=3860
W/XT9_C   ( 1181): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1181): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3860): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +270ms
D/PMS     (  904): releaseWL(41c3c728): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 3860): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3860): JniHelper::setJavaVM(0x41560048), pthread_self() = 1662885056
D/JX-Cordova( 3860): jxcore cordova android initializing
W/dalvikvm( 3860): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
I/dalvikvm-heap( 3860): Grow heap (frag case) to 11.516MB for 63974-byte allocation
I/dalvikvm-heap( 3860): Grow heap (frag case) to 11.630MB for 143930-byte allocation
,I/dalvikvm-heap( 3860): Grow heap (frag case) to 11.745MB for 215890-byte allocation
,I/dalvikvm-heap( 3860): Grow heap (frag case) to 11.919MB for 323830-byte allocation
,I/dalvikvm-heap( 3860): Grow heap (frag case) to 12.192MB for 485740-byte allocation
,I/dalvikvm-heap( 3860): Grow heap (frag case) to 12.594MB for 728606-byte allocation
,I/dalvikvm-heap( 3860): Grow heap (frag case) to 14.032MB for 1639352-byte allocation
,I/dalvikvm-heap( 3860): Grow heap (frag case) to 15.436MB for 2459024-byte allocation
,I/SensorManager(  904): mEventCount = 1351
,I/dalvikvm-heap( 3860): Grow heap (frag case) to 17.453MB for 3688532-byte allocation
,W/jxcore-log( 3860): Initializing JXcore engine
,W/jxcore-log( 3860): JXcore engine is ready
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
,D/PMS     (  904): releaseHCC(421034d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  904): releaseHCC(41fea518): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3860): Starting JXcore engine
,W/jxcore-log( 3860): Platform android
W/jxcore-log( 3860): 
,W/jxcore-log( 3860): Process ARCH arm
W/jxcore-log( 3860): 
,I/jxcore-log( 3860): JXcore Cordova bridge is ready!
I/jxcore-log( 3860): 
,W/jxcore-log( 3860): JXcore engine is started
,I/chromium( 3860): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3860): Error!: missing ) after argument list
E/jxcore  ( 3860): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
I/chromium( 3860): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,W/PluginManager( 3860): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  904): acquireWL(43f16788): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
,I/FeedHostManager( 1246): [onResume]
,I/FeedProviderManager( 1246): onResume
,I/SocialFeedProvider( 1246): +onResume
I/SocialFeedProvider( 1246): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1246): -onResume
,I/ConnectivityHelper( 1246): [getCurrentConnectionType] no network connection
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (1246/10075)
,I/InputMethodManagerService(  904): Disable input method client, pid=3860
,I/InputMethodManagerService(  904): Enable input method client, pid=1246
,W/IInputConnectionWrapper( 3860): reportFullscreenMode on inactive InputConnection
D/PMS     (  904): releaseWL(4258e3b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  904): releaseWL(43f16788): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  904): killProcessQuiet, pid=3030
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  904): Killing 3030:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3030
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/libEGL  ( 3860): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3907 uid=10077 gids={50077}
,D/PMS     (  904): acquireWL(43ed5c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
,V/AlarmManager(  904): sending alarm PendingIntent{424f1b98: PendingIntentRecord{4250cf88 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449626594223, Int=60000
,D/PMS     (  904): releaseWL(43ed5c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3907): SMSBackupAgentService started
,D/SMSBackup( 3907): Checking restore status
,D/SMSBackup( 3907): Restore complete
,D/SMSBackup( 3907): cancelCheckAlarm
,D/SMSBackup( 3907): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3410
,I/ActivityManager(  904): Killing 3410:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 3410
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  904): Client com.google.android.music (pid 3410): Died!
,I/SensorManager(  904): mEventCount = 1500
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420a9318
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
W/PMS     (  904): mWirelessDisplayManager is null
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
W/BatSI   (  904): Couldn't get kernel wake lock stats
,V/LightsService(  904): setLight #0: color=#0
D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420a9318, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422f6790
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@42108eb0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 399ms
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
D/PMS     (  904): OOBE c monitor 11
D/NfcService( 1231): ScreenObserver: OFF
D/NfcService( 1231): applyRouting - 0
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42fd4f08)
,I/IntentController( 1105): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=1246
D/PMN     (  904): wakingUp
D/PMS     (  904): acquireWL(43eeb020): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
,D/NfcService( 1231): applyRouting -2
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  904): No lock screen! windowToken=null
D/PMS     (  904): releaseWL(43eeb020): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  904): onScreenOn
D/PMS     (  904): acquireWL(42bf3fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
W/ActivityManager(  904): Disable JIT of com.htc.bgp
D/PMS     (  904): releaseWL(42bf3fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
,I/ClockThread( 1105): stop update clock
,I/ActivityManager(  904): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3922 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/WifiNative-wlan0(  904):    returned false
D/MtpService( 2205): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1231): applyRouting - 0
,D/NfcService( 1231): applyRouting -2
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): acquireWL(42582518): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
,D/PMS     (  904): releaseWL(42582518): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/MtpService( 2205): [MTP][onReceive]-
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  904): updateScreenOn: false
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/CalendarProvider2( 3922): Created com.android.providers.calendar.CalendarAlarmManager@41ac5d98(com.android.providers.calendar.HtcCalendarProvider@41aae120)
,D/CalendarProvider2( 3922): wait start:true
D/PMS     (  904): acquireWL(4231afc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1400 10028 null
D/PMS     (  904): releaseWL(4231afc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422f6790
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422f6790, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@42108eb0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
,D/PMS     (  904): acquireWL(445ed8c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,I/FeedHostManager( 1246): [onPause]
,I/FeedProviderManager( 1246): onPause
,I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cd31d8
I/SocialFeedProvider( 1246): +onPause
,I/SocialFeedProvider( 1246): -onPause
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
,I/AlarmManager(  904): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=19790 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  904):    returned false
,D/CalendarProvider2( 3922): wait end:false
D/PMS     (  904): acquireWL(41ffdcf8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
D/PMS     (  904): releaseWL(41ffdcf8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  904): releaseWL(445ed8c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  904): updateScreenOn: false
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3943 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/PhoneStatusBar( 1105): removeHeadsNotification.gc: 51
,D/ContactMessageStore( 1218): start background delete task...
D/ContactMessageStore( 1218): size: 0 , 0
,D/ContactMessageStore( 1218): Background delete complete
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): acquireWL(4305f700): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1400 10028 null
D/PMS     (  904): releaseWL(4305f700): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  904): acquireWL(43c66b18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3943 1000 null
,D/SmartSyncUtils( 3943): isEpsOn(), nState = 0
,D/PMS     (  904): releaseWL(43c66b18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 3943): getMobilePolicyEnabled, result = true
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1373): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3347): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3347): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3347): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3347): Cust_ConnectToPC   : spcsc>false
D/        ( 3347): Cust_ConnectToPC   : IPT>true
D/        ( 3347): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3347): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3347): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3347): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3347): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1373): service - onCreate()
,I/PSReceiver( 3347): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3347): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3347): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3347): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3347):  defaultType:0
,D/AutoSetting( 1373): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1373): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  904): Delay finish: com.android.settings/.PSReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
D/LocationManagerService(  904): request 424f9e90 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
,W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3943): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3943): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3943): isEpsOn(), nState = 0
D/WifiService(  904): New client listening to asynchronous messages
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42108eb0
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42108eb0, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42108eb0, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42108eb0
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41a7f7d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41a7f7d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 3922): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3922): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3809): ---------------------------------------------------
,D/ProviderChangeReceiver( 3809): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3809): start to updateAlertNotification!
,W/ContextImpl( 3824): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3809): No fired or scheduled alerts
,D/HtcAlertUtils( 3809): -- cancelReminderNotification --
,D/HtcAlertUtils( 3809): broadcastExistReminder!
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  904): killProcessQuiet, pid=3696
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  904): Killing 3696:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3696,
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,D/Process (  904): killProcessQuiet, pid=3433
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3433:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3433
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1373): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1373): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1373): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{43436e80 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  904): acquireWL(43782d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43782d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1373): service - handleMessage() stop self
,D/AutoSetting( 1373): service - handleMessage() quit looper
,D/AutoSetting( 1373): service - onDestroy() END
,D/Process (  904): killProcessQuiet, pid=3392
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3392:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3392
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(43e7cc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{4221fea8: PendingIntentRecord{4247b8e8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141096, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{41f86ea0: PendingIntentRecord{42446b70 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141167, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42191f50: PendingIntentRecord{4230a398 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=144836, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/PMS     (  904): acquireWL(42815578): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43e7cc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    (  904): [NET] getaddrinfo_proxy-
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): releaseWL(42815578): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  904): acquireWL(4279c808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149186, Int=0
W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4279c808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43a33bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43a33bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1218): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(43f382c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43f382c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/PowerUI ( 1105): closing low battery warning: level=100
D/HtcPowerSaver(  904): Checking...
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/PMS     (  904): acquireWL(4256d468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{42191f50: PendingIntentRecord{4230a398 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=204865, Int=0
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  904): [NET] getaddrinfo_proxy-
D/PMS     (  904): releaseWL(4256d468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42fe22c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209186, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42fe22c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43674248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43674248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1105): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(431ba750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(431ba750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(439ea7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=269187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(439ea7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(43fb3ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43fb3ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43fbc398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=329187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43fbc398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(430097e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(430097e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1339): GoogleAccountDataService.getToken()
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1339): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1105): com.google.android.gms (false,0)
,W/GLSActivity( 1339): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1339): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1339): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1339): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1339): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{41a91b98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1105): com.google.android.gms 2 11 4 12
,D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3610): [NET] getaddrinfo-,err=8
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3610): [NET] getaddrinfo-, 1
D/libc    ( 3610): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3610): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  904): acquireWL(42fe1128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42fe1128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(431b5a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=389187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(431b5a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(43e95430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43e95430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4249fcd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=449187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4249fcd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(43177ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
,D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  904): releaseWL(43177ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(430794b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/PMS     (  904): releaseWL(430794b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(430087e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=509187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(430087e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(43693c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43693c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1105): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(4317dec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4317dec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43a95928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=569187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43a95928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43f96a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43f96a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1218): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1218): sku_id=99
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1218): start background delete task...
D/ContactMessageStore( 1218): size: 0 , 0
,D/ContactMessageStore( 1218): Background delete complete
,D/PMS     (  904): acquireWL(42c69d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=629187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42c69d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3986 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
D/PMS     (  904): acquireWL(43e9ce00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10047}
,V/AlarmManager(  904): sending alarm PendingIntent{424607a8: PendingIntentRecord{42465ff8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449626711076, Int=10800000
,V/AlarmManager(  904): sending alarm PendingIntent{43edf518: PendingIntentRecord{4251d328 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449627134178, Int=0
,D/PMS     (  904): releaseWL(43e9ce00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1339): GoogleAccountDataService.getToken()
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (3986/10047)
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1339): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1339): GoogleAccountDataService.getToken()
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1339): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3610): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3610): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1339): GoogleAccountDataService.getToken()
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1339): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3610): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3610): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3610): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/Process (  904): killProcessQuiet, pid=3725
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3725:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3725
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(4369c638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1105): closing low battery warning: level=100
,D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(4369c638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(445ee630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{4315d888: PendingIntentRecord{43f8dca8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449627149412, Int=0
,D/PMS     (  904): releaseWL(445ee630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3610): [1] 5.onFinished: Installation state replication succeeded.
,W/GLSUser ( 1339): GoogleAccountDataService.getToken()
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1339): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1339): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1339): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1339): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1339): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1339): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1105): com.google.android.gms (false,0)
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{41be4870 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3610): [NET] getaddrinfo-,err=8
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3610): [NET] getaddrinfo-, 1
,D/libc    ( 3610): [NET] getaddrinfo_proxy+
I/RemoteViews.Performance( 1105): com.google.android.gms 4 12 4 12
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3610): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  904): acquireWL(4305f700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4305f700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1105): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42571ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=689186, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42571ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42569838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(42569838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(422e9330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(422e9330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(41edb5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=749187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(41edb5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(4245e900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(4245e900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(426dd140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=809187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426dd140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42545450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42545450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(421deb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(421deb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(424509b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=869187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(424509b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(4279fe98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/BatteryService(  904): n_update end
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/PowerUI ( 1105): closing low battery warning: level=100
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(4279fe98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(438cc340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(438cc340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4229e5e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=929187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4229e5e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1339): GoogleAccountDataService.getToken()
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1339): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1339): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1339): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1339): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1339): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1339): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1105): com.google.android.gms (false,0)
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{41e25c60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3610): [NET] getaddrinfo-,err=8
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3610): [NET] getaddrinfo-, 1
,D/libc    ( 3610): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3610): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1105): com.google.android.gms 1 10 3 12
,D/PMS     (  904): acquireWL(42c05e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(42c05e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43289ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=989187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43289ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(4252b6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  904): sending alarm PendingIntent{41d18260: PendingIntentRecord{423b0968 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781919, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42327118: PendingIntentRecord{421d7250 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449627431434, Int=900000
,V/AlarmManager(  904): sending alarm PendingIntent{42463670: PendingIntentRecord{42589528 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449627502049, Int=0
,W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PowerUsageService( 3943): call getInstance()
,D/SmartSyncUtils( 3943): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3943): MY_DEBUG = false
D/PMS     (  904): releaseWL(4252b6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  904): acquireWL(4257a4b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3943 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3943): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3943): [updateNmRange] USERNIGHT_TIMESTART = 2, USERNIGHT_TIMEEND = 7, nStart = 20, nEnd = 23, bNormalRange = true
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/SmartSyncScreenOnOffTimeReceiver( 3943): [updateNmRange] new USERNIGHT_TIMESTART = 20, new USERNIGHT_TIMEEND = 23
,I/FeedHostManager( 1246): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,D/PMS     (  904): acquireWL(430c0280): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1246 10075 null
I/FeedHostManager( 1246): NightMode begin at 0, end at 7
D/SmartSyncScreenOnOffTimeReceiver( 3943): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3943): SettingOnTime = 1449698400000, randomSettingOnTime = 1449698101000
D/SmartSyncScreenOnOffTimeReceiver( 3943): SettingOffTime = 1449687600000, randomSettingOffTime = 1449690381000
,D/SmartSyncScreenOnOffTimeReceiver( 3943): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3943): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3943): bNightModeTurnOffOnce = false
,I/FeedHostManager( 1246): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1449627502206, BeginTime: 1449615600000, EndTime: 1449640800000
,I/FeedHostManager( 1246): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
D/PMS     (  904): releaseWL(4257a4b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  904): acquireWL(44031d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10075}
D/PMS     (  904): releaseWL(430c0280): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
V/AlarmManager(  904): sending alarm PendingIntent{43ad0ea0: PendingIntentRecord{43137f88 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1449615600000, Int=0
D/PMS     (  904): acquireWL(4320d7a0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1246 10075 null
D/PMS     (  904): releaseWL(4320d7a0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  904): releaseWL(44031d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(43f5f848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43f5f848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43a45678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43a45678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(437820e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1049187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(437820e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43b99420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1105): closing low battery warning: level=100
,D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43b99420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(424fb820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(424fb820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42bde720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1109187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42bde720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(439e84e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(439e84e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43000438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1169187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43000438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42577268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(42577268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1105): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43fbf6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43fbf6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(443d9680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1229186, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(443d9680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(42ffdd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(42ffdd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1339): GoogleAccountDataService.getToken()
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1339): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1339): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1339): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1339): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1339): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1339): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1105): com.google.android.gms (false,0)
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{41edeae8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3610): [NET] getaddrinfo-,err=8
,D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3610): [NET] getaddrinfo-, 1
,D/libc    ( 3610): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
I/RemoteViews.Performance( 1105): com.google.android.gms 5 15 5 12
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3610): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  904): acquireWL(445ee680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(445ee680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43f83180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1289187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43f83180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43f6e4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43f6e4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43babaf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43babaf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43b92de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1349187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43b92de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(43b7e4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/BatteryService(  904): n_update end
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(43b7e4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4369dff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1409187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4369dff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(436985d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(436985d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(432045e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(432045e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(431eef18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1469187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(431eef18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(431e0308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(431e0308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(431cb6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1529186, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(431cb6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1339): GoogleAccountDataService.getToken()
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1339): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/GLSActivity( 1339): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1339): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1339): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1339): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1339): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1105): com.google.android.gms (false,0)
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{41fa6e20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3610): [NET] getaddrinfo-,err=8
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3610): [NET] getaddrinfo-, 1
,D/libc    ( 3610): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3610): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1105): com.google.android.gms 2 10 4 12
,D/PMS     (  904): acquireWL(424798a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  904): n_update end
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(424798a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(41f79778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1589187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(41f79778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(4231d4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
D/PMS     (  904): releaseWL(4231d4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(424f3060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(424f3060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(41f4e468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1649187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(41f4e468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(424e5d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(424e5d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4236d528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1709187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4236d528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(41b17130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(41b17130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(41ee41b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(41ee41b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
,D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(427a3728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1769187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427a3728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(432194c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(432194c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(427a7ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427a7ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(42ffdda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1829187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  904): Prepared write state in 33ms
,I/ProcessStatsService(  904): Pruning old procstats: /data/system/procstats/state-2015-12-08-10-25-58.bin
,I/ProcessStatsService(  904): Prepared write state in 43ms
,D/PMS     (  904): releaseWL(42ffdda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(4370a540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  904): sending alarm PendingIntent{41d18260: PendingIntentRecord{423b0968 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1731252, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{422cb378: PendingIntentRecord{42469c30 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820760, Int=1800000
,V/AlarmManager(  904): sending alarm PendingIntent{4265af40: PendingIntentRecord{42bf42e8 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1853991, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{425648e8: PendingIntentRecord{425015e8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449628329677, Int=1800000
V/AlarmManager(  904): sending alarm PendingIntent{42327118: PendingIntentRecord{421d7250 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449628331434, Int=900000
,D/PMS     (  904): acquireWL(42531590): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PMS     (  904): releaseWL(42531590): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  904): acquireWL(4247cc18): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1200 10028 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  904): acquireWL(43ee4670): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1200 10028 null
,D/PMS     (  904): releaseWL(4247cc18): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1200): Aggregate from 1449626529646 (log), 1449626529646 (data)
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): releaseWL(4370a540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): releaseWL(43ee4670): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(429837c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(429837c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1339): GoogleAccountDataService.getToken()
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1339): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1339): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1339): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1339): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1339): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1339): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1339): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1339): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3610): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3610): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3610): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3610): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3610): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1105): com.google.android.gms (false,0)
,D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3610): [NET] getaddrinfo-,err=8
D/libc    ( 3610): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3610): [NET] getaddrinfo-, 1
,D/libc    ( 3610): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3610): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3610): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{42002880 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress},
,I/RemoteViews.Performance( 1105): com.google.android.gms 2 23 2 12
,D/PMS     (  904): acquireWL(43f49ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1105): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1105): closing low battery warning: level=100
D/PowerUI ( 1105): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(43f49ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  904): killProcessQuiet, pid=3742
I/ActivityManager(  904): Killing 3742:com.htc.cs.dm/u0a98 (adj 15): empty for 1800s
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
,D/Process (  904): killProcessQuiet, pid=3549
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
,D/Process (  904): killProcessQuiet, pid=3646
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  904): Killing 3549:com.google.android.gm/u0a107 (adj 15): empty for 1800s
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
I/ActivityManager(  904): Killing 3646:com.google.android.apps.plus/u0a160 (adj 15): empty for 1800s
,D/Process (  904): killProcessQuiet, pid=3792
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/Process (  904): killProcessQuiet, pid=3775
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/Process (  904): killProcessQuiet, pid=3755
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  904): Killing 3792:com.htc.providers.settings:remote/u0a17 (adj 15): empty for 1800s
I/ActivityManager(  904): Killing 3775:com.htc.backup/1000 (adj 15): empty for 1801s
I/ActivityManager(  904): Killing 3755:com.google.android.apps.docs/u0a100 (adj 15): empty for 1801s
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3742
,I/ActivityManager(  904): Recipient 3549
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3792
,I/BatteryController( 1105): status:5 level:100 unsupport:false plugged:true
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3646
I/ActivityManager(  904): Recipient 3775
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3755
,D/PMS     (  904): acquireWL(42beab48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422cb2f8: PendingIntentRecord{41cdc290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1889187, Int=0
,I/IntentController( 1105): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42beab48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4039): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4039): ====startRecUseTime====
D/htc.customization.log.level( 4039):  is 
W/CustomizationLogLevel( 4039): Level value is invalid, use default level 2
D/CustomizationManager( 4039):  Read ACC file spent 0.100 (s)
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4039): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4039): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4039): Parsing tag category name = system
I/CustomizationCIDLoader( 4039): Parsing tag category name = application
I/CustomizationCIDLoader( 4039): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4039): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4039): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4039): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4039): Parsing tag category name = Settings
D/CustomizationManager( 4039):  Read CID file spent 0.152 (s)
D/CustomizationManager( 4039):  All configurations done spent 0.152 (s)
W/HtcNativeFlag( 4039): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4039): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4039): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4039): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4039, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  904): killProcessQuiet, pid=3860
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  904): Killing 3860:com.test.thalitest/u0a348 (adj 15): stop com.test.thalitest
W/asset   (  904): Copying FileAsset 0x69821270 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  904): Skipping PackageSetting{42210590 com.example.hello/10355} due to missing metadata
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1105): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1105): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1105): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1400): Ignoring removeGeofence because network location is disabled.
D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1767): Unregistering com.test.thalitest
E/acms    ( 1767): Could not unregister removed application com.test.thalitest
D/PMS     (  904): acquireWL(42224c18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1400 10028 null
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  904): releaseWL(42224c18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1301): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1301): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1246): Deferring update until onResume
D/Launcher( 1246): waitUntilResume // bindAppsRemoved
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/VoicemailCleanupService( 1272): Cleaning up data for package: com.test.thalitest
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/AccTypeManager( 1301): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PackageBroadcastService( 1200): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4053 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
E/ExternalAccountType( 1301): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/ActivityManager(  904): Delaying start of: ServiceRecord{43ed5818 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  904):   Scheme: "mms"
I/MultiDex( 4053): install
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4068 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4053): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PeopleContactsSync( 1200): CP2 sync disabled
I/MultiDex( 4053): loading existing secondary dex files
I/MultiDex( 4053): load found 1 secondary dex files
I/MultiDex( 4053): install done
I/Icing   ( 1200): doRemovePackageData com.test.thalitest
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1200, uid=10028, userID:0
D/PMS     (  904): acquireWL(424f0b30): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
D/PMS     (  904): releaseWL(424f0b30): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4068): install
I/MultiDex( 4068): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4068): loading existing secondary dex files
I/MultiDex( 4068): load found 1 secondary dex files
I/MultiDex( 4068): install done
I/ProviderInstaller( 4053): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ProviderInstaller( 4068): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
D/Process (  904): killProcessQuiet, pid=3907
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 3907:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1809s
E/SharedPreferencesImpl( 1181): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  904): Recipient 3907
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/[PluginManager]RegisterService( 1373): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1373): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1373): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9b31e0
W/[PluginManager]RegisterService( 1373): provider may killed!
W/[PluginManager]RegisterService( 1373): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1373): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1373): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1373): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1373): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1373): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1373): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1373): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1373): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1373): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1373): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1373): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1373): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1373): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1373): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1246): action: android.intent.action.PACKAGE_REMOVED
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
I/IcingCorporaProvider( 2653): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
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
I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  904): Resuming delayed broadcast
E/DropBoxManagerService(  904): Can't write: system_app_wtf
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4094 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4053): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4053): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4053): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4053): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4053): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4053): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4053): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4053): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4053): threadid=12: thread exiting with uncaught exception (group=0x41658e30)
E/SQLiteLog( 2653): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2653): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5c9ff558
W/dalvikvm( 2653): threadid=14: thread exiting with uncaught exception (group=0x41658e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2653): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2653): Process: com.google.android.googlequicksearchbox:search, PID: 2653
E/AndroidRuntime( 2653): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2653): 	at cid.d(PG:186)
E/AndroidRuntime( 2653): 	at clo.g(PG:594)
E/AndroidRuntime( 2653): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2653): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2653): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2653): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2653): 	at clr.tL(PG:827)
E/AndroidRuntime( 2653): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2653): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2653): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2653): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2653): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2653): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4053): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4053): Process: com.google.android.gms.drive, PID: 4053
E/AndroidRuntime( 4053): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4053): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4053): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4053): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4053): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4053): 	at ctn.run(SourceFile:985)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
D/Process ( 4053): killProcess, pid=4053
D/Process ( 4053): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/Process ( 2653): killProcess, pid=2653
D/Process ( 2653): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
I/ActivityManager(  904): Recipient 2653
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 2653) has died.
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 2653): Died!
D/WifiService(  904): Client connection lost with reason: 4
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
I/ActivityManager(  904): Recipient 4053
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4053) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10925ms
W/PackageManager(  904): Unable to load service info ResolveInfo{43a59d70 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4094): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4094): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4094): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4094): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4094): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4094): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4094): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4094): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4094): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4094): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4094): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4094): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4094): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4094): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4094): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4094): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4094): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4094): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4094): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4094): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4094): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4094): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4094): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4094): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4094): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4094): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4094): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4094): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4094): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4094): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4094): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4094): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4094): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4094): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4094): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4094): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4094): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4094): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4094): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4094): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4094): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4094): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4094): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4094): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4094): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4094): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4094): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4094): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4094): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4094): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4094): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4094): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4094): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4094): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4094): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4094): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4094): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4094): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4094): threadid=11: thread exiting with uncaught exception (group=0x41658e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4094): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4094): Process: com.google.android.apps.docs, PID: 4094
E/AndroidRuntime( 4094): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
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
E/AndroidRuntime( 4094): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4094): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4094): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4094): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4094): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
D/Process ( 4094): killProcess, pid=4094
D/Process ( 4094): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4112 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Recipient 4094
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4094) has died.
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41b1b010 +
I/Prism.WidgetManager( 1246): onLoadItems() +
W/ContextImpl( 4112): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4112): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4112): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4112): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4112): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4112): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4112): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4112): threadid=10: thread exiting with uncaught exception (group=0x41658e30)
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4125 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4112): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4112): Process: com.android.keychain, PID: 4112
E/AndroidRuntime( 4112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4112): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4112): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4112): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4112): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4112): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.android.keychain
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4125): getInstance(Context context)
D/AppTag  ( 4125): getInstance(Context context)
D/AppTag  ( 4125): onCreate()
I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4140 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/Process ( 4112): killProcess, pid=4112
D/Process ( 4112): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449628404535.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
D/Process (  904): killProcessQuiet, pid=3347
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3347:com.android.settings/1000 (adj 15): empty for 1802s
I/ActivityManager(  904): Recipient 4112
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.keychain (pid 4112) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10151ms

```
