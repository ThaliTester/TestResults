#### Test 573480789efee08_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3882 uid=10077 gids={50077}
D/PMS     (  909): acquireWL(439a1148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10077}
V/AlarmManager(  909): sending alarm PendingIntent{42579cc8: PendingIntentRecord{425c3268 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453981609222, Int=60000
,D/PMS     (  909): releaseWL(439a1148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
--------- beginning of /dev/log/main
D/SMSBackup( 3882): SMSBackupAgentService started
D/SMSBackup( 3882): Checking restore status
D/SMSBackup( 3882): Restore complete
D/SMSBackup( 3882): cancelCheckAlarm
D/SMSBackup( 3882): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  909): killProcessQuiet, pid=3416
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3416:com.google.android.music:main/u0a154 (adj 15): empty #17
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3416
D/MediaRouterService(  909): Client com.google.android.music (pid 3416): Died!
D/CustomizationManager( 3895): ====startRecUseTime====
D/htc.customization.log.level( 3895):  is 
W/CustomizationLogLevel( 3895): Level value is invalid, use default level 2
D/CustomizationManager( 3895):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3895): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3895): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3895): Parsing tag category name = system
I/CustomizationCIDLoader( 3895): Parsing tag category name = application
I/CustomizationCIDLoader( 3895): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3895): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3895): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3895): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3895): Parsing tag category name = Settings
D/CustomizationManager( 3895):  Read CID file spent 0.088 (s)
D/CustomizationManager( 3895):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 3895): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3895): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3895): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3895): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3895
D/PMS     (  909): acquireHCC(43972300): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(43954708): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
W/asset   (  909): Copying FileAsset 0x6cc59c18 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1126689264
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c013f0
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
E/cutils-trace( 3895): Error opening trace file: No such file or directory (2)
D/PMS     (  909): acquireWL(4390d978): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3906 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1248): [trimMemory] 20
W/asset   ( 3906): Copying FileAsset 0x5c719428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3906): Binding Chromium to main looper Looper (main, tid 1) {41aa8138}
I/LibraryLoader( 3906): Expected native library version number "",actual native library version number ""
I/chromium( 3906): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3906): Initializing chromium process, renderers=0
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43811f88:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3906): 1101781872: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  909): acquireWL(4381e428): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  909): acquireWL(43818448): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  909): releaseWL(43818448): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3906): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3906): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3906): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3906): Local Branch: 
I/Adreno-EGL( 3906): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3906): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3906):                  aa63bbd948f41d15fc72f585e
W/chromium( 3906): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3906): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3906): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3906): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3906): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3906): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3906): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3906): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3906): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3906): CordovaWebView is running on device made by: HTC
,W/AwContents( 3906): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Disable input method client, pid=1248
,I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +259ms
,W/ResourceType( 3906): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3906): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41aef0f8, mServedView=org.apache.cordova.engine.SystemWebView{41ab4e88 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 3906): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Enable input method client, pid=3906
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  909): releaseWL(4390d978): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3906): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3906): JniHelper::setJavaVM(0x4157a048), pthread_self() = 1663539472
,I/chromium( 3906): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 12.048MB for 63974-byte allocation
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 12.092MB for 95956-byte allocation
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 12.161MB for 143930-byte allocation
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 12.276MB for 215890-byte allocation
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 12.451MB for 323830-byte allocation
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 13.126MB for 728606-byte allocation
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 13.723MB for 1092904-byte allocation
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 14.644MB for 1639352-byte allocation
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 15.887MB for 2459024-byte allocation
,I/dalvikvm-heap( 3906): Grow heap (frag case) to 18.078MB for 3688532-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(43972300): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(43954708): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3906): Initializing JXcore engine
,W/jxcore-log( 3906): JXcore engine is ready
,W/jxcore-log( 3906): Starting JXcore engine
,W/jxcore-log( 3906): Platform android
W/jxcore-log( 3906): 
,W/jxcore-log( 3906): Process ARCH arm
W/jxcore-log( 3906): 
,I/jxcore-log( 3906): JXcore Cordova bridge is ready!
I/jxcore-log( 3906): 
,W/jxcore-log( 3906): JXcore engine is started
,E/jxcore  ( 3906): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3906): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3906): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3906): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 30ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  909): acquireWL(437afa90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
,I/FeedHostManager( 1248): [onResume]
,I/FeedProviderManager( 1248): onResume
I/SocialFeedProvider( 1248): +onResume
I/SocialFeedProvider( 1248): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1248): -onResume
,I/ConnectivityHelper( 1248): [getCurrentConnectionType] no network connection
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.launcher (1248/10075)
,I/InputMethodManagerService(  909): Disable input method client, pid=3906
,W/IInputConnectionWrapper( 3906): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  909): Enable input method client, pid=1248
,D/PMS     (  909): releaseWL(437afa90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/SensorManager(  909): mEventCount = 1050
,D/Process (  909): killProcessQuiet, pid=3728
,I/ActivityManager(  909): Killing 3728:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,E/libEGL  ( 3906): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  909): Recipient 3728
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,D/PMS     (  909): releaseWL(4381e428): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  909): Going to sleep due to screen timeout...
,W/PMS     (  909): mWirelessDisplayManager is null
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42040bd0
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/BatSI   (  909): Couldn't get kernel wake lock stats
D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42040bd0, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4210ebd8
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@425d8fa0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 376ms
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/PMS     (  909): OOBE c monitor 11
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1232): ScreenObserver: OFF
D/NfcService( 1232): applyRouting - 0
,I/IntentController( 1108): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42e8fe60)
,D/NfcService( 1232): applyRouting -2
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=1248
D/PMN     (  909): wakingUp
D/PMS     (  909): acquireWL(42df7470): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  909): releaseWL(42df7470): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  909): No lock screen! windowToken=null
D/PMS     (  909): acquireWL(42d20130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42d20130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/PMN     (  909): onScreenOn
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2205): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2205): [MTP][onReceive]-
D/NfcService( 1232): applyRouting - 0
,D/AutoSetting( 1386): receiver - intent: android.intent.action.USER_PRESENT
D/NfcService( 1232): applyRouting -2
,D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): acquireWL(42b9b648): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  909): releaseWL(42b9b648): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/TetherSettings( 3352): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3352): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3352): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3352): Cust_ConnectToPC   : spcsc>false
D/        ( 3352): Cust_ConnectToPC   : IPT>true
,D/        ( 3352): Cust_ConnectToPC   : Singel_USB>false
D/AutoSetting( 1386): service - onCreate()
,W/Settings( 3352): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
E/SmartNS_Utility( 3352): hasRemovableStorageSlot: true
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
D/SmartNS_Utility( 3352): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3352): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  909):    returned false
I/PSReceiver( 3352): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1386): service - AddressCache: using context: com.htc.Weather
,I/ClockThread( 1108): stop update clock
I/SmartNS_PSService( 3352): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3352): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3352):  defaultType:0
,D/AutoSetting( 1386): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/ContextImpl( 3352): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/LocationManagerService(  909): request 424eba88 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
,V/SRS_Proc(  372): ParamSet string: screen_state=on
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=3963 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  909): updateScreenOn: false
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/TetherSettings( 3352): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3352): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3352): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3352): Cust_ConnectToPC   : spcsc>false
D/        ( 3352): Cust_ConnectToPC   : IPT>true
,D/        ( 3352): Cust_ConnectToPC   : Singel_USB>false
D/PMS     (  909): acquireWL(43a72ee0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1401 10028 null
D/SmartNS_NSReceiver( 3352): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3352): Index of the first 1 = -1
D/PMS     (  909): releaseWL(43a72ee0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/ContextImpl( 3352): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3352): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4210ebd8
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4210ebd8, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@425d8fa0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/Settings( 3352): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3352): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3352): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3352): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3352): [ACC]android_networking:tethering_guard_support=false
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(43a69900): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,I/FeedHostManager( 1248): [onPause]
,I/FeedProviderManager( 1248): onPause
,I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c013f0
I/SocialFeedProvider( 1248): +onPause
,I/SocialFeedProvider( 1248): -onPause
W/ActivityManager(  909): Disable JIT of com.htc.bgp
,I/ActivityManager(  909): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3977 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/AlarmManager(  909): ACTION_SCREEN_OFF
,I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19528 mDataStallAlarmIntent=null
I/AlarmManager(  909): [AlarmQueuing] wifi connection: false
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  909):    returned false
D/PMS     (  909): acquireWL(43a60f90): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
D/PMS     (  909): releaseWL(43a60f90): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/PMS     (  909): releaseWL(43a69900): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  909): updateScreenOn: false
,D/ContactMessageStore( 1220): start background delete task...
D/ContactMessageStore( 1220): size: 0 , 0
,D/ContactMessageStore( 1220): Background delete complete
,I/CalendarProvider2( 3977): Created com.android.providers.calendar.CalendarAlarmManager@41ae3bc8(com.android.providers.calendar.HtcCalendarProvider@41acbf50)
,D/CalendarProvider2( 3977): wait start:true
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] getTotalRam: 1873 Mb
,D/CalendarProvider2( 3977): wait end:false
D/PMS     (  909): acquireWL(43a31150): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1401 10028 null
,D/PMS     (  909): releaseWL(43a31150): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1386): service - mHandler: cancel location update
D/AutoSetting( 1386): service -           changes count: 0
,W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3963): isEpsOn(), nState = 0
D/PMS     (  909): acquireWL(43a2e0d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3963 1000 null
,D/SmartSyncUtils( 3963): getMobilePolicyEnabled, result = true,
D/PMS     (  909): releaseWL(43a2e0d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 3963): isEpsOn(), nState = 0
D/SmartSyncUtils( 3963): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3963): getMobilePolicyEnabled, result = true
D/WifiService(  909): New client listening to asynchronous messages
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425d8fa0
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425d8fa0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425d8fa0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425d8fa0
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425d94e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425d94e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 3977): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3977): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/ProviderChangeReceiver( 3750): ---------------------------------------------------
,D/ProviderChangeReceiver( 3750): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3750): start to updateAlertNotification!
,D/AlertService( 3750): No fired or scheduled alerts
D/HtcAlertUtils( 3750): -- cancelReminderNotification --
,D/HtcAlertUtils( 3750): broadcastExistReminder!
W/ContextImpl( 3764): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  909): killProcessQuiet, pid=3398
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3398:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3398
,D/PMS     (  909): acquireWL(42f55450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=113692, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42f55450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  909): killProcessQuiet, pid=3438
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3438:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3438
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{42d85b58 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  909): acquireWL(42e3fd10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42e3fd10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1386): service - handleMessage() stop self
,D/AutoSetting( 1386): service - handleMessage() quit looper
,D/AutoSetting( 1386): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=3557
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3557:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3557
,D/PMS     (  909): acquireWL(42df6ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10028}
,V/AlarmManager(  909): sending alarm PendingIntent{43c10b30: PendingIntentRecord{42407d68 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140298, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{4202b4d0: PendingIntentRecord{423b3b30 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140947, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
V/AlarmManager(  909): sending alarm PendingIntent{422bce78: PendingIntentRecord{42340810 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145145, Int=0
,D/PMS     (  909): acquireWL(42d998d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  909): [NET] getaddrinfo_proxy-
D/PMS     (  909): releaseWL(42df6ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): releaseWL(42d998d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(425509e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(425509e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(42550058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=173692, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42550058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(4254e330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4254e330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(424860d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  909): [NET] getaddrinfo_proxy-
V/AlarmManager(  909): sending alarm PendingIntent{422bce78: PendingIntentRecord{42340810 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=205167, Int=0
D/PMS     (  909): releaseWL(424860d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42474a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42474a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(42470520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=233692, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42470520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(4245fd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4245fd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(4244b338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=293693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4244b338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(42425928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42425928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(4241f580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=353693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4241f580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1555): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1555): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,W/GLSActivity( 1341): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1341): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1341): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1341): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1341): 	at dalvik.system.NativeStart.run(Native Method)
D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41aae778 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3636): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3636): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3636): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3636): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3636): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1108): com.google.android.gms 1 10 3 12
D/libc    ( 3636): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3636): [NET] getaddrinfo-,err=8
D/libc    ( 3636): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3636): [NET] getaddrinfo-, 1
D/libc    ( 3636): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3636): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3636): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  909): acquireWL(41b2c960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(41b2c960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(41d323d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=413693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(41d323d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(41ef22b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(41ef22b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(42e4c068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=473693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e4c068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(4249e5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4249e5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(422bfdf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(422bfdf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(4241f068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=533693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4241f068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(421aef80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(421aef80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(41d06208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=593692, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(41d06208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(432d3508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(432d3508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1220): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1220): sku_id=99
,D/ContactMessageStore( 1220): start background delete task...
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1220): size: 0 , 0
,D/ContactMessageStore( 1220): Background delete complete
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(42e21948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=653693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e21948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1555): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1555): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1341): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1341): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1341): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1341): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1341): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41af6400 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3636): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3636): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3636): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3636): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3636): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1108): com.google.android.gms 1 8 4 12
D/libc    ( 3636): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3636): [NET] getaddrinfo-,err=8
D/libc    ( 3636): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3636): [NET] getaddrinfo-, 1
,D/libc    ( 3636): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3636): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3636): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  909): acquireWL(43dfeb88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43dfeb88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42e27160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=713693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e27160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(424075f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(424075f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(420aaa48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=773693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(420aaa48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42f52aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f52aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42e96078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=833693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e96078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42503b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42503b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(4237e5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=893692, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4237e5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(424e9c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(424e9c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42512a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=953693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42512a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1555): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1555): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1341): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1341): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1341): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1341): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1341): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,E/PlayEventLogger( 3636): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3636): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3636): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3636): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3636): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41afd4a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3636): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3636): [NET] getaddrinfo-,err=8
D/libc    ( 3636): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3636): [NET] getaddrinfo-, 1
,D/libc    ( 3636): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3636): [NET] getaddrinfo_proxy-
I/RemoteViews.Performance( 1108): com.google.android.gms 1 15 4 12
,E/PlayEventLogger( 3636): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
W/SocketClient(  364): write error (Broken pipe)
,D/PMS     (  909): acquireWL(42dfc988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42dfc988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(424eb398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{424bf720: PendingIntentRecord{43a2b2f8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453982516851, Int=0
,D/SmartSyncUtils( 3963): isEpsOn(), nState = 0
D/PMS     (  909): acquireWL(4237a2a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3963 1000 null
D/PMS     (  909): releaseWL(424eb398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 3963): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3963): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3963): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3963): SettingOnTime = 1454047200000, randomSettingOnTime = 1454045864000
,D/SmartSyncScreenOnOffTimeReceiver( 3963): SettingOffTime = 1454025600000, randomSettingOffTime = 1454030625000
,D/SmartSyncScreenOnOffTimeReceiver( 3963): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3963): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3963): bNightModeTurnOffOnce = false
D/PMS     (  909): releaseWL(4237a2a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  909): acquireWL(43284cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1013693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43284cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42ff6b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42ff6b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,D/PMS     (  909): acquireWL(4254a520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9c718: PendingIntentRecord{423dfa10 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781154, Int=0
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4021 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{42182ff8: PendingIntentRecord{425c9cb0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453981725982, Int=10800000
,W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,V/AlarmManager(  909): sending alarm PendingIntent{4254a278: PendingIntentRecord{42541778 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453982446262, Int=900000
,V/AlarmManager(  909): sending alarm PendingIntent{4230c3b0: PendingIntentRecord{42481b70 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453982557384, Int=1800000
D/PowerUsageService( 3963): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3963): MY_DEBUG = false
D/PMS     (  909): acquireWL(42f2ebf0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1200 10028 null
,D/PMS     (  909): releaseWL(4254a520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  909): acquireWL(42558438): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1200 10028 null
,D/PMS     (  909): releaseWL(42f2ebf0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1200): Aggregate from 1453980757331 (log), 1453980757331 (data)
W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4021/10047)
,W/EventLogAggregator( 1200): Unknown tag: install_package_attempt
W/EventLogAggregator( 1200): Unknown tag: snet
,W/EventLogAggregator( 1200): Unknown tag: snet_gcore
,D/PMS     (  909): releaseWL(42558438): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/Process (  909): killProcessQuiet, pid=3182
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3182:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3182
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(43349440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1073692, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43349440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(432fbba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(432fbba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(43273a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1133692, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43273a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4322b468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4322b468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43165b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1193693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43165b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42fd6bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42fd6bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1555): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1555): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/PMS     (  909): acquireWL(42a3e290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1253693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42a3e290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1555): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1555): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1341): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1341): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1341): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1341): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1341): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,E/PlayEventLogger( 3636): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3636): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3636): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3636): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3636): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3636): 	at dalvik.system.NativeStart.run(Native Method)
D/libc    ( 3636): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3636): [NET] getaddrinfo-,err=8
D/libc    ( 3636): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3636): [NET] getaddrinfo-, 1
,D/libc    ( 3636): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3636): [NET] getaddrinfo_proxy-
E/PlayEventLogger( 3636): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41b34990 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.google.android.gms 1 13 3 12
,D/PMS     (  909): acquireWL(423ae448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423ae448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42387f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc7ae8: PendingIntentRecord{41c60928 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1313693, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42387f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4040): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4040): ====startRecUseTime====
D/htc.customization.log.level( 4040):  is 
W/CustomizationLogLevel( 4040): Level value is invalid, use default level 2
D/CustomizationManager( 4040):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4040): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4040): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4040): Parsing tag category name = system
I/CustomizationCIDLoader( 4040): Parsing tag category name = application
I/CustomizationCIDLoader( 4040): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4040): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4040): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4040): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4040): Parsing tag category name = Settings
D/CustomizationManager( 4040):  Read CID file spent 0.092 (s)
D/CustomizationManager( 4040):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 4040): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4040): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4040): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4040): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4040, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  909): killProcessQuiet, pid=3906
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  909): Killing 3906:com.test.thalitest/u0a189 (adj 15): stop com.test.thalitest
W/asset   (  909): Copying FileAsset 0x63c4b2e0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
I/acms    ( 1766): Unregistering com.test.thalitest
E/acms    ( 1766): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1555): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1555): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1555): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1401): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1304): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1304): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): acquireWL(43dd7198): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1401 10028 null
D/PMS     (  909): releaseWL(43dd7198): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1274): Cleaning up data for package: com.test.thalitest
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AccTypeManager( 1304): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/Launcher( 1248): Deferring update until onResume
D/Launcher( 1248): waitUntilResume // bindAppsRemoved
D/PackageBroadcastService( 1200): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4054 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
E/ExternalAccountType( 1304): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/MultiDex( 4054): install
D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4054): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  909): Delaying start of: ServiceRecord{440d6990 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4054): loading existing secondary dex files
I/MultiDex( 4054): load found 1 secondary dex files
I/MultiDex( 4054): install done
I/PeopleContactsSync( 1200): CP2 sync disabled
I/ActivityManager(  909): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4070 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1200, uid=10028, userID:0
I/ProviderInstaller( 4054): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  909): acquireWL(43324238): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
I/Icing   ( 1200): doRemovePackageData com.test.thalitest
D/PMS     (  909): releaseWL(43324238): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4070): install
I/MultiDex( 4070): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  909): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4070): loading existing secondary dex files
I/MultiDex( 4070): load found 1 secondary dex files
I/MultiDex( 4070): install done
I/ProviderInstaller( 4070): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  909): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1386): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1386): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1248): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2651): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4090 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/PackageManager(  909): Unable to load service info ResolveInfo{422be7f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4054): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4054): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4054): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4054): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4054): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4054): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4054): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4054): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4054): threadid=12: thread exiting with uncaught exception (group=0x41672e30)
W/ContextImpl( 4090): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/ActivityManager(  909): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4054): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4054): Process: com.google.android.gms.drive, PID: 4054
E/AndroidRuntime( 4054): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4054): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4054): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4054): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4054): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4054): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4054): 	at ctn.run(SourceFile:985)
D/PMS     (  909): acquireWL(44107348): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
I/ActivityManager(  909): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
D/Process ( 4054): killProcess, pid=4054
D/Process ( 4054): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
E/SQLiteDatabase( 4090): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4090): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4090): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4090): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4090): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4090): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4090): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4090): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4090): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4090): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4090): threadid=10: thread exiting with uncaught exception (group=0x41672e30)
E/SQLiteLog( 2651): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2651): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5c8f2400
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/AndroidRuntime( 4090): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4090): Process: com.android.keychain, PID: 4090
E/AndroidRuntime( 4090): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4090): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4090): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4090): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4090): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4090): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4090): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4090): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4090): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  909): Recipient 4054
I/ActivityManager(  909): Process com.google.android.gms.drive (pid 4054) has died.
E/ActivityManager(  909): App crashed! Process: com.android.keychain
E/IcingCorporaProvider( 2651): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2651): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2651): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2651): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2651): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2651): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2651): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2651): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2651): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2651): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2651): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2651): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2651): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2651): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2651): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2651): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2651): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2651): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2651): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2651): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2651): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2651): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2651): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2651): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2651): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2651): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2651): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2651): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2651): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2651): 	... 15 more
W/IcingCorporaProvider( 2651): notifyTableChanged failed.
W/IcingCorporaProvider( 2651): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2651): UpdateCorporaTask done [took 190 ms] updated apps [took 190 ms] 
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  909): Resuming delayed broadcast
D/Process ( 4090): killProcess, pid=4090
D/Process ( 4090): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4108 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453982821515.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
D/PMS     (  909): releaseWL(44107348): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/AppTag  ( 4108): getInstance(Context context)
D/AppTag  ( 4108): getInstance(Context context)
D/AppTag  ( 4108): onCreate()
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  909): start
I/ActivityManager(  909): Recipient 4090
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.keychain (pid 4090) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/DeviceManagement( 3802): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 3802): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
D/PMS     (  909): acquireWL(424a97f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3673 10160 null
D/PMS     (  909): releaseWL(424a97f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/DeviceManagement( 3802): WorkflowService: Starting workflow service
I/DeviceManagement( 3802): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c77ef8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 3802): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3802): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 3802): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3802): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 3802): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 3802): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager(  909): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4129 uid=10099 gids={50099, 3003, 5012}
E/SQLiteDBG( 3802): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5c8e0740
W/DeviceManagement( 3802): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c77ef8]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 3802): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 3802): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 3802): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 3802): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 3802): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 3802): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 3802): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 3802): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 3802): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 3802): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 3802): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 3802): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 3802): WorkflowService: Stopping workflow service
D/Process (  909): killProcessQuiet, pid=3781
I/ActivityManager(  909): Killing 3781:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AtomicFile(  909): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  909): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  909): Recipient 3781
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Documents( 4129): Loading roots for com.android.providers.downloads.documents
D/Documents( 4129): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4129): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4129): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4129): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4129): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4129): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4129): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4129): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4129): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4129): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4129): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4129): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4129): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4129): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4129): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4129): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4129): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4129): threadid=1: thread exiting with uncaught exception (group=0x41672e30)
E/AndroidRuntime( 4129): FATAL EXCEPTION: main
E/AndroidRuntime( 4129): Process: com.android.documentsui, PID: 4129
E/AndroidRuntime( 4129): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4129): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4129): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4129): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4129): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4129): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4129): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4129): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4129): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4129): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4129): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4129): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4129): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4129): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4129): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4129): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4129): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4129): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4129): 	... 10 more
I/ActivityManager(  909): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4142 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process (  909): killProcessQuiet, pid=3834
I/ActivityManager(  909): Killing 3834:com.htc.backup/1000 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/ActivityManager(  909): App crashed! Process: com.android.documentsui
D/GCM     ( 1341): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4129): killProcess, pid=4129
D/Process ( 4129): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453982821729.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
I/ActivityManager(  909): Recipient 3834
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  909): killProcessQuiet, pid=3851
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  909): Killing 3851:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  909): Recipient 4129
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.documentsui (pid 4129) has died.
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3851
D/GCM     ( 1341): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ExternalStorage( 4142): After updating volumes, found 1 active roots
I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4158 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4158): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4158): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4158): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4158): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4158): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4158): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4158): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4158): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4158): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4158): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4158): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4158): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4158): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4158): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4158): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4158): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4158): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4158): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4158): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4158): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4158): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4158): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4158): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 4158): Opened MyDB.db in read-only mode
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b36f38 +
I/Prism.WidgetManager( 1248): onLoadItems() +

```
