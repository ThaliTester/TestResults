#### Test 568182548138a64_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,E/cutils-trace( 6331): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6331): ====startRecUseTime====
D/htc.customization.log.level( 6331):  is 
W/CustomizationLogLevel( 6331): Level value is invalid, use default level 2
D/CustomizationManager( 6331):  Read ACC file spent 0.032 (s)
D/CIDMapFileReader( 6331): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6331): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6331): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6331): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6331): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6331): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6331): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6331): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6331): Parsing tag category name = system
I/CustomizationCIDLoader( 6331): Parsing tag category name = application
I/CustomizationCIDLoader( 6331): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6331): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6331): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6331): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6331): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6331): add string-array item, value = 42507
I/CustomizationCIDLoader( 6331): add string-array item, value = 21902
I/CustomizationCIDLoader( 6331): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6331): add string-array item, value = 23420
I/CustomizationCIDLoader( 6331): add string-array item, value = 22299
I/CustomizationCIDLoader( 6331): add string-array item, value = 24002
I/CustomizationCIDLoader( 6331): add string-array item, value = 23210
I/CustomizationCIDLoader( 6331): add string-array item, value = 23205
I/CustomizationCIDLoader( 6331): add string-array item, value = 23806
I/CustomizationCIDLoader( 6331): add string-array item, value = 23430
I/CustomizationCIDLoader( 6331): add string-array item, value = 23408
I/CustomizationCIDLoader( 6331): add string-array item, value = 27205
I/CustomizationCIDLoader( 6331): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6331): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6331):  Read CID file spent 0.067 (s)
D/CustomizationManager( 6331):  All configurations done spent 0.067 (s)
--------- beginning of system
I/ActivityManager(  947): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6331 on display 0
D/PMS     (  947): acquireHCC(349acf66): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 947 1000 null
D/PMS     (  947): acquireHCC(1fff92a7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 947 1000 null
I/ActivityManager(  947): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6349 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  947): Display changed displayId=0
D/DotMatrix( 1336): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1336): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1629): [trimMemory] 20
I/WebViewFactory( 6349): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6349): Time to load native libraries: 9 ms (timestamps 1455-1464),
,I/LibraryLoader( 6349): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6349): Binding Chromium to main looper Looper (main, tid 1) {29c4b6aa}
,I/LibraryLoader( 6349): Expected native library version number "",actual native library version number ""
,I/chromium( 6349): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6349): Initializing chromium process, singleProcess=true
W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6349): ApplicationContext is null in ApplicationStatus
,W/chromium( 6349): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6349): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6349): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6349): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6349): Local Branch: 
I/Adreno-EGL( 6349): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6349): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6349):                  d74aa161a12b9c6fc6332151
,W/System.err(  947): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  947): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@245c26bb:true
W/System.err(  947): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  947): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  947): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  947): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6349): 118461302: getState(). Returning 12,
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6349): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6349): CordovaWebView is running on device made by: HTC
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  947): Activity pause timeout for ActivityRecord{12aa8354 u0 com.test.thalitest/.MainActivity t8},
W/HtcSystemUPManager(  947): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/chromium( 6349): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  947): Explicit concurrent mark sweep GC freed 44850(2MB) AllocSpace objects, 3(924KB) LOS objects, 33% free, 16MB/25MB, paused 1.572ms total 139.344ms
,D/StatusBarManagerService(  947): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  947): hiding MENU key
,D/StatusBarManagerService(  947): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  947): hiding MENU key,
,D/FindExtension( 6349): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6349): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@11353814, mServedView=org.apache.cordova.engine.SystemWebView{3e3728bd VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@b141eb2
,I/PhoneStatusBar( 1224): setImeWindowStatus(false,false)
,I/InputMethodManagerService(  947): Disable input method client, pid=1629
D/StatusBarManagerService(  947): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6349): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  947): Displayed com.test.thalitest/.MainActivity: +785ms (total +829ms)
,W/BindingManager( 6349): Cannot call determinedVisibility() - never saw a connection for the pid: 6349
,D/JsMessageQueue( 6349): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6349): JniHelper::setJavaVM(0xab5118f8), pthread_self() = -1400606456
,I/chromium( 6349): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  947): releaseHCC(349acf66): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  947): releaseHCC(1fff92a7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6349): Initializing JXcore engine
W/jxcore-log( 6349): JXcore engine is ready
,W/jxcore-log( 6349): Starting JXcore engine
,W/jxcore-log( 6349): Platform android
W/jxcore-log( 6349): 
W/jxcore-log( 6349): Process ARCH arm
W/jxcore-log( 6349): 
,I/jxcore-log( 6349): JXcore Cordova bridge is ready!
I/jxcore-log( 6349): 
W/jxcore-log( 6349): JXcore engine is started
,E/jxcore  ( 6349): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6349): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6349): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  947): Killing 6081:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=6081
,D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  947): Recipient 6081
,W/PluginManager( 6349): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 231ms. Plugin should use CordovaInterface.getThreadPool().
,D/PMS     (  947): acquireWL(13723bb4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  947): n_update end
D/HeadsetStateMachine( 3045): Disconnected process message: 10, size: 0
D/PMS     (  947): releaseWL(13723bb4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PowerUI ( 1224): closing low battery warning: level=97
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: E msg.what=155652
D/HtcPowerSaver(  947): updateBatteryInfo
D/WifiController(  947): processMsg: DeviceActiveState
D/PMS     (  947): runPSCheck
D/WifiController(  947): processMsg: StaEnabledState
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): processMsg: DefaultState
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): handleMessage: X
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1336): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
I/HtcPowerSaver(  947): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1224): status:2 level:97 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(370c73dd): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{1000},
,D/PMS     (  947): acquireWL(3588db52): PARTIAL_WAKE_LOCK  *backup* 0x1 947 1000 null
V/AlarmManager(  947): sending alarm PendingIntent{31848e23: PendingIntentRecord{ad15f20 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453416043365, Int=0
,V/AlarmManager(  947): sending alarm PendingIntent{18e170d9: PendingIntentRecord{29355a9e com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143552, Int=0,
,D/PMS     (  947): releaseWL(370c73dd): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/BackupManagerService(  947): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  947): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  947): releaseWL(3588db52): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  947): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  947): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
D/PMS     (  947): acquireWL(187e97f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 947 1000 null,
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  947): [NET] android_getaddrinfofornet-, err=8
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  947): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  947): [NET] android_getaddrinfo_proxy+
D/libc    (  947): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  947): [NET] android_getaddrinfo_proxy-, success
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  947): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  947): [reportHTCStatus] eventMask = 3 , status = 0
D/PMS     (  947): acquireWL(283b9e9b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 947 1000 null
,D/GpsLocationProvider(  947): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  947): releaseWL(187e97f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  947):  [handleDownloadXtraData]inject done.
D/PMS     (  947): releaseWL(283b9e9b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  947): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1570): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  947): acquireWL(1297f238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(1297f238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  947): plugged=true pluggin=true,
,I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1224): closing low battery warning: level=98
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PMS     (  947): runPSCheck
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1336): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): updateStatus (8000,98,-1,false,false,false,-1)
D/WifiController(  947): processMsg: DeviceActiveState
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/HeadsetStateMachine( 3045): Disconnected process message: 10, size: 0
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1224): status:2 level:98 unsupport:false plugged:true
,D/HtcUPManager( 1224): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1224): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1538): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@24a7540d
,D/Process (  947): killProcessQuiet, pid=6106
I/ActivityManager(  947): Killing 6106:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 6106
,D/PMS     (  947): acquireWL(5cf6211): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000},
V/AlarmManager(  947): sending alarm PendingIntent{225149a7: PendingIntentRecord{3f376e54 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=154172, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{13541f76: PendingIntentRecord{27ab8977 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=213344, Int=0,
V/AlarmManager(  947): sending alarm PendingIntent{30f5f9e4: PendingIntentRecord{35370e4d com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186653, Int=0
,D/PMS     (  947): acquireWL(b5abd02): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(5cf6211): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1224): Weather sync is On
W/WeatherTimeKeeper( 1224): [refreshWeatherData] no weather data
,D/PMS     (  947): acquireWL(2cc54613): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(b5abd02): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  947): releaseWL(2cc54613): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(3a24ba05): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(3a24ba05): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(172eea5a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(172eea5a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(5fd648b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(10085968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(10e15226): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): releaseWL(5fd648b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1839): Vacuum at: now=1453416119556 tag=VacuumService,
,D/PMS     (  947): releaseWL(10085968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(13bda414): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1839): Using platform SSLCertificateSocketFactory
,W/Uploader( 1839): No account for auth token provided
,D/PMS     (  947): releaseWL(13bda414): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(2b3524bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(2b3524bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1839): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1839): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1839): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1839): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1839): [NET] android_getaddrinfo_proxy+
D/libc    ( 1839): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1839): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1839): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1839): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1839): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1839): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1839): No account for auth token provided
,W/Uploader( 1839):  no longer exists, so no auth token.
,W/Uploader( 1839): No account for auth token provided
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1839): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1839): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1839): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1839): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1839): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1839): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1839): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1839): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1839): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1839): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1839): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1839): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1839): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1336): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1336): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1224): reapply : com.google.android.gms 4 40
,W/Uploader( 1839): No account for auth token provided
,D/PMS     (  947): releaseWL(10e15226): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(2d3890d6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(2d3890d6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  947): acquireWL(18bb0f57): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(18bb0f57): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1329): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1329): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1329): wlan0: BSS: Remove id 1 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1329): wlan0: BSS: Remove id 4 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 a0:c5:62:7a:49:97]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 a0:c5:62:7a:49:97
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  947): acquireWL(3a9c3a44): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
D/UsbnetService(  947): BroadcastReceiver::onReceive+
I/BatteryService(  947): n_update end
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PMS     (  947): releaseWL(3a9c3a44): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): updateBatteryInfo
I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  947): plugged=true pluggin=true
D/WifiController(  947): handleMessage: E msg.what=155652
D/PMS     (  947): runPSCheck
D/WifiController(  947): processMsg: DeviceActiveState
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): processMsg: StaEnabledState
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): battery changed pluggedType: 2
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1336): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WifiController(  947): handleMessage: X
,D/PowerUI ( 1224): closing low battery warning: level=98
D/HeadsetStateMachine( 3045): Disconnected process message: 10, size: 0
,D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  947): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1224): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  947): acquireWL(22ddb72d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000}
V/AlarmManager(  947): sending alarm PendingIntent{225149a7: PendingIntentRecord{3f376e54 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=214173, Int=0
,V/AlarmManager(  947): sending alarm PendingIntent{57749f3: PendingIntentRecord{1144b6b0 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453416265132, Int=0
,D/PMS     (  947): releaseWL(22ddb72d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1224): Weather sync is On
W/WeatherTimeKeeper( 1224): [refreshWeatherData] no weather data
,D/PMS     (  947): acquireWL(60b9929): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{1000}
,V/AlarmManager(  947): sending alarm PendingIntent{3a50e4ae: PendingIntentRecord{6b2924f android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=369366, Int=0
D/PMS     (  947): acquireWL(3ab68ddc): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 947 1000 null
,D/PMS     (  947): acquireWL(331b9ee5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 947 1000 null
,D/PMS     (  947): releaseWL(60b9929): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  947): releaseWL(3ab68ddc): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null,
,D/PMS     (  947): releaseWL(331b9ee5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1839): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1839): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1839): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1839): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1839): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1839): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1839): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1336): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1336): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5639): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5639): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5639): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5639): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5639): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
,E/PlayEventLogger( 5639): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5639): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1224): reapply : com.google.android.gms 3 40
,W/System  ( 5639): Ignoring header User-Agent because its value was null.,
D/libc    ( 5639): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5639): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5639): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5639): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5639): [NET] android_getaddrinfo_proxy+
D/libc    ( 5639): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5639): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  947): acquireWL(2382ad3f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(2382ad3f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PowerUI ( 1224): closing low battery warning: level=99
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1336): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): handleMessage: E msg.what=155652
I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  947): battery changed pluggedType: 2
D/HeadsetStateMachine( 3045): Disconnected process message: 10, size: 0
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: X
,I/HtcPowerSaver(  947): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1224): status:2 level:99 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  947): acquireWL(2d27260c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
D/DotMatrix( 1336): [EventService] reorderNotification, total:0
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(2d27260c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1336): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  947): plugged=true pluggin=true
D/HeadsetStateMachine( 3045): Disconnected process message: 10, size: 0
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive-
W/ContextImpl( 6268): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
D/WifiController(  947): handleMessage: E msg.what=155652
D/PowerUI ( 1224): closing low battery warning: level=100
D/WifiController(  947): processMsg: DeviceActiveState,
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): processMsg: StaEnabledState
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): processMsg: DefaultState
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): handleMessage: X
D/HeadsetPhoneState( 3045): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3045): Disconnected process message: 11, size: 0
,D/TetherSettings( 5998): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5998): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5998): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5998): Cust_ConnectToPC   : spcsc>false
D/        ( 5998): Cust_ConnectToPC   : IPT>true
D/        ( 5998): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 5998): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 5998): Index of the first 1 = -1
,I/BatteryController( 1224): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 5998): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 5998): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 ,
,W/Settings( 5998): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SmartNS_Utility( 5998): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5998): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5998): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5998): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5998): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1570): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1570): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1570): sku_id=118
D/ContactMessageStore( 1570): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1570): start background delete task...
,D/ContactMessageStore( 1570): size: 0 , 0
,D/ContactMessageStore( 1570): Background delete complete
,D/PMS     (  947): acquireWL(1165e96a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(1165e96a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  947): updateBatteryInfo
,I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PowerUI ( 1224): closing low battery warning: level=100
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): >> updateStatus
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1336): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
D/HeadsetStateMachine( 3045): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1224): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(277ede5b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
,D/PMS     (  947): releaseWL(277ede5b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): >> updateStatus
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1336): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3045): Disconnected process message: 10, size: 0
,I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): handleMessage: E msg.what=155652,
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1224): closing low battery warning: level=100
D/WifiController(  947): processMsg: DefaultState
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1224): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(e2696f8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000},
V/AlarmManager(  947): sending alarm PendingIntent{225149a7: PendingIntentRecord{3f376e54 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=394172, Int=0
,V/AlarmManager(  947): sending alarm PendingIntent{43e07d1: PendingIntentRecord{11713236 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941786, Int=0,
,I/bt-btm  ( 3045): Received oneshot timer event complete
I/bt-btm  ( 3045): btm_ble_timeout
I/bt-btm  ( 3045): btm_gen_resolvable_private_addr
,D/PMS     (  947): acquireWL(36430537): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3045 1002 null
,D/PMS     (  947): releaseWL(e2696f8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/bt-btm  ( 3045): btm_ble_rand_enc_complete
I/bt-btm  ( 3045): btm_gen_resolve_paddr_low
D/bt-smp  ( 3045): smp_encrypt_data,
W/bt-smp  ( 3045): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3045): Plain text(LSB ~ MSB) = b9 c4 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3045): Encrypted text(LSB ~ MSB) = 09 de b8 10 74 85 84 f3 e9 0f b3 2c 6d 6a cc bd 
I/bt-btm  ( 3045): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3045): Stopping oneshot timer
D/bt-btm  ( 3045): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1224): Weather sync is On,
W/WeatherTimeKeeper( 1224): [refreshWeatherData] no weather data
,D/PMS     (  947): releaseWL(36430537): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  947): acquireWL(5aa2aa4): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{10024}
V/AlarmManager(  947): sending alarm PendingIntent{214a500d: PendingIntentRecord{8163bc2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=973437, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{275798b9: PendingIntentRecord{8ea94fe android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806050, Int=0,
,D/PMS     (  947): acquireWL(31b8bdd3): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(31b8bdd3): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  947): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6422 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  947): sending alarm PendingIntent{19b14d10: PendingIntentRecord{2058e009 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453416792230, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{2a10520e: PendingIntentRecord{3e91c85a com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453416868532, Int=0
,W/ContextImpl( 6268): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  947): releaseWL(5aa2aa4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6268): MY_DEBUG = false
,D/PowerUsageService( 6268): repeat time = 1453417779329
,I/art     (  441): Explicit concurrent mark sweep GC freed 8656(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 427us total 34.266ms
,I/art     (  441): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 340us total 20.134ms
,I/art     (  441): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 325us total 20.921ms,
,D/StatusBarManagerService(  947): setSystemUiVisibility(0x700),
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  947): hiding MENU key
,D/StatusBarManagerService(  947): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  947): hiding MENU key,
,D/FindExtension( 1629): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
I/ThreadedRenderer( 1629): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  947): Disable input method client, pid=6349
D/StatusBarManagerService(  947): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6349): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6349): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6349): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1224): setImeWindowStatus(false,false),
,I/PowerUsageList:PowerUsageHelper( 6268): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6268): gen(), null == sipper.uidObj, userId = 0,
,E/cutils-trace( 6445): Error opening trace file: Permission denied (13),
I/dex2oat ( 6445): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6445): dex2oat: override thread count:4
,D/PMS     (  947): acquireWL(31a673c5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1839): Message class com.google.f.a.a.i
,D/PMS     (  947): releaseWL(31a673c5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/dex2oat ( 6445): dex2oat took 610.704ms (threads: 4)
,I/PushClient( 6422): ApplicationMonitor {14a08de4}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6422): ApplicationMonitor {14a08de4}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6422): ApplicationMonitor {14a08de4}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6422): ApplicationMonitor {14a08de4}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6422): ApplicationMonitor {14a08de4}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6422): ApplicationMonitor {14a08de4}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6422): ApplicationMonitor {14a08de4}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6422): ApplicationMonitor {14a08de4}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6422): ApplicationMonitor {14a08de4}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6422): PnsModel {3d3ed77}: update(): Update registration caused by: alarm,
,I/PushClient( 6422): PnsConfigModel {3fd01e5a}: <init>(): Use dm-client for provisioning.
,W/System.err( 6422): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6422): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6422): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6422): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  947): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6453 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6453): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6453 dbg=false s=true
,I/DeviceManagement( 6453): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6453): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6453): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6453): WorkflowService: Starting workflow service
,I/DeviceManagement( 6453): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3d3ed77] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6453): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88],
,I/DeviceManagement( 6453): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6453): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6453): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6453): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6453): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6453): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6453): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3d3ed77],
,I/DeviceManagement( 6453): WorkflowService: Stopping workflow service,
,D/Process (  947): killProcessQuiet, pid=6132
I/ActivityManager(  947): Killing 6132:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6422): PnsModel {3d3ed77}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  947): Recipient 6132
,D/Process (  947): killProcessQuiet, pid=4667
,I/ActivityManager(  947): Killing 4667:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 4667
,D/PMS     (  947): acquireWL(187cdd79): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
D/UsbnetService(  947): BroadcastReceiver::onReceive+
I/BatteryService(  947): n_update end
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PMS     (  947): releaseWL(187cdd79): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/NotificationService(  947): plugged=true pluggin=true
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2,
,D/WifiController(  947): processMsg: DeviceActiveState
D/PowerUI ( 1224): closing low battery warning: level=100
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  947): processMsg: DefaultState
D/HtcPowerSaver(  947): updateBatteryInfo
,D/WifiController(  947): handleMessage: X
D/PMS     (  947): runPSCheck
I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  947): Checking...
D/HeadsetStateMachine( 3045): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  947): >> updateStatus
,D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): << updateStatus
D/DotMatrix( 1336): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1224): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(3d3b5abe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000}
,V/AlarmManager(  947): sending alarm PendingIntent{225149a7: PendingIntentRecord{3f376e54 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=994173, Int=0
,V/AlarmManager(  947): sending alarm PendingIntent{14dfb71f: PendingIntentRecord{e069a6c com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453416919512, Int=0
,D/SmartSyncUtils( 6268): isEpsOn(), nState = 0
,D/PMS     (  947): acquireWL(1764d835): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6268 1000 null
,D/PMS     (  947): releaseWL(3d3b5abe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6268): [updateNmRange] bManual = false
,D/WeatherUtility( 1224): Weather sync is On
W/WeatherTimeKeeper( 1224): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 6268): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6268): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6268): SettingOnTime = 1453442400000, randomSettingOnTime = 1453440322000
D/SmartSyncScreenOnOffTimeReceiver( 6268): SettingOffTime = 1453420800000, randomSettingOffTime = 1453423387000
D/SmartSyncScreenOnOffTimeReceiver( 6268): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6268): bNightMode = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6268): bNightModeTurnOffOnce = false
,D/PMS     (  947): releaseWL(1764d835): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  947): acquireWL(1dce64ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
,I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(1dce64ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  947): updateBatteryInfo
,D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1224): closing low battery warning: level=100
D/DotMatrix( 1336): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1336): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3045): Disconnected process message: 10, size: 0
,D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PMS     (  947): runPSCheck
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1224): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  947): User[0] Flushing usage stats to disk
,I/FeedHostManager( 1629): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) },
D/PMS     (  947): acquireWL(11d2a63b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000}
V/AlarmManager(  947): sending alarm PendingIntent{225149a7: PendingIntentRecord{3f376e54 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1054173, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{11f8f158: PendingIntentRecord{297c2b1 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1453417200000, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{1dd60396: PendingIntentRecord{53b6b17 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.reminders.REFRESH_NOTIFICATION, t=0, cnt=1, w=1453417200000, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{3fb7cb04: PendingIntentRecord{2a34d8ed com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_UPDATE_GOLDEN_TABLE, t=0, cnt=1, w=1453417200000, Int=0
D/PMS     (  947): acquireWL(6e6c322): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1629 10074 null
D/PMS     (  947): releaseWL(6e6c322): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/PMS     (  947): acquireWL(39689370): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4304 10024 null
,D/WeatherUtility( 1224): Weather sync is On
W/WeatherTimeKeeper( 1224): [refreshWeatherData] no weather data
,D/PMS     (  947): releaseWL(11d2a63b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/PMS     (  947): acquireWL(71316e9): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6268 1000 null
,D/PMS     (  947): acquireWL(3551ef6e): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4304 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(39689370): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  947): releaseWL(3551ef6e): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,D/ContactMessageStore( 1570): notify MmsSms
,D/AccFlag ( 1570): sense_version=6.0
D/AccFlag ( 1570): sku_id=118
,D/TelephUtils( 1570): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 55
,D/AccFlag ( 1570): sku_id=118
,D/TelephUtils( 1570): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 69
D/AccFlag ( 1570): sku_id=118
,D/TelephUtils( 1570): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 97
D/AccFlag ( 1570): sku_id=118
,D/TelephUtils( 1570): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 54,
D/AccFlag ( 1570): sku_id=118
,D/PMS     (  947): acquireWL(1bb5942b): PARTIAL_WAKE_LOCK  Icing 0x1 4304 10024 WorkSource{10024 com.google.android.gms},
,D/TelephUtils( 1570): QUERY for  <hidden uri>  [ com.android.phone ] tid: 61
,D/PMS     (  947): releaseWL(1bb5942b): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(5adba21): PARTIAL_WAKE_LOCK  Icing 0x1 4304 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  947): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=6485 uid=10035 gids={50035, 9997} abi=arm64-v8a,
,D/SMSBackup( 6212): Got a database change event,
,I/Icing   ( 4304): Indexing 45DF604A3178D15E8C0610E8DC9A22B2315E4983 from com.google.android.gms,
,I/Icing   ( 4304): Indexing done 45DF604A3178D15E8C0610E8DC9A22B2315E4983
,D/PMS     (  947): releaseWL(5adba21): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  947): killProcessQuiet, pid=6161
,I/ActivityManager(  947): Killing 6161:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 6161
,D/PMS     (  947): releaseWL(71316e9): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,TIME-OUT KILL (timeout was 1200000ms)
```
