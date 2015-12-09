#### Test 5065027873d6a28_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  908): acquireWL(42791210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
V/AlarmManager(  908): sending alarm PendingIntent{439763d0: PendingIntentRecord{43e1b750 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449626587649, Int=0
,D/PMS     (  908): releaseWL(42791210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
--------- beginning of /dev/log/main
D/Finsky  ( 3526): [365] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3526): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
E/cutils-trace( 3846): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3846): ====startRecUseTime====
D/htc.customization.log.level( 3846):  is 
W/CustomizationLogLevel( 3846): Level value is invalid, use default level 2
D/CustomizationManager( 3846):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3846): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3846): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3846): Parsing tag category name = system
I/CustomizationCIDLoader( 3846): Parsing tag category name = application
I/CustomizationCIDLoader( 3846): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3846): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3846): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3846): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3846): Parsing tag category name = Settings
D/CustomizationManager( 3846):  Read CID file spent 0.102 (s)
D/CustomizationManager( 3846):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 3846): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3846): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3846): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3846): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3846
D/PMS     (  908): acquireHCC(43470040): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(42a3d710): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
W/asset   (  908): Copying FileAsset 0x69c79e08 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1114820392
D/PMS     (  908): acquireWL(428a0638): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/FeedHostManager( 1246): [onPause]
I/FeedProviderManager( 1246): onPause
I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420067f0
I/SocialFeedProvider( 1246): +onPause
I/SocialFeedProvider( 1246): -onPause
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3857 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1246): [trimMemory] 20
W/asset   ( 3857): Copying FileAsset 0x5c79e428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3857): Binding Chromium to main looper Looper (main, tid 1) {41f20d58}
I/LibraryLoader( 3857): Expected native library version number "",actual native library version number ""
I/chromium( 3857): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3857): Initializing chromium process, renderers=0
D/PMS     (  908): acquireWL(44404038): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  908): acquireWL(43f81dd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  908): releaseWL(44404038): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@434727c0:true
D/BluetoothAdapter( 3857): 1106472120: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3857): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3857): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3857): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3857): Local Branch: 
I/Adreno-EGL( 3857): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3857): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3857):                  aa63bbd948f41d15fc72f585e
W/chromium( 3857): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3857): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3857): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3857): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3857): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3857): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3857): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3857): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3857): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3857): CordovaWebView is running on device made by: HTC
,W/AwContents( 3857): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Disable input method client, pid=1246
W/ResourceType( 3857): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3857): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41f68240, mServedView=org.apache.cordova.engine.SystemWebView{41f2dfd0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  908): Enable input method client, pid=3857
W/AwContents( 3857): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1183): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1183): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +290ms
D/PMS     (  908): releaseWL(428a0638): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 3857): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3857): JniHelper::setJavaVM(0x41ae1010), pthread_self() = 1663368080
D/JX-Cordova( 3857): jxcore cordova android initializing
W/dalvikvm( 3857): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
I/SensorManager(  908): mEventCount = 900
,I/dalvikvm-heap( 3857): Grow heap (frag case) to 11.651MB for 143930-byte allocation
,I/dalvikvm-heap( 3857): Grow heap (frag case) to 11.768MB for 215890-byte allocation
,I/dalvikvm-heap( 3857): Grow heap (frag case) to 11.936MB for 323830-byte allocation
,I/dalvikvm-heap( 3857): Grow heap (frag case) to 12.193MB for 485740-byte allocation
,I/dalvikvm-heap( 3857): Grow heap (frag case) to 12.595MB for 728606-byte allocation
,I/dalvikvm-heap( 3857): Grow heap (frag case) to 14.106MB for 1639352-byte allocation
,I/dalvikvm-heap( 3857): Grow heap (frag case) to 15.476MB for 2459024-byte allocation
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(43470040): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  908): releaseHCC(42a3d710): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3857): Grow heap (frag case) to 17.539MB for 3688532-byte allocation
,W/jxcore-log( 3857): Initializing JXcore engine
,W/jxcore-log( 3857): JXcore engine is ready
,W/jxcore-log( 3857): Starting JXcore engine
,W/jxcore-log( 3857): Platform android
W/jxcore-log( 3857): 
,W/jxcore-log( 3857): Process ARCH arm
W/jxcore-log( 3857): 
,I/jxcore-log( 3857): JXcore Cordova bridge is ready!
I/jxcore-log( 3857): 
,W/jxcore-log( 3857): JXcore engine is started
,I/chromium( 3857): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3857): Error!: missing ) after argument list
E/jxcore  ( 3857): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,D/PMS     (  908): releaseWL(43f81dd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/chromium( 3857): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3857): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 39ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  908): acquireWL(43677640): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
,I/FeedHostManager( 1246): [onResume]
,I/FeedProviderManager( 1246): onResume
I/SocialFeedProvider( 1246): +onResume
I/SocialFeedProvider( 1246): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1246): -onResume
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.launcher (1246/10076)
I/ConnectivityHelper( 1246): [getCurrentConnectionType] no network connection
,I/InputMethodManagerService(  908): Disable input method client, pid=3857
,I/InputMethodManagerService(  908): Enable input method client, pid=1246
,W/IInputConnectionWrapper( 3857): reportFullscreenMode on inactive InputConnection
,D/PMS     (  908): releaseWL(43677640): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  908): killProcessQuiet, pid=3562
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  908): Killing 3562:com.google.android.gm/u0a107 (adj 15): empty #17
,E/libEGL  ( 3857): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  908): Recipient 3562
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4257d4a0
,D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/PMS     (  908): mWirelessDisplayManager is null
,W/BatSI   (  908): Couldn't get kernel wake lock stats
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4257d4a0, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422e2ed8
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@42814898
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 315ms
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4449abe0)
D/NfcService( 1228): ScreenObserver: OFF
,D/NfcService( 1228): applyRouting - 0
,D/NfcService( 1228): applyRouting -2
,I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  908): Disable input method client, pid=1246
D/PMS     (  908): acquireWL(427a0d88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMN     (  908): wakingUp
D/PMS     (  908): releaseWL(427a0d88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  908): acquireWL(429a1700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(429a1700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
I/WindowManager(  908): No lock screen! windowToken=null
D/PMN     (  908): onScreenOn
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/MtpService( 2154): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1228): applyRouting - 0
,D/MtpService( 2154): [MTP][onReceive]-
,D/NfcService( 1228): applyRouting -2
,D/AutoSetting( 1299): receiver - intent: android.intent.action.USER_PRESENT
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): acquireWL(43da14e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  908): releaseWL(43da14e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
D/TetherSettings( 3302): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3302): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3302): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3302): Cust_ConnectToPC   : spcsc>false
D/        ( 3302): Cust_ConnectToPC   : IPT>true
D/        ( 3302): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3302): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3302): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3302): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3302): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1299): service - onCreate()
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
,D/AutoSetting( 1299): service - AddressCache: using context: com.htc.Weather
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,I/PSReceiver( 3302): onReceive:android.intent.action.USER_PRESENT
D/LocationManagerService(  908): request 426b3140 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1299): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
,I/ClockThread( 1107): stop update clock
,D/WifiNative-wlan0(  908):    returned false
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3302): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3302): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3302):  defaultType:0
,V/SRS_Proc(  364): ParamSet string: screen_state=on
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  908): updateScreenOn: false
,W/ActivityManager(  908): Disable JIT of com.htc.bgp
,I/ActivityManager(  908): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3912 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/PMS     (  908): acquireWL(44062ee8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  908): releaseWL(44062ee8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(445c79d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(445c79d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422e2ed8
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422e2ed8, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@42814898
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/FeedHostManager( 1246): [onPause]
,I/FeedProviderManager( 1246): onPause
,I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420067f0
I/SocialFeedProvider( 1246): +onPause
,I/SocialFeedProvider( 1246): -onPause
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(43d63b98): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
,D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,I/AlarmManager(  908): [AlarmQueuing] wifi connection: false
,D/PMS     (  908): releaseWL(43d63b98): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19650 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  908):    returned false
,I/CalendarProvider2( 3912): Created com.android.providers.calendar.CalendarAlarmManager@41f5baa0(com.android.providers.calendar.HtcCalendarProvider@41f43e28)
,V/SRS_Proc(  364): ParamSet string: screen_state=off
D/PMS     (  908): acquireWL(4359ff28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
,D/PMS     (  908): releaseWL(4359ff28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/CalendarProvider2( 3912): wait start:true
D/NetworkPolicy(  908): updateScreenOn: false
,D/ContactMessageStore( 1214): start background delete task...
D/ContactMessageStore( 1214): size: 0 , 0
D/ContactMessageStore( 1214): Background delete complete
,D/CalendarProvider2( 3912): wait end:false
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3931 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  908): acquireWL(4289b7c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] getTotalRam: 1873 Mb
D/PMS     (  908): releaseWL(4289b7c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43670990): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): releaseWL(43670990): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1299): service - mHandler: cancel location update
,D/AutoSetting( 1299): service -           changes count: 0
,D/SmartSyncUtils( 3931): isEpsOn(), nState = 0
D/PMS     (  908): acquireWL(441f5d68): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3931 1000 null
,D/SmartSyncUtils( 3931): getMobilePolicyEnabled, result = true
D/PMS     (  908): releaseWL(441f5d68): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 3931): isEpsOn(), nState = 0
D/SmartSyncUtils( 3931): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3931): isEpsOn(), nState = 0
D/WifiService(  908): New client listening to asynchronous messages
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42814898
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42814898, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42814898, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42814898
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@428182a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@428182a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  908): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  908): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  908): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  908): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  908): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  908): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  908): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 3912): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3912): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3674): ---------------------------------------------------
,D/ProviderChangeReceiver( 3674): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3674): start to updateAlertNotification!
,W/ContextImpl( 3688): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3674): No fired or scheduled alerts
,D/HtcAlertUtils( 3674): -- cancelReminderNotification --
,D/HtcAlertUtils( 3674): broadcastExistReminder!
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  908): killProcessQuiet, pid=3647
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3647:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3647
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,D/Process (  908): killProcessQuiet, pid=3377
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3377:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3377
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(43f41cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{424a9988: PendingIntentRecord{4298a128 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=119802, Int=0
,D/PMS     (  908): releaseWL(43f41cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(444cb3a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1329 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1329/10029)
,D/PMS     (  908): releaseWL(444cb3a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{42a128e0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(43d72130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43d72130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1299): service - handleMessage() stop self
,D/AutoSetting( 1299): service - onDestroy() END
,D/AutoSetting( 1299): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=2752
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2752:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2752
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(43f90be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{4409cb68: PendingIntentRecord{42961860 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137609, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{427367e8: PendingIntentRecord{428c47f8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141013, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{422a02d0: PendingIntentRecord{42808110 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145055, Int=0
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  357): [NET] get_iface_protocol fail: 
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  357): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  357): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
D/PMS     (  908): acquireWL(435ac128): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(435ac128): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  908): releaseWL(43f90be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  908): acquireWL(4444fe28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=152983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4444fe28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1214): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(435b0070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(435b0070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(438d0020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(438d0020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1329): disconnect managed GoogleApiClient
,D/PMS     (  908): acquireWL(44020968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{43647a98: PendingIntentRecord{4298a128 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=179545, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{422a02d0: PendingIntentRecord{42808110 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=205287, Int=0
,D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
,D/PMS     (  908): acquireWL(4362fcb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1329 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  357): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  357): [NET] get_iface_protocol fail: 
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  357): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  357): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
D/PMS     (  908): releaseWL(44020968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1329/10029)
,D/PMS     (  908): releaseWL(4362fcb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(444b7bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=212983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(444b7bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4373a6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4373a6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(43da1680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=272984, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43da1680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(4445cd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4445cd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43047920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=332983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43047920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3526): [NET] getaddrinfo-,err=8
D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3526): [NET] getaddrinfo-, 1
,D/libc    ( 3526): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  357): [NET] get_iface_protocol fail: 
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  357): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  357): [NET] getaddrinfo-,err=7
,D/libc    ( 3526): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(42a40358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42a40358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(436c0740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=392983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(436c0740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43d3f538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43d3f538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(44055948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=452983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44055948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42ab3208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42ab3208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(436f5ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=512983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(436f5ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43c4cb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43c4cb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(440a8f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=572983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(440a8f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42a37860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42a37860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1214): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1214): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1214): sku_id=99
,D/ContactMessageStore( 1214): start background delete task...
,D/ContactMessageStore( 1214): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1214): size: 0 , 0
,D/ContactMessageStore( 1214): Background delete complete,
,D/PMS     (  908): acquireWL(436de100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=632983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(436de100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  908): killProcessQuiet, pid=3590
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3590:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3590
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3526): [NET] getaddrinfo-,err=8
D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3526): [NET] getaddrinfo-, 1
D/libc    ( 3526): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  357): [NET] get_iface_protocol fail: 
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  357): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  357): [NET] getaddrinfo-,err=7
,D/libc    ( 3526): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(4401f408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4401f408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(44402738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=692983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44402738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43980f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43980f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43f2db38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=752983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43f2db38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(440dc6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(440dc6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4446d4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4446d4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43b5b7a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=812984, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43b5b7a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43f58098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43f58098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(44093e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=872984, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44093e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42884778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42884778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(435e28c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=932983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(435e28c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3526): [NET] getaddrinfo-,err=8
D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3526): [NET] getaddrinfo-, 1
,D/libc    ( 3526): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  357): [NET] get_iface_protocol fail: 
,D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  357): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  357): [NET] getaddrinfo-,err=7
,D/libc    ( 3526): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(42a59be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42a59be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43644c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=992983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43644c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43b5a3c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/SmartSyncUtils( 3931): isEpsOn(), nState = 0
V/AlarmManager(  908): sending alarm PendingIntent{428fc4f8: PendingIntentRecord{42d12438 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449627494690, Int=0
,D/PMS     (  908): releaseWL(43b5a3c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43fe5cb0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3931 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3931): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3931): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3931): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 3931): SettingOnTime = 1449640800000, randomSettingOnTime = 1449638721000
,D/SmartSyncScreenOnOffTimeReceiver( 3931): SettingOffTime = 1449712800000, randomSettingOffTime = 1449713411000
D/SmartSyncScreenOnOffTimeReceiver( 3931): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3931): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3931): bNightModeTurnOffOnce = false
D/PMS     (  908): acquireWL(442c5e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{43fff568: PendingIntentRecord{4448a158 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1449627494735, Int=0
D/PMS     (  908): releaseWL(43fe5cb0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl( 3931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3931): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 3931): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  908): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 3931): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 3931): turnOffMobile bCheckMobileData = false
D/LocationManagerService(  908): getProviders()=[gps, network]
,D/LocationManagerService(  908): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  908): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 3931): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 3931): isCharging status = 5
D/PMS     (  908): releaseWL(442c5e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 3931): turnOffWifi ui setting = false
,D/PMS     (  908): acquireWL(43b65668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b65668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43ed6750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1052983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43ed6750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4417d870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4417d870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42a382b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1112983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42a382b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(438f0840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(438f0840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/PMS     (  908): acquireWL(43b81270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4218d558: PendingIntentRecord{42898b60 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=779872, Int=0
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3975 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{425c5d10: PendingIntentRecord{423af5d0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449626697186, Int=10800000
,V/AlarmManager(  908): sending alarm PendingIntent{4213c278: PendingIntentRecord{42b12618 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449627382917, Int=1800000
,V/AlarmManager(  908): sending alarm PendingIntent{42a69ff0: PendingIntentRecord{42848d28 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449627417628, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{429edf68: PendingIntentRecord{42a3eee0 com.google.android.gms startService}}, i=com.google.android.gms.icing.INDEX_RECURRING_MAINTENANCE, t=0, cnt=1, w=1449627648014, Int=86400000
,D/PMS     (  908): acquireWL(42a38b90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): acquireWL(445d61d8): PARTIAL_WAKE_LOCK  Icing 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1956): Performing maintenance.
,D/PowerUsageService( 3931): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3931): MY_DEBUG = false
D/PMS     (  908): acquireWL(44548c60): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(43b81270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  908): releaseWL(42a38b90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (3975/10049)
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,I/EventLogService( 1956): Aggregate from 1449625582768 (log), 1449625582768 (data)
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,I/Icing   ( 1956): updateResources: need to parse f{com.google.android.gms}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360022774
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023334
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023500
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023503
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023506
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027565
,D/PMS     (  908): releaseWL(44548c60): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1956): Performing maintenance usage 2092845 budget 4122869654 free 99.949% index free 99.911% purge? false target 1642946445
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): releaseWL(445d61d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  908): killProcessQuiet, pid=3714
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3714:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3714
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(433d5f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1172983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(433d5f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(440d54e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(440d54e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(433d45d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1232984, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(433d45d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3526): [NET] getaddrinfo-,err=8
D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3526): [NET] getaddrinfo-, 1
,D/libc    ( 3526): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  357): [NET] get_iface_protocol fail: 
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  357): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  357): [NET] getaddrinfo-,err=7
,D/libc    ( 3526): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(44498f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44498f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4349c2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1292983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4349c2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43fad2f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43fad2f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4310ba80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1352983, Int=0
I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4310ba80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4447d740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4447d740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42a26ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1412983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42a26ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43eddfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/PMS     (  908): releaseWL(43eddfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(44078078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1472983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44078078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4349b358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4349b358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43c5ba98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1532983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43c5ba98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3526): [NET] getaddrinfo-,err=8
D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3526): [NET] getaddrinfo-, 1
,D/libc    ( 3526): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  357): [NET] get_iface_protocol fail: 
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  357): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  357): [NET] getaddrinfo-,err=7
,D/libc    ( 3526): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(42e83598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  908): n_update end
D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(42e83598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4443a6a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/PMS     (  908): releaseWL(4443a6a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(439d66a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1592983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(439d66a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44473700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44473700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(44050a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(44050a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(44051550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1652983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44051550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4456f108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/BatteryService(  908): n_update end
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(4456f108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43565098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43565098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(44013a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1712983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44013a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(444327e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(444327e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4417f118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(4417f118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1107): closing low battery warning: level=100
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(44489d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1772983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44489d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(443d2fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(443d2fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(42773788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(42773788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
I/ProcessStatsService(  908): Prepared write state in 38ms
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2015-12-08-10-20-00.bin
,D/PMS     (  908): acquireWL(42a66cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1832983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42a66cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3526): [NET] getaddrinfo-,err=8
D/libc    ( 3526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3526): [NET] getaddrinfo-, 1
,D/libc    ( 3526): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  357): [NET] get_iface_protocol fail: 
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  357): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  357): [NET] getaddrinfo-,err=7
,D/libc    ( 3526): [NET] getaddrinfo_proxy-
,D/PMS     (  908): acquireWL(439adeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(439adeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(445ae680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(445ae680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/Process (  908): killProcessQuiet, pid=3492
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
,D/Process (  908): killProcessQuiet, pid=3783
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
I/ActivityManager(  908): Killing 3492:com.google.android.apps.plus/u0a160 (adj 15): empty for 1807s
I/ActivityManager(  908): Killing 3783:com.htc.providers.settings:remote/u0a17 (adj 15): empty for 1807s
,I/ActivityManager(  908): Killing 3731:com.htc.cs.dm/u0a98 (adj 15): empty for 1807s
D/Process (  908): killProcessQuiet, pid=3731
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/Process (  908): killProcessQuiet, pid=3766
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/Process (  908): killProcessQuiet, pid=3744
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  908): Killing 3766:com.htc.backup/1000 (adj 15): empty for 1807s
I/ActivityManager(  908): Killing 3744:com.google.android.apps.docs/u0a100 (adj 15): empty for 1807s
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3783
I/ActivityManager(  908): Recipient 3731
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3766
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3744
I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3492
,D/PMS     (  908): acquireWL(440cefc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42457ad0: PendingIntentRecord{429db5e0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820555, Int=1800000
D/PMS     (  908): acquireWL(43b128a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
,V/AlarmManager(  908): sending alarm PendingIntent{42a0abd8: PendingIntentRecord{42a0ab80 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1849787, Int=0
V/AlarmManager(  908): sending alarm PendingIntent{43cccc78: PendingIntentRecord{43cdd088 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1859658, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{4218d558: PendingIntentRecord{42898b60 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1881018, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{42a69ff0: PendingIntentRecord{42848d28 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449628317628, Int=900000
,D/PMS     (  908): releaseWL(43b128a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/LocationManagerService(  908): getAllProviders()=[passive, gps, network]
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,W/ContextImpl( 3931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1956/10029)
,I/ActivityManager(  908): Resuming delayed broadcast
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  908): releaseWL(440cefc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/libc    ( 1329): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1329): [NET] getaddrinfo-,err=8
D/libc    ( 1329): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 1329): [NET] getaddrinfo-, 1
D/libc    ( 1329): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  357): [NET] get_iface_protocol fail: 
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  357): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  357): [NET] getaddrinfo-,err=7
,D/libc    ( 1329): [NET] getaddrinfo_proxy-
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(429c56e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{427b1f98: PendingIntentRecord{4278c018 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1892983, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(429c56e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4023): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4023): ====startRecUseTime====
D/htc.customization.log.level( 4023):  is 
W/CustomizationLogLevel( 4023): Level value is invalid, use default level 2
D/CustomizationManager( 4023):  Read ACC file spent 0.122 (s)
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4023): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4023): Parsing tag category name = system
I/CustomizationCIDLoader( 4023): Parsing tag category name = application
I/CustomizationCIDLoader( 4023): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4023): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4023): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4023): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4023): Parsing tag category name = Settings
D/CustomizationManager( 4023):  Read CID file spent 0.179 (s)
D/CustomizationManager( 4023):  All configurations done spent 0.179 (s)
W/HtcNativeFlag( 4023): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4023): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4023): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4023): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4023, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  908): killProcessQuiet, pid=3857
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
D/Process (  908): killProcessQuiet, pid=3828
I/ActivityManager(  908): Killing 3857:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
I/ActivityManager(  908): Killing 3828:com.htc.mms.backupagent/u0a78 (adj 15): empty for 1814s
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
W/asset   (  908): Copying FileAsset 0x6f7e5da8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3828
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  908): Skipping PackageSetting{425b35c0 com.example.hello/10396} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1196): Ignoring removeGeofence because network location is disabled.
D/PMS     (  908): acquireWL(43a3eb40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1273): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1319): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
D/PMS     (  908): releaseWL(43a3eb40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/Launcher( 1246): Deferring update until onResume
D/Launcher( 1246): waitUntilResume // bindAppsRemoved
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/[PluginManager]RegisterService( 1299): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1299): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/Prism.PackageStateRece_( 1246): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
W/AccTypeManager( 1319): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1319): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/IcingCorporaProvider( 2556): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4038 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/ExternalAccountType( 1319): Unsupported attribute readOnly
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
D/PhoneApp( 1214): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  908): acquireWL(43c52a70): PARTIAL_WAKE_LOCK  Icing 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2556): UpdateCorporaTask done [took 399 ms] updated apps [took 398 ms] 
E/SQLiteDatabase( 4038): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4038): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4038): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4038): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4038): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4038): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4038): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4038): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4038): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4038): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4038): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4038): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4038): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4038): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4038): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4038): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4038): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4038): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4038): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4038): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4038): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4038): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4038): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4038): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4038): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4038): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4038): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4038): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4038): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4038): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4038): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4038): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4038): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4038): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4038): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4038): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4038): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4038): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4038): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4038): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4038): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4038): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4038): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4038): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4038): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4038): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4038): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4038): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4038): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4038): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4038): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4038): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4038): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4038): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4038): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4038): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4038): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4038): threadid=11: thread exiting with uncaught exception (group=0x41af2e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4038): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4038): Process: com.google.android.apps.docs, PID: 4038
E/AndroidRuntime( 4038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4038): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4038): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4038): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4038): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4038): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
E/SQLiteDatabase( 4038): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4038): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4038): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4038): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4038): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4038): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4038): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4038): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4038): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4038): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4038): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4038): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4038): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4038): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4038): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4038): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4038): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4038): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4038): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4038): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4038): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4038): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4038): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4038): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4038): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4038): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4038): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4038): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4038): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4038): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4038): killProcess, pid=4038
D/Process ( 4038): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4056 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Recipient 4038
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4038) has died.
I/TrimMemoryManager( 1246): [trimMemory] 5
W/ContextImpl( 4056): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4056): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4056): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4056): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4056): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4056): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4056): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4056): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4056): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4056): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4056): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4056): threadid=10: thread exiting with uncaught exception (group=0x41af2e30)
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4069 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4056): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4056): Process: com.android.keychain, PID: 4056
E/AndroidRuntime( 4056): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4056): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4056): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4056): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4056): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4056): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4056): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4056): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4056): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4069): getInstance(Context context)
D/AppTag  ( 4069): getInstance(Context context)
D/AppTag  ( 4069): onCreate()
I/ActivityManager(  908): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4084 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/Process ( 4056): killProcess, pid=4056
D/Process ( 4056): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449628402127.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  908): 	... 4 more
I/ActivityManager(  908): Recipient 4056
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.android.keychain (pid 4056) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41fb4db0 +
I/Prism.WidgetManager( 1246): onLoadItems() +
I/Icing   ( 1956): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
E/Icing   ( 1956): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1956): Could not init tag ds.tag.deleted
I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1956): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1956): Clearing selected account for com.test.thalitest
D/PMS     (  908): acquireWL(4417c3d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4084 10160 null
E/SQLiteDatabase( 4084): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4084): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4084): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4084): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4084): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4084): 	at del.a(PG:264)
E/SQLiteDatabase( 4084): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4084): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  908): releaseWL(4417c3d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
D/Process (  908): killProcessQuiet, pid=3526
E/SQLiteDatabase( 4084): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4084): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4084): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4084): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4084): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4084): 	at del.a(PG:264)
E/SQLiteDatabase( 4084): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4084): 	at java.lang.Thread.run(Thread.java:864)
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3526:com.android.vending/u0a74 (adj 15): empty for 1814s
E/EsApplication( 4084): Failed app initialization
E/EsApplication( 4084): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4084): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4084): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4084): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4084): 	at del.a(PG:264)
E/EsApplication( 4084): 	at eeq.run(PG:187)
E/EsApplication( 4084): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  908): Delay finish: com.google.android.gms/.photos.autobackup.PhotosAppUninstalledReceiver
I/LocationSettingsChecker( 1956): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  908): Recipient 3526
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageManager(  908): Unable to load service info ResolveInfo{44412ea8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
I/Icing   ( 1956): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
D/PMS     (  908): releaseWL(43c52a70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
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
W/SQLiteOpenHelper( 1956): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1956): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1956): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
W/SQLiteOpenHelper( 1956): Opened phenotype.db in read-only mode
E/SQLiteLog( 1956): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1956): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1

```
