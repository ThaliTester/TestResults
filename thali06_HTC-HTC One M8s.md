#### Test 52383621d5a0cb8_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,E/cutils-trace( 7106): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7106): ====startRecUseTime====
D/htc.customization.log.level( 7106):  is 
W/CustomizationLogLevel( 7106): Level value is invalid, use default level 2
D/CustomizationManager( 7106):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 7106): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7106): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7106): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7106): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7106): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7106): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7106): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7106): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7106): Parsing tag category name = system
I/CustomizationCIDLoader( 7106): Parsing tag category name = application
I/CustomizationCIDLoader( 7106): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7106): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7106): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7106): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7106): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7106): add string-array item, value = 42507
I/CustomizationCIDLoader( 7106): add string-array item, value = 21902
I/CustomizationCIDLoader( 7106): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7106): add string-array item, value = 23420
I/CustomizationCIDLoader( 7106): add string-array item, value = 22299
I/CustomizationCIDLoader( 7106): add string-array item, value = 24002
I/CustomizationCIDLoader( 7106): add string-array item, value = 23210
I/CustomizationCIDLoader( 7106): add string-array item, value = 23205
I/CustomizationCIDLoader( 7106): add string-array item, value = 23806
I/CustomizationCIDLoader( 7106): add string-array item, value = 23430
I/CustomizationCIDLoader( 7106): add string-array item, value = 23408
I/CustomizationCIDLoader( 7106): add string-array item, value = 27205
I/CustomizationCIDLoader( 7106): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7106): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7106):  Read CID file spent 0.100 (s)
D/CustomizationManager( 7106):  All configurations done spent 0.100 (s)
--------- beginning of system
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7106 on display 0
D/PMS     (  970): acquireHCC(3642ea29): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
D/PMS     (  970): acquireHCC(28c61ae): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
W/asset   (  970): Copying FileAsset 0x55bb3ae1c0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  970): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7124 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  970): Display changed displayId=0
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 7124): Copying FileAsset 0xac5b10e0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1512): [trimMemory] 20
I/WebViewFactory( 7124): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 7124): Time to load native libraries: 9 ms (timestamps 1718-1727)
I/LibraryLoader( 7124): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7124): Binding Chromium to main looper Looper (main, tid 1) {15d4ed1}
I/LibraryLoader( 7124): Expected native library version number "",actual native library version number ""
I/chromium( 7124): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7124): Initializing chromium process, singleProcess=true
W/art     ( 7124): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7124): ApplicationContext is null in ApplicationStatus
W/chromium( 7124): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7124): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7124): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7124): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7124): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7124): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7124): Local Branch: 
I/Adreno-EGL( 7124): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7124): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7124):                  d74aa161a12b9c6fc6332151
W/System.err(  970): java.lang.Throwable: stack dump
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2020d547:true
W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 7124): 513214221: getState(). Returning 12
W/art     ( 7124): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7124): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7124): CordovaWebView is running on device made by: HTC
W/art     ( 7124): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7124): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7124): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/StatusBarManagerService(  970): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/FindExtension( 7124): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 7124): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@f6b90c3, mServedView=org.apache.cordova.engine.SystemWebView{10ba3d40 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3d75c479
I/InputMethodManagerService(  970): Disable input method client, pid=1512
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 7124): reportFullscreenMode on inactive InputConnection
I/ActivityManager(  970): Displayed com.test.thalitest/.MainActivity: +633ms (total +677ms)
W/BindingManager( 7124): Cannot call determinedVisibility() - never saw a connection for the pid: 7124
D/JsMessageQueue( 7124): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7124): JniHelper::setJavaVM(0xab4458f8), pthread_self() = -1401371720
D/JX-Cordova( 7124): jxcore cordova android initializing
,W/jxcore-log( 7124): Initializing JXcore engine
W/jxcore-log( 7124): JXcore engine is ready
,W/jxcore-log( 7124): Starting JXcore engine,
,W/jxcore-log( 7124): Platform android
W/jxcore-log( 7124): 
W/jxcore-log( 7124): Process ARCH arm
W/jxcore-log( 7124): 
,D/PMS     (  970): releaseHCC(3642ea29): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  970): releaseHCC(28c61ae): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/Process (  970): killProcessQuiet, pid=5997
I/ActivityManager(  970): Killing 5997:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5997
,I/jxcore-log( 7124): JXcore Cordova bridge is ready!,
I/jxcore-log( 7124): 
W/jxcore-log( 7124): JXcore engine is started
,I/Choreographer( 7124): Skipped 96 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7124): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 7124): Error!: Cannot find module '../server-address.js',
E/jxcore  ( 7124): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 7124): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37),
,D/Process (  970): killProcessQuiet, pid=6604
I/ActivityManager(  970): Killing 6604:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  970): Recipient 6604
,W/PluginManager( 7124): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 247ms. Plugin should use CordovaInterface.getThreadPool().
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  970): acquireWL(35c21d2f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 970 1000 null
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233392e),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  970): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/PMS     (  970): acquireWL(15dd5d4b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{2d5f8c1e: PendingIntentRecord{2b93fcff android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=139596, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{34afc328: PendingIntentRecord{153c7841 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=146546, Int=0,
,D/PMS     (  970): releaseWL(15dd5d4b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/GpsLocationProvider(  970): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  970): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  970):  [handleDownloadXtraData]inject done.
,D/PMS     (  970): acquireWL(3aa931e6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null,
D/PMS     (  970): releaseWL(35c21d2f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
D/PMS     (  970): releaseWL(3aa931e6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1447): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1447): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  970): acquireWL(5228327): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
,V/AlarmManager(  970): sending alarm PendingIntent{ad1e9d4: PendingIntentRecord{3e97577d android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1449056550518, Int=0
D/PMS     (  970): acquireWL(2ac68672): PARTIAL_WAKE_LOCK  *backup* 0x1 970 1000 null
,D/PMS     (  970): releaseWL(5228327): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  970): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  970): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  970): releaseWL(2ac68672): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  970): acquireWL(21aa2ac3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): releaseWL(21aa2ac3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus,
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  970): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  970): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1447): switchBindHtcMsgCursor: null
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1590): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1c9734fb
,D/Process (  970): killProcessQuiet, pid=6845
I/ActivityManager(  970): Killing 6845:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6845
,D/PMS     (  970): acquireWL(44dcf40): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{2d5f8c1e: PendingIntentRecord{2b93fcff android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199596, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{15c6ee79: PendingIntentRecord{cf297be android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=213178, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{87ab01f: PendingIntentRecord{14e09f6c com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=194723, Int=0
,D/PMS     (  970): acquireWL(dbef935): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(44dcf40): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  970): acquireWL(3e3c71ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(dbef935): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  970): releaseWL(3e3c71ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1d2d7004): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1d2d7004): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(2b9219ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2b9219ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(b697022): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(185b4ab3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(278367e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(b697022): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1924): Vacuum at: now=1449056593893 tag=VacuumService
,I/GoogleURLConnFactory( 1924): Using platform SSLCertificateSocketFactory
,D/PMS     (  970): releaseWL(185b4ab3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(28b5df0f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(28b5df0f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1400bb9c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1400bb9c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1924): No account for auth token provided
,D/libc    ( 1924): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1924): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1924): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1924): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1924): [NET] android_getaddrinfo_proxy+
D/libc    ( 1924): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1924): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1924): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1924): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1924): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1924): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1924): No account for auth token provided,
,W/Uploader( 1924): No account for auth token provided,
,W/Uploader( 1924):  no longer exists, so no auth token.,
,W/Uploader( 1924): No account for auth token provided
,I/GLSUser ( 1924): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1924): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1924): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1924): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1924): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1924): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1924): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1924): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1924): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 2 40,
,I/GLSUser ( 1924): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1924): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1924): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1924): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1924): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1924): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1924): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
,E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1924): ,	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1924): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,W/Uploader( 1924): No account for auth token provided,
,I/GLSUser ( 1924): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1924): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1924): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1924): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1924): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1924): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1924): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1924): ,	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1924): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 4 40
,D/PMS     (  970): releaseWL(278367e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(1a6712cd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(1a6712cd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(3d2ba782): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3d2ba782): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  970): acquireWL(292c1e93): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(292c1e93): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  970): updateBatteryInfo
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
,D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): << updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1379): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
,D/wpa_supplicant( 1379): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
,D/PMS     (  970): acquireWL(31cbfed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/BatteryService(  970): n_update end
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): releaseWL(31cbfed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): updateBatteryInfo
D/WifiController(  970): handleMessage: E msg.what=155652
D/NotificationService(  970): plugged=true pluggin=true
D/WifiController(  970): processMsg: DeviceActiveState
D/PMS     (  970): runPSCheck
D/WifiController(  970): processMsg: StaEnabledState
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: X
D/WifiController(  970): battery changed pluggedType: 2
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  970): acquireWL(5f0ec9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{2d5f8c1e: PendingIntentRecord{2b93fcff android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259596, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{16f010ef: PendingIntentRecord{313a37fc com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1449056724099, Int=0
,D/PMS     (  970): releaseWL(5f0ec9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  970): acquireWL(3bc0ce85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3bc0ce85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
,D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1924): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1924): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1924): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1924): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 4 40
W/GLSActivity( 1924): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1924): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1924): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1924): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1924): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1924): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1924): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6369): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6369): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6369): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6369): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6369): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6369): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6369): 	at android.os.Binder.execTransact(Binder.java:454)
,I/art     ( 1924): Background sticky concurrent mark sweep GC freed 40100(2MB) AllocSpace objects, 16(1236KB) LOS objects, 42% free, 4MB/8MB, paused 5.391ms total 74.741ms,
,W/System  ( 6369): Ignoring header User-Agent because its value was null.,
,D/libc    ( 6369): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6369): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6369): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6369): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6369): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6369): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6369): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  970): acquireWL(3ded13df): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end,
D/PMS     (  970): releaseWL(3ded13df): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): updateBatteryInfo
,D/NotificationService(  970): plugged=true pluggin=true
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  970): acquireWL(1779982c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(1779982c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  970): acquireWL(292b62f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(292b62f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1447): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1447): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1447): sku_id=118
,D/ContactMessageStore( 1447): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1447): start background delete task...
,D/ContactMessageStore( 1447): size: 0 , 0
,D/ContactMessageStore( 1447): Background delete complete
,D/PMS     (  970): acquireWL(3e1df88a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end,
D/PMS     (  970): releaseWL(3e1df88a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(19390efb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(19390efb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(30fe0b18): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
I/bt-btm  ( 3329): Received oneshot timer event complete
V/AlarmManager(  970): sending alarm PendingIntent{2d5f8c1e: PendingIntentRecord{2b93fcff android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379596, Int=0
I/bt-btm  ( 3329): btm_ble_timeout
V/AlarmManager(  970): sending alarm PendingIntent{301c3971: PendingIntentRecord{33eb1356 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=944041, Int=0
I/bt-btm  ( 3329): btm_gen_resolvable_private_addr
,D/PMS     (  970): acquireWL(57f9fd7): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3329 1002 null
,D/bt-btm  ( 3329): btm_ble_rand_enc_complete,
D/PMS     (  970): releaseWL(30fe0b18): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
I/bt-btm  ( 3329): btm_gen_resolve_paddr_low
D/bt-smp  ( 3329): smp_encrypt_data
W/bt-smp  ( 3329): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3329): Plain text(LSB ~ MSB) = 98 5f 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3329): Encrypted text(LSB ~ MSB) = cf 29 7c 16 9d 06 d5 d2 ba 6a 2d 5d 5d 55 60 98 
I/bt-btm  ( 3329): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3329): Stopping oneshot timer
,D/bt-btm  ( 3329): Starting oneshot timer type:103 timeout:900s
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  970): releaseWL(57f9fd7): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  970): acquireWL(3154c0c4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3154c0c4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0,
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(2f69fbad): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024},
V/AlarmManager(  970): sending alarm PendingIntent{f9d0ee2: PendingIntentRecord{25346273 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=938109, Int=0
,I/ActivityManager(  970): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7190 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,V/AlarmManager(  970): sending alarm PendingIntent{253f2530: PendingIntentRecord{c57a5a9 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1449057107179, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{262bf71e: PendingIntentRecord{25378bff android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805659, Int=0
D/PMS     (  970): acquireWL(3f81372e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3f81372e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=7207 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,V/AlarmManager(  970): sending alarm PendingIntent{468b2cf: PendingIntentRecord{2229645c com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
V/AlarmManager(  970): sending alarm PendingIntent{235bf365: PendingIntentRecord{3abe797f com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449057351523, Int=0
,W/ContextImpl( 7021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  970): releaseWL(2f69fbad): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 7021): MY_DEBUG = false
,D/PMS     (  970): acquireWL(34e7aceb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1924 10024 WorkSource{10024 com.google.android.gms},
D/PowerUsageService( 7021): repeat time = 1449058251616
,D/PMS     (  970): acquireWL(279d60e1): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,I/GCM     ( 4675): Message from null null,
E/GCM     ( 4675): Dropping message from null
,D/PMS     (  970): releaseWL(279d60e1): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms}
,D/StatusBarManagerService(  970): setSystemUiVisibility(0x700),
,D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
D/StatusBarManagerService(  970): hiding MENU key
D/FindExtension( 1512): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/ThreadedRenderer( 1512): Defer allocateBuffers to drawing time
D/StatusBarManagerService(  970): hiding MENU key
,I/InputMethodManagerService(  970): Disable input method client, pid=7124
,D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
D/GCM     ( 1924): Message class com.google.f.a.a.i
W/IInputConnectionWrapper( 7124): Do restartInputUnchecked, ic=null
I/InputMethodManager( 7124): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
,W/IInputConnectionWrapper( 7124): reportFullscreenMode on inactive InputConnection
,D/PMS     (  970): releaseWL(34e7aceb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,I/ImageRamCache( 7207): create image Cache, size: 31457280.,
,I/ImageRamCache( 7207): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 7207): create image Cache, size: 31457280.
,I/FeedSettings( 7207): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
I/FeedSettings( 7207): GroupBudget 0.500000 0.380000
I/FeedSettings( 7207): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 7207): changeLocale(): en_GB,
E/cutils-trace( 7239): Error opening trace file: Permission denied (13)
I/dex2oat ( 7239): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7239): dex2oat: override thread count:4
,I/Prism.AllAppsOptionsMa_( 7207): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 7207): loadGridSize() with Alternative
,I/PowerUsageList:PowerUsageHelper( 7021): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 7021): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 7021): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 7021): gen(), null == sipper.uidObj, userId = 0
,D/libc    ( 7207): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4,
D/libc    ( 7207): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7207): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    ( 7207): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7207): [NET] android_getaddrinfo_proxy+
D/libc    ( 7207): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/PowerUsageService( 7021): calcPower(), no data
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7207): [NET] android_getaddrinfo_proxy-, success
,I/dex2oat ( 7239): dex2oat took 568.345ms (threads: 4),
,I/PushClient( 7190): ApplicationMonitor {a45ccd3}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 7190): ApplicationMonitor {a45ccd3}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 7190): ApplicationMonitor {a45ccd3}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7190): ApplicationMonitor {a45ccd3}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7190): ApplicationMonitor {a45ccd3}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 7190): ApplicationMonitor {a45ccd3}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 7190): ApplicationMonitor {a45ccd3}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false,
,I/PushClient( 7190): ApplicationMonitor {a45ccd3}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7190): ApplicationMonitor {a45ccd3}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7190): PnsModel {b8226c2}: update(): Update registration caused by: alarm
,I/PushClient( 7190): PnsConfigModel {257e8e41}: <init>(): Use dm-client for provisioning.,
,W/System.err( 7190): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 7190): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7190): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.,
,W/ContextImpl( 7190): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  970): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7252 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7252): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7252 dbg=false s=true
,I/DeviceManagement( 7252): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 7252): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,D/Process (  970): killProcessQuiet, pid=6801
I/ActivityManager(  970): Killing 6801:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 7252): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/ActivityManager(  970): Recipient 6801
,I/DeviceManagement( 7252): WorkflowService: Starting workflow service
,I/DeviceManagement( 7252): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@b8226c2] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7252): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7252): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7252): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7252): SessionStateController: Checking invariants...,
,I/art     (  970): Explicit concurrent mark sweep GC freed 33082(1787KB) AllocSpace objects, 11(1352KB) LOS objects, 33% free, 16MB/25MB, paused 1.759ms total 156.613ms
,I/DeviceManagement( 7252): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7252): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7252): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7252): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@b8226c2]
,I/DeviceManagement( 7252): WorkflowService: Stopping workflow service,
,I/ActivityManager(  970): Killing 6343:com.android.settings/1000 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=6343
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6343,
,I/PushClient( 7190): PnsModel {b8226c2}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  970): killProcessQuiet, pid=6369,
I/ActivityManager(  970): Killing 6369:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6369
,W/SQLiteConnectionPool( 7207): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,D/PMS     (  970): acquireWL(1cec1653): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{2d5f8c1e: PendingIntentRecord{2b93fcff android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=979596, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{1684fb90: PendingIntentRecord{3ca52c89 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449057397239, Int=0
,D/SmartSyncUtils( 7021): isEpsOn(), nState = 0,
,D/PMS     (  970): acquireWL(20dbe48e): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7021 1000 null
,D/PMS     (  970): releaseWL(1cec1653): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 7021): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 7021): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 7021): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 7021): SettingOnTime = 1449122400000, randomSettingOnTime = 1449119509000
D/SmartSyncScreenOnOffTimeReceiver( 7021): SettingOffTime = 1449100800000, randomSettingOffTime = 1449106916000
,D/SmartSyncScreenOnOffTimeReceiver( 7021): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 7021): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 7021): bNightModeTurnOffOnce = false
,D/PMS     (  970): releaseWL(20dbe48e): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  970): acquireWL(1117c4af): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(1117c4af): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  970): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DefaultState
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(136640bc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(136640bc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
,D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  970): << updateStatus
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(37ab0845): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(37ab0845): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): updateBatteryInfo
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  970): User[0] Flushing usage stats to disk,
,D/PMS     (  970): acquireWL(3ab5bb9a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
,I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3ab5bb9a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  970): runPSCheck
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(11a5fccb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(11a5fccb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): updateBatteryInfo
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
,D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(26b4aca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(26b4aca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100,
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(3978e3c1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3978e3c1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
,D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(3623f766): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3623f766): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): << updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(1959aa7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
,I/BatteryService(  970): n_update end
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): releaseWL(1959aa7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/NotificationService(  970): plugged=true pluggin=true
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): updateBatteryInfo
D/WifiController(  970): processMsg: DeviceActiveState
D/PMS     (  970): runPSCheck
D/WifiController(  970): processMsg: StaEnabledState
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: X
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  970): acquireWL(24eefafd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{2d5f8c1e: PendingIntentRecord{2b93fcff android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1039597, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{26e823f2: PendingIntentRecord{af73a43 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1844056, Int=0
,I/bt-btm  ( 3329): Received oneshot timer event complete
I/bt-btm  ( 3329): btm_ble_timeout
I/bt-btm  ( 3329): btm_gen_resolvable_private_addr
,D/PMS     (  970): acquireWL(11d668c0): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3329 1002 null
,D/bt-btm  ( 3329): btm_ble_rand_enc_complete
I/ProcessStatsService(  970): Prepared write state in 12ms
I/bt-btm  ( 3329): btm_gen_resolve_paddr_low
D/bt-smp  ( 3329): smp_encrypt_data
W/bt-smp  ( 3329): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3329): Plain text(LSB ~ MSB) = 45 c4 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3329): Encrypted text(LSB ~ MSB) = ca b8 9b cf 34 98 f2 20 a8 cd f9 61 49 13 95 31 
I/bt-btm  ( 3329): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3329): Stopping oneshot timer
,D/bt-btm  ( 3329): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  970): releaseWL(24eefafd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,I/ProcessStatsService(  970): Pruning old procstats: /data/system/procstats/state-2015-12-01-15-20-40.bin,
,D/PMS     (  970): releaseWL(11d668c0): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  970): acquireWL(30b549f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(30b549f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3329): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(29508d3e): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024}
,V/AlarmManager(  970): sending alarm PendingIntent{1e49379f: PendingIntentRecord{181950ec com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449057859695, Int=1800000
,V/AlarmManager(  970): sending alarm PendingIntent{3bf78cb5: PendingIntentRecord{14e09f6c com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=1599297, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{3e443f4a: PendingIntentRecord{b93aebb com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1856876, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{cc08fd8: PendingIntentRecord{25346273 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1871287, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{262bf71e: PendingIntentRecord{25378bff android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1691207, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{340b7aaa: PendingIntentRecord{31bf369b android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825600, Int=1800000
,V/AlarmManager(  970): sending alarm PendingIntent{32e13f31: PendingIntentRecord{3abe797f com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449058251616, Int=0
,D/PMS     (  970): acquireWL(1c0f0616): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4675 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(259ad184): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(3ed99d6d): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4675 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1c0f0616): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4675): Aggregate from 1449056480196 (log), 1449056059654 (data)
,D/LocationManagerService(  970): getAllProviders()=[passive, gps, network]
,D/PMS     (  970): acquireWL(1660d25): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10176 com.google.android.youtube},
,I/ActivityManager(  970): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7288 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  970): releaseWL(259ad184): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(130efa): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(130efa): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(2609bcab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(e39f08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
,D/PMS     (  970): releaseWL(3ed99d6d): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  428): Explicit concurrent mark sweep GC freed 8631(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 229us total 27.859ms,
D/PMS     (  970): releaseWL(e39f08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
,W/ContextImpl( 7021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  970): releaseWL(29508d3e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 7021): MY_DEBUG = false
,I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 193us total 23.019ms
D/PowerUsageService( 7021): repeat time = 1449059151883
,D/PMS     (  970): acquireWL(3d708352): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms},
,I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 167us total 21.714ms
,D/PMS     (  970): releaseWL(2609bcab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GLSUser ( 1924): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1924): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1924): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1924): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/PowerUsageList:PowerUsageHelper( 7021): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 7021): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 7021): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 7021): gen(), null == sipper.uidObj, userId = 0,
,W/ResourcesManager( 7288): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7288): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7288): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 7288): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7288): Installed default security provider GmsCore_OpenSSL
,D/PowerUsageService( 7021): calcPower(), no data,
,D/PMS     (  970): releaseWL(3d708352): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(26cd2aaa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(26cd2aaa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(31d7269b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(31d7269b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/ResourcesManager( 7288): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7288): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/cutils-trace( 7324): Error opening trace file: Permission denied (13)
,I/dex2oat ( 7324): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-47249223.jar --oat-fd=27 --oat-location=/data/data/com.google.android.youtube/cache/ads-47249223.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7324): dex2oat: override thread count:4
,E/YouTube MDX( 7288): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 7288): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    ( 7288): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  970): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 7288): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 7324): dex2oat took 320.833ms (threads: 4)
,D/VoldConnector(  970): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 7288): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/VoldConnector(  970): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 7288): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,D/VoldConnector(  970): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/},
,W/ContextImpl( 7288): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/InstanceID/Rpc( 7288): Found 10024,
,D/VoldConnector(  970): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
W/ContextImpl( 7288): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,D/PMS     (  970): acquireWL(2074a7fe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2074a7fe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1660d25): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube}
,D/PMS     (  970): acquireWL(94f1b5f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(94f1b5f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Killing 6080:com.google.android.gms.wearable/u0a24 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=6080
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/GCM     ( 1924): Message class com.google.f.a.a.i,
D/PMS     (  970): acquireWL(17a0ff2d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(17a0ff2d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Recipient 6080
,D/libc    ( 7288): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7288): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7288): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7288): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 7288): [NET] android_getaddrinfo_proxy+
D/libc    ( 7288): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7288): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 7288): [NET] android_getaddrinfofornet+,hn 14(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7288): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7288): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7288): [NET] android_getaddrinfofornet-, err=8
,TIME-OUT KILL (timeout was 1800000ms)
```
