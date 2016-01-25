#### Test 57132760f6ec045_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6879): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6879): ====startRecUseTime====
D/htc.customization.log.level( 6879):  is 
W/CustomizationLogLevel( 6879): Level value is invalid, use default level 2
D/CustomizationManager( 6879):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6879): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6879): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6879): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6879): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6879): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6879): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6879): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6879): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6879): Parsing tag category name = system
I/CustomizationCIDLoader( 6879): Parsing tag category name = application
I/CustomizationCIDLoader( 6879): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6879): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6879): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6879): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6879): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6879): add string-array item, value = 42507
I/CustomizationCIDLoader( 6879): add string-array item, value = 21902
I/CustomizationCIDLoader( 6879): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6879): add string-array item, value = 23420
I/CustomizationCIDLoader( 6879): add string-array item, value = 22299
I/CustomizationCIDLoader( 6879): add string-array item, value = 24002
I/CustomizationCIDLoader( 6879): add string-array item, value = 23210
I/CustomizationCIDLoader( 6879): add string-array item, value = 23205
I/CustomizationCIDLoader( 6879): add string-array item, value = 23806
I/CustomizationCIDLoader( 6879): add string-array item, value = 23430
I/CustomizationCIDLoader( 6879): add string-array item, value = 23408
I/CustomizationCIDLoader( 6879): add string-array item, value = 27205
I/CustomizationCIDLoader( 6879): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6879): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6879):  Read CID file spent 0.103 (s)
D/CustomizationManager( 6879):  All configurations done spent 0.104 (s)
--------- beginning of system
I/ActivityManager(  969): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6879 on display 0
D/PMS     (  969): acquireHCC(2a4acd7e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 969 1000 null
D/PMS     (  969): acquireHCC(39ea12df): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 969 1000 null
W/asset   (  969): Copying FileAsset 0x5582314be0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  969): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6897 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1310): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1310): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  969): Display changed displayId=0
W/asset   ( 6897): Copying FileAsset 0xac0a8f48 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1494): [trimMemory] 20
I/WebViewFactory( 6897): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6897): Time to load native libraries: 9 ms (timestamps 1061-1070),
,I/LibraryLoader( 6897): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6897): Binding Chromium to main looper Looper (main, tid 1) {2e26bb9b},
I/LibraryLoader( 6897): Expected native library version number "",actual native library version number ""
,I/chromium( 6897): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6897): Initializing chromium process, singleProcess=true,
,W/art     ( 6897): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6897): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6897): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6897): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6897): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6897): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6897): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6897): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6897): Local Branch: 
I/Adreno-EGL( 6897): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6897): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6897):                  d74aa161a12b9c6fc6332151
,W/System.err(  969): java.lang.Throwable: stack dump
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  969): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  969): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  969): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  969): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@161eb3c4:true
,D/BluetoothAdapter( 6897): 497776247: getState(). Returning 12,
,W/art     ( 6897): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6897): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6897): CordovaWebView is running on device made by: HTC
,W/art     ( 6897): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6897): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  969): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/chromium( 6897): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  969): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
,D/StatusBarManagerService(  969): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
,D/FindExtension( 6897): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6897): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@153699bd, mServedView=org.apache.cordova.engine.SystemWebView{10453bb2 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2356d703
,I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
I/InputMethodManagerService(  969): Disable input method client, pid=1494
D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6897): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  969): Displayed com.test.thalitest/.MainActivity: +644ms (total +689ms)
,W/BindingManager( 6897): Cannot call determinedVisibility() - never saw a connection for the pid: 6897
,D/JsMessageQueue( 6897): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6897): JniHelper::setJavaVM(0xaaf3c8f8), pthread_self() = -1406662328
,I/chromium( 6897): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6897): Initializing JXcore engine
W/jxcore-log( 6897): JXcore engine is ready
,W/jxcore-log( 6897): Starting JXcore engine,
,D/PMS     (  969): releaseHCC(2a4acd7e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  969): releaseHCC(39ea12df): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/Process (  969): killProcessQuiet, pid=5870
I/ActivityManager(  969): Killing 5870:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/jxcore-log( 6897): Platform android,
W/jxcore-log( 6897): 
W/jxcore-log( 6897): Process ARCH arm
W/jxcore-log( 6897): 
,I/ActivityManager(  969): Recipient 5870
,I/jxcore-log( 6897): JXcore Cordova bridge is ready!
I/jxcore-log( 6897): 
,W/jxcore-log( 6897): JXcore engine is started
,E/jxcore  ( 6897): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6897): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6897): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/Process (  969): killProcessQuiet, pid=6534
I/ActivityManager(  969): Killing 6534:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  969): Recipient 6534
,W/PluginManager( 6897): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 141ms. Plugin should use CordovaInterface.getThreadPool().
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  969): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  969): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  969): acquireWL(16caf8c): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 969 1000 null
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  969): [NET] android_getaddrinfofornet-, err=8
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  969): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  969): [NET] android_getaddrinfo_proxy+
,D/libc    (  969): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  969): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 12(0x35342e3233302e),sn(),hints(known),family 0,flags 4
,D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  969): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  969): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  969): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  969):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  969): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  969): acquireWL(1efb3878): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 969 1000 null
D/PMS     (  969): releaseWL(16caf8c): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  969): releaseWL(1efb3878): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  969): acquireWL(20fbcb51): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10024}
V/AlarmManager(  969): sending alarm PendingIntent{14ce6fb6: PendingIntentRecord{1eb334b7 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=149167, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{28e76424: PendingIntentRecord{2e0cb8d android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453758228994, Int=0
,D/PMS     (  969): acquireWL(33c9d142): PARTIAL_WAKE_LOCK  *backup* 0x1 969 1000 null
D/PMS     (  969): releaseWL(20fbcb51): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  969): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  969): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  969): releaseWL(33c9d142): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,W/ContextImpl(  969): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  969): acquireWL(25bc6553): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(25bc6553): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  969): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): >> updateStatus
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1436): switchBindHtcMsgCursor: null,
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1585): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@12cf7ad3
I/ActivityManager(  969): Killing 6628:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  969): killProcessQuiet, pid=6628
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6628
,D/PMS     (  969): acquireWL(29489e90): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
V/AlarmManager(  969): sending alarm PendingIntent{37f42c25: PendingIntentRecord{20841fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=161956, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{279b9389: PendingIntentRecord{2927bf8e android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=213447, Int=0
,V/AlarmManager(  969): sending alarm PendingIntent{181e03af: PendingIntentRecord{324113bc com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=194658, Int=0,
,D/PMS     (  969): acquireWL(3920df45): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(29489e90): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  969): acquireWL(b64469a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(3920df45): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  969): releaseWL(b64469a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(4fe1e54): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(4fe1e54): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(1668b1fd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(1668b1fd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(177d0ef2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(1bf94943): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(259370f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(177d0ef2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1924): Vacuum at: now=1453758291842 tag=VacuumService,
,D/PMS     (  969): releaseWL(259370f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(1edd369f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(1edd369f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(28cee3ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(28cee3ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(1bf94943): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(1e1123b5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(1e1123b5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(192b8a4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(192b8a4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(3ae89dbb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(2ebc52d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(3ae89dbb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1924): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1924): No account for auth token provided,
,D/libc    ( 1924): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1924): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1924): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1924): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1924): [NET] android_getaddrinfo_proxy+
D/libc    ( 1924): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1924): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1924): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1924): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1924): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1924): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1924): No account for auth token provided
,W/Uploader( 1924): No account for auth token provided
,W/Uploader( 1924): No account for auth token provided,
,W/Uploader( 1924):  no longer exists, so no auth token.
,I/GLSUser ( 1924): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1924): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1924): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1924): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  969): Explicit concurrent mark sweep GC freed 48604(2MB) AllocSpace objects, 6(996KB) LOS objects, 33% free, 16MB/25MB, paused 2.034ms total 195.227ms
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
,E/Uploader( 1924): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1924): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1924): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1924): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1924): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1924): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1924): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1924): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1924): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1924): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1924): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1924): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1924): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1924): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1215): reapply : com.google.android.gms 2 40
,I/GLSUser ( 1924): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1924): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1924): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1924): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1924): Failed to get auth token: User intervention required. Notification has been pushed.
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
E/Uploader( 1924): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1924): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
,D/PMS     (  969): releaseWL(2ebc52d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(2ad19d9e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(2ad19d9e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(1f7a707f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(1f7a707f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  969): acquireWL(36a2c84c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(36a2c84c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
,D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1324): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1324): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
,D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97
,D/PMS     (  969): acquireWL(131ea095): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(131ea095): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  969): updateBatteryInfo
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  969): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  969): >> updateStatus
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969): BroadcastReceiver::onReceive-
,D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  969): acquireWL(135f5aa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{37f42c25: PendingIntentRecord{20841fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=221956, Int=0
,V/AlarmManager(  969): sending alarm PendingIntent{125a1d38: PendingIntentRecord{1695b111 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453758424272, Int=0
,D/PMS     (  969): releaseWL(135f5aa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/UsbnetService(  969): BroadcastReceiver::onReceive+,
D/PMS     (  969): acquireWL(3dd5c276): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  969): releaseWL(3dd5c276): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/HtcPowerSaver(  969): updateBatteryInfo
D/WifiController(  969): processMsg: StaEnabledState
D/PMS     (  969): runPSCheck
D/WifiController(  969): processMsg: DefaultState
,D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): >> updateStatus
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1924): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1924): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1924): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1924): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/RemoteViews( 1215): reapply : com.google.android.gms 2 40
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/GLSActivity( 1924): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1924): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1924): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1924): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
,W/GLSActivity( 1924): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1924): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1924): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6215): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6215): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6215): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6215): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6215): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6215): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6215): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6215): Ignoring header User-Agent because its value was null.
,D/libc    ( 6215): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6215): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6215): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6215): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6215): [NET] android_getaddrinfo_proxy+
D/libc    ( 6215): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6215): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  969): acquireWL(162b4468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(162b4468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): battery changed pluggedType: 2
,D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  969): processMsg: DefaultState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: X
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
,D/PMS     (  969): acquireWL(2fb40081): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  969): n_update end
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): releaseWL(2fb40081): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  969): >> updateStatus
,D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  969): acquireWL(c91b526): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(c91b526): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  969): processMsg: DefaultState,
D/WifiController(  969): handleMessage: X
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  969): acquireWL(9fe567): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(9fe567): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  969): processMsg: DefaultState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: X
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1436): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1436): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1436): sku_id=118
D/ContactMessageStore( 1436): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1436): start background delete task...
,D/ContactMessageStore( 1436): size: 0 , 0
,D/ContactMessageStore( 1436): Background delete complete
,D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/PMS     (  969): acquireWL(10a43f14): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  969): n_update end
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PMS     (  969): releaseWL(10a43f14): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/NotificationService(  969): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): runPSCheck
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): Checking...
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  969): acquireWL(3e9f23bd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(3e9f23bd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): processMsg: StaEnabledState
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  969): acquireWL(7d3fdb2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{37f42c25: PendingIntentRecord{20841fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=401956, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{163b7103: PendingIntentRecord{3f103880 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=946068, Int=0
,I/bt-btm  ( 3413): Received oneshot timer event complete
I/bt-btm  ( 3413): btm_ble_timeout
I/bt-btm  ( 3413): btm_gen_resolvable_private_addr
,D/PMS     (  969): acquireWL(3e1f3eb9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3413 1002 null
,D/bt-btm  ( 3413): btm_ble_rand_enc_complete
I/bt-btm  ( 3413): btm_gen_resolve_paddr_low
D/bt-smp  ( 3413): smp_encrypt_data
W/bt-smp  ( 3413): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3413): Plain text(LSB ~ MSB) = 2c 22 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3413): Encrypted text(LSB ~ MSB) = 6a f6 c2 2f 3a 72 f1 32 4c 25 f3 6a ce 8b a3 ff 
I/bt-btm  ( 3413): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3413): Stopping oneshot timer
D/bt-btm  ( 3413): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  969): releaseWL(7d3fdb2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  969): releaseWL(3e1f3eb9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  969): acquireWL(348042fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): releaseWL(348042fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  969): updateBatteryInfo
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  969): runPSCheck
D/HtcPowerSaver(  969): Checking...
I/HtcPowerSaver(  969): >> updateStatus
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  969): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  969): << updateStatus
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  969): acquireWL(3d7a1a5f): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10024}
V/AlarmManager(  969): sending alarm PendingIntent{25805cac: PendingIntentRecord{2cec0d75 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937226, Int=0
,D/PMS     (  969): acquireWL(2a19910a): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(2a19910a): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  969): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6968 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  969): sending alarm PendingIntent{2ecffd7b: PendingIntentRecord{15ec9798 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453758876057, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{2b41bd6b: PendingIntentRecord{1e7670c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805893, Int=0
,V/AlarmManager(  969): sending alarm PendingIntent{37d0bf1: PendingIntentRecord{1c6f6d57 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453759049986, Int=0
,W/ContextImpl( 6795): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  969): releaseWL(3d7a1a5f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6795): MY_DEBUG = false
,D/PowerUsageService( 6795): repeat time = 1453759950043
,D/StatusBarManagerService(  969): setSystemUiVisibility(0x700),
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
,D/StatusBarManagerService(  969): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
D/FindExtension( 1494): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1494): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  969): Disable input method client, pid=6897
W/IInputConnectionWrapper( 6897): Do restartInputUnchecked, ic=null
D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManager( 6897): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6897): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
,I/PowerUsageList:PowerUsageHelper( 6795): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6795): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 6991): Error opening trace file: Permission denied (13),
I/dex2oat ( 6991): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6991): dex2oat: override thread count:4
,D/PMS     (  969): acquireWL(7df9544): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(3045762d): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1924 10024 WorkSource{10024 com.google.android.gms}
,I/GCM     ( 4123): Message from null null
,E/GCM     ( 4123): Dropping message from null
,D/PMS     (  969): releaseWL(3045762d): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1924): Message class com.google.f.a.a.i,
,D/PMS     (  969): releaseWL(7df9544): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/dex2oat ( 6991): dex2oat took 508.978ms (threads: 4)
,I/PushClient( 6968): ApplicationMonitor {9c1434d}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6968): ApplicationMonitor {9c1434d}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6968): ApplicationMonitor {9c1434d}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6968): ApplicationMonitor {9c1434d}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6968): ApplicationMonitor {9c1434d}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6968): ApplicationMonitor {9c1434d}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6968): ApplicationMonitor {9c1434d}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6968): ApplicationMonitor {9c1434d}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6968): ApplicationMonitor {9c1434d}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6968): PnsModel {3723e2e4}: update(): Update registration caused by: alarm
,I/PushClient( 6968): PnsConfigModel {f69c18b}: <init>(): Use dm-client for provisioning.
,W/System.err( 6968): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 6968): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6968): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6968): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  969): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6998 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6998): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6998 dbg=false s=true,
,I/DeviceManagement( 6998): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6998): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6998): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6998): WorkflowService: Starting workflow service
,I/DeviceManagement( 6998): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1dab7677] args=[Bundle[mParcelledData.dataSize=88]]
I/DeviceManagement( 6998): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6998): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6998): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6998): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6998): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6998): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6998): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6998): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1dab7677]
,I/DeviceManagement( 6998): WorkflowService: Stopping workflow service,
,D/Process (  969): killProcessQuiet, pid=6190
I/ActivityManager(  969): Killing 6190:com.android.settings/1000 (adj 15): empty #17,
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6190,
,I/PushClient( 6968): PnsModel {3723e2e4}: update(): The registration record has not expired yet. No need to update.
,D/Process (  969): killProcessQuiet, pid=5224
I/ActivityManager(  969): Killing 5224:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 5224
,D/PMS     (  969): acquireWL(2017d361): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
V/AlarmManager(  969): sending alarm PendingIntent{37f42c25: PendingIntentRecord{20841fa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1001956, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{a92be86: PendingIntentRecord{182c2347 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453759097384, Int=0
D/SmartSyncUtils( 6795): isEpsOn(), nState = 0
,D/PMS     (  969): acquireWL(d74d774): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6795 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6795): [updateNmRange] bManual = false
D/PMS     (  969): releaseWL(2017d361): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6795): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
D/SmartSyncScreenOnOffTimeReceiver( 6795): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6795): SettingOnTime = 1453788000000, randomSettingOnTime = 1453786692000,
D/SmartSyncScreenOnOffTimeReceiver( 6795): SettingOffTime = 1453766400000, randomSettingOffTime = 1453766709000
D/SmartSyncScreenOnOffTimeReceiver( 6795): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6795): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6795): bNightModeTurnOffOnce = false
D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  969): releaseWL(d74d774): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): acquireWL(2c1d449d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  969): n_update end
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  969): releaseWL(2c1d449d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  969): plugged=true pluggin=true
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
,D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  969): acquireWL(21cc3d12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(21cc3d12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): updateBatteryInfo
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  969): plugged=true pluggin=true
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  969): runPSCheck
D/HeadsetStateMachine( 3413): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  969): Checking...
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  969): >> updateStatus
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  969): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
