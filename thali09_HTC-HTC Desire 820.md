#### Test 57132760f6ec045_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  912): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4065 uid=10078 gids={50078}
D/PMS     (  912): acquireWL(423c1588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10078}
V/AlarmManager(  912): sending alarm PendingIntent{4245fc08: PendingIntentRecord{42473500 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453758156203, Int=60000
D/PMS     (  912): releaseWL(423c1588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
--------- beginning of /dev/log/main
D/SMSBackup( 4065): SMSBackupAgentService started
D/SMSBackup( 4065): Checking restore status
D/SMSBackup( 4065): Restore complete
D/SMSBackup( 4065): cancelCheckAlarm
D/SMSBackup( 4065): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  912): killProcessQuiet, pid=3857
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025382
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025534
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025606
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025609
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025613
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026973
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026987
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029974
I/ActivityManager(  912): Killing 3857:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Recipient 3857
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  912): Client connection lost with reason: 4
,E/cutils-trace( 4078): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4078): ====startRecUseTime====
D/htc.customization.log.level( 4078):  is 
W/CustomizationLogLevel( 4078): Level value is invalid, use default level 2
D/CustomizationManager( 4078):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4078): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4078): Parsing tag category name = system
I/CustomizationCIDLoader( 4078): Parsing tag category name = application
I/CustomizationCIDLoader( 4078): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4078): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4078): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4078): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4078): Parsing tag category name = Settings
D/CustomizationManager( 4078):  Read CID file spent 0.098 (s)
D/CustomizationManager( 4078):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 4078): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4078): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4078): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4078): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  912): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  912): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  912): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4078
D/PMS     (  912): acquireHCC(442263e8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 912 1000 null
D/PMS     (  912): acquireHCC(42341c50): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 912 1000 null
W/asset   (  912): Copying FileAsset 0x6251ff10 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  912): @test_code: getHtcIntentFlag: 0 obj: 1111361840
D/PMS     (  912): acquireWL(42625838): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 912 1000 null
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c95710
I/SocialFeedProvider( 1250): +onPause
I/SocialFeedProvider( 1250): -onPause
I/ActivityManager(  912): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4089 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4089): Copying FileAsset 0x5c7b0428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1250): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4089): Binding Chromium to main looper Looper (main, tid 1) {41b36420}
I/LibraryLoader( 4089): Expected native library version number "",actual native library version number ""
I/chromium( 4089): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4089): Initializing chromium process, renderers=0
D/PMS     (  912): acquireWL(423338f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): acquireWL(42697170): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): releaseWL(423338f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41e5bcd0:true
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4089): 1102364248: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 4089): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4089): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4089): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4089): Local Branch: 
I/Adreno-EGL( 4089): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4089): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4089):                  aa63bbd948f41d15fc72f585e
W/chromium( 4089): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4089): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4089): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4089): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4089): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4089): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4089): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4089): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4089): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4089): CordovaWebView is running on device made by: HTC
,W/AwContents( 4089): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  912): Disable input method client, pid=1250
,W/ResourceType( 4089): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4089): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b7d3e0, mServedView=org.apache.cordova.engine.SystemWebView{41b43170 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4089): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  912): Displayed com.test.thalitest/.MainActivity: +293ms
W/XT9_C   ( 1187): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1187): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  912): Enable input method client, pid=4089
D/PMS     (  912): releaseWL(42625838): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4089): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4089): JniHelper::setJavaVM(0x41607048), pthread_self() = 1664083504
,I/chromium( 4089): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 11.998MB for 63974-byte allocation
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 12.036MB for 95956-byte allocation
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 12.111MB for 143930-byte allocation
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 12.225MB for 215890-byte allocation
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 12.400MB for 323830-byte allocation
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 13.076MB for 728606-byte allocation
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 13.673MB for 1092904-byte allocation
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 14.594MB for 1639352-byte allocation
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 15.838MB for 2459024-byte allocation
,I/dalvikvm-heap( 4089): Grow heap (frag case) to 18.023MB for 3688532-byte allocation
,W/CpuWake (  912): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  912): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  912): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  912): <<release mCpuPerf_Freq wakelock
D/PMS     (  912): releaseHCC(442263e8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  912): releaseHCC(42341c50): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4089): Initializing JXcore engine
,W/jxcore-log( 4089): JXcore engine is ready
,W/jxcore-log( 4089): Starting JXcore engine
,W/jxcore-log( 4089): Platform android
W/jxcore-log( 4089): 
,W/jxcore-log( 4089): Process ARCH arm
W/jxcore-log( 4089): 
,I/jxcore-log( 4089): JXcore Cordova bridge is ready!
I/jxcore-log( 4089): 
,W/jxcore-log( 4089): JXcore engine is started
,E/jxcore  ( 4089): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4089): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4089): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  912): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  912): acquireWL(422179a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 912 1000 null
W/PluginManager( 4089): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,I/FeedHostManager( 1250): [onResume]
,I/FeedProviderManager( 1250): onResume
,I/SocialFeedProvider( 1250): +onResume
I/ConnectivityHelper( 1250): [getCurrentConnectionType] no network connection
,I/SocialFeedProvider( 1250): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1250): -onResume
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.launcher (1250/10076)
,I/InputMethodManagerService(  912): Disable input method client, pid=4089
,W/IInputConnectionWrapper( 4089): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  912): Enable input method client, pid=1250
,D/PMS     (  912): releaseWL(422179a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  912): killProcessQuiet, pid=3770
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  912): Killing 3770:com.google.android.talk/u0a111 (adj 15): empty #17
,E/libEGL  ( 4089): call to OpenGL ES API with no current context (logged once per thread)
,V/LightsService(  912): setLight #0: color=#24
,V/LightsService(  912): setLight #0: color=#21
,I/ActivityManager(  912): Recipient 3770
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/LightsService(  912): setLight #0: color=#1a
,V/LightsService(  912): setLight #0: color=#14
,D/PMS     (  912): releaseWL(42697170): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  912): mEventCount = 900
,I/PMS     (  912): Going to sleep due to screen timeout...
,W/PMS     (  912): mWirelessDisplayManager is null
,D/WirelessDisplayService(  912): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  912): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422803b8
,W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = CM36282 Light sensor
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422803b8, eanble = 0, strlen(mName) = 59
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  912): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420d3530
W/SensorService(  912): Listener[1] = com.htc.smartdim.sensor_eye@42b1b6e8
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  912): Couldn't get kernel wake lock stats
V/LightsService(  912): setLight #2: color=#0
D/qdlights(  912): set_light_buttons_func: on=0 brightness=0
V/LightsService(  912): setLight #0: color=#0
,D/SurfaceControl(  912): Excessive delay in blankDisplay() while turning screen off: 318ms
D/PMS     (  912): nativeSetInteractive:false
D/PMS     (  912): nativeSetInteractive:false done
D/PMS     (  912): nativeSetAutoSuspend:true
D/PMS     (  912): nativeSetAutoSuspend:true done
D/HABCtrl (  912): TPE algorithm. remove timeout.
I/InputManager(  912): Cancel all due to getting PMS screen off broadcast
D/PMS     (  912): OOBE c monitor 11
,I/InputMethodManagerService(  912): screenObserver, isScreenOn=false
D/NfcService( 1236): ScreenObserver: OFF
,D/NfcService( 1236): applyRouting - 0
V/KeyguardServiceDelegate(  912): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426609f0)
I/IntentController( 1110): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false),
,D/NfcService( 1236): applyRouting -2
I/InputMethodManagerService(  912): Disable input method client, pid=1250
D/PMS     (  912): acquireWL(42ee5b00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1236 1027 null
D/PMN     (  912): wakingUp
,D/PMS     (  912): releaseWL(42ee5b00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  912): **** SHOWN CALLED ****
D/PMS     (  912): acquireWL(43725d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/WindowManager(  912): No lock screen! windowToken=null
I/BatteryService(  912): n_update end
D/PMS     (  912): releaseWL(43725d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  912): onScreenOn
,D/MtpService( 2039): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1236): applyRouting - 0
,D/MtpService( 2039): [MTP][onReceive]-
,D/NfcService( 1236): applyRouting -2
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/AutoSetting( 1305): receiver - intent: android.intent.action.USER_PRESENT
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WirelessDisplayService(  912): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  912): acquireWL(432a0d00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1236 1027 null
D/PMS     (  912): releaseWL(432a0d00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/TetherSettings( 3423): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3423): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3423): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3423): Cust_ConnectToPC   : spcsc>false
D/        ( 3423): Cust_ConnectToPC   : IPT>true
D/        ( 3423): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3423): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3423): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3423): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3423): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1305): service - onCreate()
D/AlarmManager(  912): ACTION_SCREEN_ON
I/AlarmManager(  912): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done recovering
I/AlarmManager(  912): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done EPS screen off alarm recovering
,I/PSReceiver( 3423): onReceive:android.intent.action.USER_PRESENT
,I/ClockThread( 1110): stop update clock
,D/AutoSetting( 1305): service - AddressCache: using context: com.htc.Weather
I/SmartNS_PSService( 3423): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3423): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3423):  defaultType:0
W/ContextImpl( 3423): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1305): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  912): request 420469b0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  912): provider request: passive ProviderRequest[ON interval=0]
D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_ON
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  912):    returned false
,V/SRS_Proc(  371): ParamSet string: screen_state=on
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/ActivityManager(  912): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4146 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/NetworkPolicy(  912): updateScreenOn: false
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  912): acquireWL(44359550): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(44359550): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  912): acquireWL(4366ef88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/TetherSettings( 3423): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3423): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3423): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3423): Cust_ConnectToPC   : spcsc>false
D/        ( 3423): Cust_ConnectToPC   : IPT>true
,D/        ( 3423): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3423): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3423): Index of the first 1 = -1
W/ContextImpl( 3423): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  912): releaseWL(4366ef88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3423): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3423): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3423): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3423): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420d3530
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420d3530, eanble = 0, strlen(mName) = 91
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  912): Listener[0] = com.htc.smartdim.sensor_eye@42b1b6e8
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartNS_Utility( 3423): [ACC]android_networking:tethering_guard_support=false
D/PMN     (  912): goingToSleep
W/ActivityManager(  912): Disable JIT of com.htc.bgp
,I/ActivityManager(  912): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4161 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/PMS     (  912): acquireWL(4364bf20): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 912 1000 null
,I/FeedHostManager( 1250): [onPause]
,I/FeedProviderManager( 1250): onPause
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c95710
I/SocialFeedProvider( 1250): +onPause
,I/SocialFeedProvider( 1250): -onPause
D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=21645 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 0
D/AlarmManager(  912): ACTION_SCREEN_OFF
I/AlarmManager(  912): [AlarmQueuing] screen off now: 
I/AlarmManager(  912): [AlarmQueuing] data connection: true
I/AlarmManager(  912): [AlarmQueuing] wifi connection: false
,D/PMS     (  912): acquireWL(438ed010): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 912 1000 null
,D/WifiNative-wlan0(  912):    returned false
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  912): releaseWL(438ed010): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  912): releaseWL(4364bf20): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/ContactMessageStore( 1222): start background delete task...
D/ContactMessageStore( 1222): size: 0 , 0
,D/ContactMessageStore( 1222): Background delete complete
D/NetworkPolicy(  912): updateScreenOn: false
,I/CalendarProvider2( 4161): Created com.android.providers.calendar.CalendarAlarmManager@41b66c60(com.android.providers.calendar.HtcCalendarProvider@41b4efe8)
,D/CalendarProvider2( 4161): wait start:true
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] getTotalRam: 1873 Mb
,D/CalendarProvider2( 4161): wait end:false
D/PMS     (  912): acquireWL(442e63c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(442e63c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42ef5440): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  912): releaseWL(42ef5440): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1305): service - mHandler: cancel location update
,D/AutoSetting( 1305): service -           changes count: 0
,D/SmartSyncUtils( 4146): isEpsOn(), nState = 0
D/PMS     (  912): acquireWL(43e846d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4146 1000 null
,D/SmartSyncUtils( 4146): getMobilePolicyEnabled, result = true
D/PMS     (  912): releaseWL(43e846d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4146): isEpsOn(), nState = 0
D/SmartSyncUtils( 4146): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4146): isEpsOn(), nState = 0
D/WifiService(  912): New client listening to asynchronous messages
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42b1b6e8
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 1
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42b1b6e8, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 0
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42b1b6e8, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42b1b6e8
E/ActivityThread(  912): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42a4dcd0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42a4dcd0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  912): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  912): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  912): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  912): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  912): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  912): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  912): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 4161): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4161): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 4031): ---------------------------------------------------
,D/ProviderChangeReceiver( 4031): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4031): start to updateAlertNotification!
,W/ContextImpl( 4045): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 4031): No fired or scheduled alerts
,D/HtcAlertUtils( 4031): -- cancelReminderNotification --
,D/HtcAlertUtils( 4031): broadcastExistReminder!
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  912): killProcessQuiet, pid=3891
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3891:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3891
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1222): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1222): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  912): killProcessQuiet, pid=3498
,I/ActivityManager(  912): Killing 3498:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 3498
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(42c8eb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=122211, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42c8eb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{4431d178 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  912): acquireWL(43e53820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): releaseWL(43e53820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(43ed51c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{41bf1460: PendingIntentRecord{442ed448 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140258, Int=0
,D/PMS     (  912): releaseWL(43ed51c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1305): service - handleMessage() stop self
,D/AutoSetting( 1305): service - handleMessage() quit looper
,D/AutoSetting( 1305): service - onDestroy() END
,D/Process (  912): killProcessQuiet, pid=3926
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3926:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3926
,D/PMS     (  912): acquireWL(4391a908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{432474c8: PendingIntentRecord{43e4cb00 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126693, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{424b0980: PendingIntentRecord{42445f58 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=143081, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{42458950: PendingIntentRecord{41d885e8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=144515, Int=0
,D/PMS     (  912): acquireWL(4429fe30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2362/10029)
,D/PMS     (  912): releaseWL(4429fe30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  912): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  912): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  912): acquireWL(435bedf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(435bedf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
,D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  912): [NET] getaddrinfo_proxy-
D/PMS     (  912): releaseWL(4391a908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(438dbd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(438dbd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1222): switchBindHtcMsgCursor: null
,D/PMS     (  912): acquireWL(43baa6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=182210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43baa6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43abe230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43abe230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(4433fd80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{424d8b90: PendingIntentRecord{43e4cb00 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186515, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{42458950: PendingIntentRecord{41d885e8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=204736, Int=0
,D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
D/PMS     (  912): releaseWL(4433fd80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  912): acquireWL(43e47808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2362/10029)
D/libc    (  912): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(4399a580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(43e47808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(4399a580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43780af0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025382
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025534
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025600
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025606
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025609
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025613
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026973
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026987
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029974
,D/PMS     (  912): releaseWL(43780af0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43489e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2362/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025382
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025534
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025606
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025609
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025613
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026973
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026987
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029974
,D/PMS     (  912): acquireWL(42723380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1201): Vacuum at: now=1453758262916 tag=VacuumService
D/PMS     (  912): releaseWL(43489e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42723380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43b2acf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025382
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025534
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025600
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025606
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025609
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025613
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026973
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026987
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029974
,D/PMS     (  912): releaseWL(43b2acf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43b460b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2362 10029 WorkSource{10029 com.google.android.gms},
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2362/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025382
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025534
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025600
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025606
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025609
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025613
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026973
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026987
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029974
,D/PMS     (  912): releaseWL(43b460b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  912): acquireWL(42a890c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=242210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42a890c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(42a78368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42a78368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(441f8c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=302210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(441f8c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(445edfa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(445edfa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  912): killProcessQuiet, pid=3802
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3802:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3802
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(43ebbb68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=362210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43ebbb68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3704): [NET] getaddrinfo-,err=8
D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3704): [NET] getaddrinfo-, 1
,D/libc    ( 3704): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3704): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(438ec198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(438ec198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(443310a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=422210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(443310a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42ea6ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42ea6ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(4376f2a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=482210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4376f2a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42c8a8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c8a8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(43847a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): releaseWL(43847a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(42e47aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=542211, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42e47aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43cbb590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43cbb590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42f0bd20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=602210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42f0bd20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(431dc188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
I/BatteryService(  912): n_update end
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(431dc188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1222): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1222): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1222): sku_id=99
D/ContactMessageStore( 1222): start background delete task...
,D/ContactMessageStore( 1222): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1222): size: 0 , 0
,D/ContactMessageStore( 1222): Background delete complete
,D/PMS     (  912): acquireWL(43ec8278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43ec8278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(424e5ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=662210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(424e5ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3704): [NET] getaddrinfo-,err=8
D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3704): [NET] getaddrinfo-, 1
D/libc    ( 3704): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3704): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(43798d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43798d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42661060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=722210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42661060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(436a8d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  912): releaseWL(436a8d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42b580c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=782211, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42b580c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42646860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42646860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42426d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=842210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42426d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43d188d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43d188d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(43d4eda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=902210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43d4eda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(438db7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  912): releaseWL(438db7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(4312d350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=962210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4312d350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3704): [NET] getaddrinfo-,err=8
,D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3704): [NET] getaddrinfo-, 1
,D/libc    ( 3704): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3704): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(442d9ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(442d9ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
,D/PowerUI ( 1110): closing low battery warning: level=100
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(442054e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,D/ConnectivityService(  912): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  912): sending alarm PendingIntent{41d75680: PendingIntentRecord{424c30f8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786804, Int=0
,D/ConnectivityService(  912): Done.
,D/ConnectivityService(  912): Setting timer for 720seconds
,I/ActivityManager(  912): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4215 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  912): sending alarm PendingIntent{42e2c888: PendingIntentRecord{44204d50 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,I/ActivityManager(  912): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4227 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  912): sending alarm PendingIntent{42540ce0: PendingIntentRecord{42513e58 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453758271851, Int=10800000
,D/Finsky  ( 3704): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  912): sending alarm PendingIntent{4254f0d0: PendingIntentRecord{43f46208 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453758747776, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{426d98e0: PendingIntentRecord{4265f3a0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453758992170, Int=900000
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (3704/10074)
,V/AlarmManager(  912): sending alarm PendingIntent{41e86aa0: PendingIntentRecord{429ff5c8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453759068113, Int=0
,W/ContextImpl( 4146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4146): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4146): MY_DEBUG = false
,D/SmartSyncUtils( 4146): isEpsOn(), nState = 0
,D/PMS     (  912): acquireWL(43d6fb80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4146 1000 null
,D/PMS     (  912): releaseWL(442054e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4146): [updateNmRange] bManual = false
I/ImageRamCache( 4215): create image Cache, size: 31457280.
I/ImageRamCache( 4215): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 4215): create image Cache, size: 12582912.
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SmartSyncScreenOnOffTimeReceiver( 4146): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
I/FeedSettings( 4215): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4215): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4215): GroupBudget 60 45 15
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.aurora (4227/10049)
,W/BatSI   (  912): Couldn't get kernel wake lock stats
D/SmartSyncScreenOnOffTimeReceiver( 4146): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4146): SettingOnTime = 1453788000000, randomSettingOnTime = 1453785353000
D/SmartSyncScreenOnOffTimeReceiver( 4146): SettingOffTime = 1453773600000, randomSettingOffTime = 1453778588000
V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SmartSyncScreenOnOffTimeReceiver( 4146): bDayMode = false
I/Prism.ExternalStringMa_( 4215): changeLocale(): en_GB
D/SmartSyncScreenOnOffTimeReceiver( 4146): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4146): bNightModeTurnOffOnce = false
I/Prism.AllAppsOptionsMa_( 4215): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4215): loadGridSize() with Alternative
D/PMS     (  912): releaseWL(43d6fb80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/libc    ( 3704): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3704): [NET] getaddrinfo-,err=8
D/libc    ( 3704): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3704): [NET] getaddrinfo-, 1
,D/libc    ( 3704): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3704): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3704): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (3704/10074)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (3704/10074)
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3704): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3704): [NET] getaddrinfo-,err=8
D/libc    ( 3704): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3704): [NET] getaddrinfo-, 1
,D/libc    ( 3704): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3704): [NET] getaddrinfo_proxy-
D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (3704/10074)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (3704/10074)
,D/libc    ( 4215): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4215): [NET] getaddrinfo-,err=8
D/libc    ( 4215): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4215): [NET] getaddrinfo-, 1
,D/libc    ( 4215): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 4215): [NET] getaddrinfo_proxy-
,E/[CSBICLIENT][v9][BiLogUploadService]( 4215): Exception on getConfig()
,W/BatSI   (  912): Couldn't get kernel wake lock stats
V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3704): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3704): [NET] getaddrinfo-,err=8
D/libc    ( 3704): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3704): [NET] getaddrinfo-, 1
,D/libc    ( 3704): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3704): [NET] getaddrinfo_proxy-
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (3704/10074)
W/Finsky  ( 3704): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/Process (  912): killProcessQuiet, pid=3971
,I/ActivityManager(  912): Killing 3971:com.htc.backup/1000 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 3971
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (3704/10074)
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3704): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3704): [NET] getaddrinfo-,err=8
D/libc    ( 3704): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3704): [NET] getaddrinfo-, 1
,D/libc    ( 3704): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3704): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3704): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (3704/10074)
,D/Finsky  ( 3704): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  912): acquireWL(42512f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10074}
,V/AlarmManager(  912): sending alarm PendingIntent{41eaa980: PendingIntentRecord{4256f640 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1453759069276, Int=0
,D/Finsky  ( 3704): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/WearableService( 1201): callingUid 10029, callindPid: 1201
,D/DeviceConnectionService( 1201): client connected with version: 8296000
D/PMS     (  912): acquireWL(43868ec8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3704 10074 null
D/PMS     (  912): releaseWL(42512f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (3704/10074)
D/Finsky  ( 3704): [402] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3704): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
D/Finsky  ( 3704): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 3704): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3704): [NET] getaddrinfo-,err=8
D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3704): [NET] getaddrinfo-, 1
,D/libc    ( 3704): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3704): [NET] getaddrinfo_proxy-
D/PMS     (  912): releaseWL(43868ec8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/Process (  912): killProcessQuiet, pid=3988
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3988:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3988
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(43c6a210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43c6a210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42abce48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1022210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42abce48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(44227b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10074}
,V/AlarmManager(  912): sending alarm PendingIntent{43a41838: PendingIntentRecord{4322b380 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453759083473, Int=0
,D/PMS     (  912): releaseWL(44227b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3704): [386] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3704): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PMS     (  912): acquireWL(437674d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(437674d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
,I/HtcPowerSaver(  912): >> updateStatus
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(437fbba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(437fbba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42e5df08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1082210, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42e5df08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43853e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43853e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(43edbe60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1142211, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1250): Grow heap (frag case) to 12.666MB for 50416-byte allocation
,D/PMS     (  912): releaseWL(43edbe60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43ac6ce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43ac6ce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(44245878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1202211, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(44245878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42efa9a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42efa9a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  912): acquireWL(426f1210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41b44810: PendingIntentRecord{420445b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1262211, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(426f1210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3704): [NET] getaddrinfo-,err=8
D/libc    ( 3704): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3704): [NET] getaddrinfo-, 1
,D/libc    ( 3704): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3704): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(42e41720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42e41720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4258): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4258): ====startRecUseTime====
D/htc.customization.log.level( 4258):  is 
W/CustomizationLogLevel( 4258): Level value is invalid, use default level 2
D/CustomizationManager( 4258):  Read ACC file spent 0.107 (s)
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4258): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4258): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4258): Parsing tag category name = system
I/CustomizationCIDLoader( 4258): Parsing tag category name = application
I/CustomizationCIDLoader( 4258): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4258): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4258): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4258): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4258): Parsing tag category name = Settings
D/CustomizationManager( 4258):  Read CID file spent 0.164 (s)
D/CustomizationManager( 4258):  All configurations done spent 0.164 (s)
W/HtcNativeFlag( 4258): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4258): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4258): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4258): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  912): deletePackageAsUser: pkg=com.test.thalitest, pid=4258, uid=2000 user=0
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  912): killProcessQuiet, pid=4089
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  912): Killing 4089:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
W/asset   (  912): Copying FileAsset 0x6215bd80 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  912): Skipping PackageSetting{42285fd8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1526): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1526): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1526): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  912): acquireWL(438ea9d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1201): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 4215): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4215): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1322): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  912): releaseWL(438ea9d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1250): Deferring update until onResume
D/Launcher( 1250): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1279): Cleaning up data for package: com.test.thalitest
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
W/AccTypeManager( 1322): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1322): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
W/SystemReader( 1236): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/[PluginManager]RegisterService( 1305): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1305): handle notify Blinkfeed plugin client changed
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
D/Prism.PackageStateRece_( 1250): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
E/ExternalAccountType( 1322): Unsupported attribute readOnly
I/IcingCorporaProvider( 2668): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/ActivityManager(  912): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4277 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/InputMethodManagerService(  912): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PhoneApp( 1222): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  912): acquireWL(42313ac0): PARTIAL_WAKE_LOCK  Icing 0x1 1975 10029 WorkSource{10029 com.google.android.gms}
E/SQLiteLog( 2668): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2668): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5cab4d08
E/IcingCorporaProvider( 2668): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2668): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2668): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2668): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2668): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2668): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2668): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2668): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2668): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2668): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2668): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2668): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2668): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2668): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2668): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2668): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2668): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2668): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2668): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2668): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2668): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2668): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2668): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2668): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2668): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2668): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2668): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2668): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2668): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2668): 	... 15 more
W/IcingCorporaProvider( 2668): notifyTableChanged failed.
W/IcingCorporaProvider( 2668): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2668): UpdateCorporaTask done [took 240 ms] updated apps [took 240 ms] 
D/PMS     (  912): releaseWL(42313ac0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/SQLiteDatabase( 4277): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4277): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4277): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4277): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4277): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4277): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4277): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4277): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4277): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4277): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4277): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4277): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4277): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4277): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4277): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4277): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4277): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4277): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4277): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4277): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4277): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4277): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4277): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4277): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4277): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4277): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4277): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4277): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4277): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4277): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4277): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4277): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4277): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4277): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4277): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4277): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4277): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4277): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4277): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4277): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4277): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4277): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4277): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4277): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4277): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4277): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4277): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4277): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4277): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4277): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4277): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4277): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4277): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4277): threadid=11: thread exiting with uncaught exception (group=0x416ffe30)
E/ActivityManager(  912): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4277): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4277): Process: com.google.android.apps.docs, PID: 4277
E/AndroidRuntime( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4277): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4277): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4277): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4277): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4277): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
I/ActivityManager(  912): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4296 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4277): killProcess, pid=4277
D/Process ( 4277): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  912): Recipient 4277
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.google.android.apps.docs (pid 4277) has died.
W/ContextImpl( 4296): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  912): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4309 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4296): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4296): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4296): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4296): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4296): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4296): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4296): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4296): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4296): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4296): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4296): threadid=10: thread exiting with uncaught exception (group=0x416ffe30)
E/AndroidRuntime( 4296): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4296): Process: com.android.keychain, PID: 4296
E/AndroidRuntime( 4296): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4296): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4296): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4296): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4296): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4296): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4296): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4296): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4296): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  912): App crashed! Process: com.android.keychain
D/ErrorReport(  912): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 4215): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4215): loadItems() com.htc.launcher.pageview.WidgetManager@41b99870 +
I/Prism.WidgetManager( 4215): onLoadItems() +
D/AppTag  ( 4309): getInstance(Context context)
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41bc1e10 +
I/Prism.WidgetManager( 1250): onLoadItems() +
D/Process ( 4296): killProcess, pid=4296
D/Process ( 4296): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  912): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  912): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453759370121.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  912): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  912): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  912): 	... 4 more
D/AppTag  ( 4309): getInstance(Context context)
D/AppTag  ( 4309): onCreate()
I/ActivityManager(  912): Recipient 4296
I/ActivityManager(  912): Process com.android.keychain (pid 4296) has died.
W/ActivityManager(  912): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  912): acquireWL(43205840): PARTIAL_WAKE_LOCK  AsyncService 0x1 3681 10160 null
W/PackageManager(  912): Unable to load service info ResolveInfo{4337de50 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  912): releaseWL(43205840): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 3704): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1975): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1975): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1975): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1975): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1975): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  912): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 1975): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1975): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d667d10
W/dalvikvm( 1975): threadid=26: thread exiting with uncaught exception (group=0x416ffe30)
E/AndroidRuntime( 1975): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1975): Process: com.google.android.gms, PID: 1975
E/AndroidRuntime( 1975): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1975): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1975): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1975): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1975): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1975): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1975): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1975): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1975): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1975): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1975): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1975): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1975): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1975): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1975): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1975): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1975): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1975): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1975): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 1975): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1975): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1975): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1975): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1975): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1975): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  912): App crashed! Process: com.google.android.gms
E/PhenotypeInitializer( 1975): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1975): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 1975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 1975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1975): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1975): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1975): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 1975): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 1975): killProcess, pid=1975
D/Process ( 1975): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
I/ActivityManager(  912): Recipient 1975
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.google.android.gms (pid 1975) has died.
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
I/ActivityManager(  912): Resuming delayed broadcast
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10992ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10991ms

```
