#### Test 564496606be5677_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  969): acquireWL(1b8db3dd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{208672a1: PendingIntentRecord{19b20cc6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=123691, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{22111b52: PendingIntentRecord{2b07ce23 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453288566636, Int=0
D/PMS     (  969): acquireWL(5339f20): PARTIAL_WAKE_LOCK  *backup* 0x1 969 1000 null
D/PMS     (  969): releaseWL(1b8db3dd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/BackupManagerService(  969): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  969): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  969): releaseWL(5339f20): PARTIAL_WAKE_LOCK  *backup* 0x1 null
--------- beginning of main
D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,E/cutils-trace( 7052): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7052): ====startRecUseTime====
D/htc.customization.log.level( 7052):  is 
W/CustomizationLogLevel( 7052): Level value is invalid, use default level 2
D/CustomizationManager( 7052):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 7052): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7052): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7052): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7052): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7052): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7052): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7052): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7052): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7052): Parsing tag category name = system
I/CustomizationCIDLoader( 7052): Parsing tag category name = application
I/CustomizationCIDLoader( 7052): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7052): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7052): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7052): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7052): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7052): add string-array item, value = 42507
I/CustomizationCIDLoader( 7052): add string-array item, value = 21902
I/CustomizationCIDLoader( 7052): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7052): add string-array item, value = 23420
I/CustomizationCIDLoader( 7052): add string-array item, value = 22299
I/CustomizationCIDLoader( 7052): add string-array item, value = 24002
I/CustomizationCIDLoader( 7052): add string-array item, value = 23210
I/CustomizationCIDLoader( 7052): add string-array item, value = 23205
I/CustomizationCIDLoader( 7052): add string-array item, value = 23806
I/CustomizationCIDLoader( 7052): add string-array item, value = 23430
I/CustomizationCIDLoader( 7052): add string-array item, value = 23408
I/CustomizationCIDLoader( 7052): add string-array item, value = 27205
I/CustomizationCIDLoader( 7052): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7052): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7052):  Read CID file spent 0.102 (s)
D/CustomizationManager( 7052):  All configurations done spent 0.103 (s)
I/ActivityManager(  969): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7052 on display 0
D/PMS     (  969): acquireHCC(2436b0d9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 969 1000 null
D/PMS     (  969): acquireHCC(36019a9e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 969 1000 null
I/ActivityManager(  969): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7070 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1332): [EventService]  onDisplayChanged: 0
V/ActivityManager(  969): Display changed displayId=0
D/DotMatrix( 1332): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1589): [trimMemory] 20
I/WebViewFactory( 7070): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 7070): Time to load native libraries: 9 ms (timestamps 2348-2357)
,I/LibraryLoader( 7070): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7070): Binding Chromium to main looper Looper (main, tid 1) {274f4cd7},
I/LibraryLoader( 7070): Expected native library version number "",actual native library version number ""
,I/chromium( 7070): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7070): Initializing chromium process, singleProcess=true,
,W/art     ( 7070): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7070): ApplicationContext is null in ApplicationStatus
,W/chromium( 7070): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7070): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7070): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 7070): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7070): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7070): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7070): Local Branch: 
I/Adreno-EGL( 7070): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7070): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7070):                  d74aa161a12b9c6fc6332151
,W/System.err(  969): java.lang.Throwable: stack dump,
W/System.err(  969): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  969): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  969): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  969): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a72fd02:true
,D/BluetoothAdapter( 7070): 953278323: getState(). Returning 12,
,W/art     ( 7070): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 7070): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 7070): CordovaWebView is running on device made by: HTC
,W/art     ( 7070): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7070): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  969): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 7070): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  969): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
D/StatusBarManagerService(  969): setSystemUiVisibility(0x0)
,D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
,D/FindExtension( 7070): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 7070): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@216dd019, mServedView=org.apache.cordova.engine.SystemWebView{3d7f68de VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3ae77abf,
I/InputMethodManagerService(  969): Disable input method client, pid=1589
D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 7070): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  969): Displayed com.test.thalitest/.MainActivity: +620ms (total +662ms)
,W/BindingManager( 7070): Cannot call determinedVisibility() - never saw a connection for the pid: 7070,
,D/JsMessageQueue( 7070): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 7070): JniHelper::setJavaVM(0xaafde8f8), pthread_self() = -1406077440
,I/chromium( 7070): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,W/jxcore-log( 7070): Initializing JXcore engine,
W/jxcore-log( 7070): JXcore engine is ready
,W/jxcore-log( 7070): Starting JXcore engine,
,D/PMS     (  969): releaseHCC(2436b0d9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  969): releaseHCC(36019a9e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 7070): Platform android,
W/jxcore-log( 7070): 
W/jxcore-log( 7070): Process ARCH arm
W/jxcore-log( 7070): 
,I/jxcore-log( 7070): JXcore Cordova bridge is ready!
I/jxcore-log( 7070): 
,W/jxcore-log( 7070): JXcore engine is started
,E/jxcore  ( 7070): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 7070): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 7070): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,I/ActivityManager(  969): Killing 6721:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  969): killProcessQuiet, pid=6721
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  969): Recipient 6721
,W/PluginManager( 7070): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 141ms. Plugin should use CordovaInterface.getThreadPool().
,D/Process (  969): killProcessQuiet, pid=6162,
I/ActivityManager(  969): Killing 6162:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6162
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  969): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  969): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  969): acquireWL(2ccf535f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 969 1000 null,
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, err=8
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  969): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  969): [NET] android_getaddrinfo_proxy+
D/libc    (  969): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  969): [NET] android_getaddrinfo_proxy-, success,
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233392e),sn(),hints(known),family 0,flags 4
,D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS,
,D/GpsLocationProvider(  969): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  969): [reportHTCStatus] eventMask = 3 , status = 0
D/PMS     (  969): acquireWL(30bfc67b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 969 1000 null
D/GpsLocationProvider(  969): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  969): releaseWL(2ccf535f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  969):  [handleDownloadXtraData]inject done.
D/PMS     (  969): releaseWL(30bfc67b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  969): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  969): acquireWL(2e432c98): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10024}
,V/AlarmManager(  969): sending alarm PendingIntent{3fc07cf1: PendingIntentRecord{1e6cd0d6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=149180, Int=0
,D/PMS     (  969): releaseWL(2e432c98): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  969): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/PMS     (  969): acquireWL(377a4f57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
D/UsbnetService(  969): BroadcastReceiver::onReceive+
I/BatteryService(  969): n_update end
,D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): releaseWL(377a4f57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  969): processMsg: DeviceActiveState
D/HtcPowerSaver(  969): updateBatteryInfo
D/WifiController(  969): processMsg: StaEnabledState
D/PMS     (  969): runPSCheck
D/WifiController(  969): processMsg: DefaultState
D/HtcPowerSaver(  969): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: X
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1543): switchBindHtcMsgCursor: null,
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1627): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@916be77
,D/Process (  969): killProcessQuiet, pid=6746
I/ActivityManager(  969): Killing 6746:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6746
,D/PMS     (  969): acquireWL(178a7a44): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{208672a1: PendingIntentRecord{19b20cc6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=183690, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{bcef72d: PendingIntentRecord{303d2462 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=213004, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{30ea89f3: PendingIntentRecord{2ed6f6b0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=195250, Int=0
,D/PMS     (  969): acquireWL(2cd0d929): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(178a7a44): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/PMS     (  969): acquireWL(15cd24ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(2cd0d929): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  969): releaseWL(15cd24ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(1da6ebc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(1da6ebc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  969): acquireWL(20998461): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(20998461): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(2bb91b86): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(13d7bc47): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10176 com.google.android.youtube}
,I/ActivityManager(  969): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7127 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  969): acquireWL(1422fc74): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(2bb91b86): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/StatusBarManagerService(  969): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
,D/StatusBarManagerService(  969): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  969): hiding MENU key
,D/FindExtension( 1589): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/ThreadedRenderer( 1589): Defer allocateBuffers to drawing time
,W/IInputConnectionWrapper( 7070): Do restartInputUnchecked, ic=null
I/InputMethodManagerService(  969): Disable input method client, pid=7070
I/InputMethodManager( 7070): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 7070): reportFullscreenMode on inactive InputConnection,
,I/GoogleURLConnFactory( 1947): Using platform SSLCertificateSocketFactory
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
,D/PMS     (  969): releaseWL(1422fc74): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(28f6296a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(28f6296a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/ResourcesManager( 7127): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7127): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7127): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PMS     (  969): acquireWL(236a1e5b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(236a1e5b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/System  ( 7127): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 7127): Installed default security provider GmsCore_OpenSSL
,E/cutils-trace( 7162): Error opening trace file: Permission denied (13)
,I/dex2oat ( 7162): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads2098078175.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads2098078175.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7162): dex2oat: override thread count:4
,E/YouTube MDX( 7127): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 7127): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
D/libc    ( 7127): [NET] android_getaddrinfofornet-, SUCCESS,
I/dex2oat ( 7162): dex2oat took 44.772ms (threads: 4)
,D/VoldConnector(  969): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,W/ContextImpl( 7127): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,D/VoldConnector(  969): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/ContextImpl( 7127): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,W/ContextImpl( 7127): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files,
D/VoldConnector(  969): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,D/VoldConnector(  969): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 7127): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 7127): Found 10024
,D/VoldConnector(  969): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 7127): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/PMS     (  969): acquireWL(b679abe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(b679abe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 7127): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7127): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7127): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 7127): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7127): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7127): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 7127): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 7127): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7127): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7127): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7127): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7127): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7127): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7127): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7127): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7127): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7127): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7127): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 7127): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7127): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7127): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7127): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  969): releaseWL(13d7bc47): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube}
,D/PMS     (  969): acquireWL(14e60b04): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(14e60b04): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(66618ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(95f0322): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(133ad370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(66618ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1947): Vacuum at: now=1453288653068 tag=VacuumService,
,I/GoogleURLConnFactory( 1947): Using platform SSLCertificateSocketFactory,
,D/PMS     (  969): releaseWL(95f0322): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(70e2f6e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1947): No account for auth token provided,
,D/PMS     (  969): releaseWL(70e2f6e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(3871d47a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(3871d47a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/libc    ( 1947): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1947): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1947): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1947): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1947): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1947): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1947): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1947): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1947): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1947): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1947): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1947): No account for auth token provided,
,W/Uploader( 1947): No account for auth token provided,
,W/Uploader( 1947): No account for auth token provided,
,W/Uploader( 1947):  no longer exists, so no auth token.,
,W/Uploader( 1947): No account for auth token provided
,I/GLSUser ( 1947): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1947): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1947): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1947): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1220): reapply : com.google.android.gms 1 40
,D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1947): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1947): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1947): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1947): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1947): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1947): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1947): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1947): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
,E/Uploader( 1947): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1947): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1947): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1947): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1947): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  969): releaseWL(133ad370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(521f8a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(521f8a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(34f7cc59): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(34f7cc59): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  969): Killing 6770:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
D/Process (  969): killProcessQuiet, pid=6770
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6770,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  969): acquireWL(339b501e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  969): n_update end
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): releaseWL(339b501e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
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
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/WifiController(  969): battery changed pluggedType: 2
,D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: DefaultState
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1328): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1328): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1328): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1328): wlan0: BSS: Remove id 4 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11]
,E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  969): acquireWL(20be70ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(20be70ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
,D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1220): closing low battery warning: level=100
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  969): processMsg: DefaultState
,D/WifiController(  969): handleMessage: X
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): runPSCheck
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): Checking...
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): >> updateStatus
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  969): acquireWL(1bbdfecc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(1bbdfecc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  969): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): >> updateStatus,
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1947): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1947): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1947): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1947): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1220): reapply : com.google.android.gms 3 40
,W/GLSActivity( 1947): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1947): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1947): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1947): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1947): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1947): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1947): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6432): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6432): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6432): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6432): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6432): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6432): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6432): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6432): Ignoring header User-Agent because its value was null.
,D/libc    ( 6432): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6432): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6432): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6432): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6432): [NET] android_getaddrinfo_proxy+
D/libc    ( 6432): [NET] android_getaddrinfo_proxy get netid:0,
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6432): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  969): acquireWL(dc9fcce): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
V/AlarmManager(  969): sending alarm PendingIntent{208672a1: PendingIntentRecord{19b20cc6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=243690, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{1424b2fc: PendingIntentRecord{2d112d85 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453288781714, Int=0
,I/ActivityManager(  969): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7223 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  969): sending alarm PendingIntent{260d17da: PendingIntentRecord{3d73c40b com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453288847348, Int=0
,D/PMS     (  969): releaseWL(dc9fcce): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,E/cutils-trace( 7244): Error opening trace file: Permission denied (13)
,I/dex2oat ( 7244): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7244): dex2oat: override thread count:4
,I/dex2oat ( 7244): dex2oat took 951.450ms (threads: 4)
,I/PushClient( 7223): ApplicationMonitor {2f21eaa9}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
I/PushClient( 7223): ApplicationMonitor {2f21eaa9}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 7223): ApplicationMonitor {2f21eaa9}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7223): ApplicationMonitor {2f21eaa9}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 7223): ApplicationMonitor {2f21eaa9}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7223): ApplicationMonitor {2f21eaa9}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 7223): ApplicationMonitor {2f21eaa9}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7223): ApplicationMonitor {2f21eaa9}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7223): ApplicationMonitor {2f21eaa9}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7223): PnsModel {29635e30}: update(): Update registration caused by: alarm
,I/PushClient( 7223): PnsConfigModel {3fa719c7}: <init>(): Use dm-client for provisioning.
,W/System.err( 7223): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 7223): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7223): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7223): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  969): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7252 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7252): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7252 dbg=false s=true
,I/DeviceManagement( 7252): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 7252): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7252): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 7252): WorkflowService: Starting workflow service
,I/DeviceManagement( 7252): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@29635e30] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7252): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7252): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7252): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7252): SessionStateController: Checking invariants...
,I/art     (  969): Explicit concurrent mark sweep GC freed 32514(1806KB) AllocSpace objects, 7(840KB) LOS objects, 33% free, 16MB/24MB, paused 1.598ms total 137.531ms
,I/DeviceManagement( 7252): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7252): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7252): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7252): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@29635e30]
,I/DeviceManagement( 7252): WorkflowService: Stopping workflow service,
,I/ActivityManager(  969): Killing 6791:com.android.settings/1000 (adj 15): empty #17
D/Process (  969): killProcessQuiet, pid=6791,
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6791,
,I/PushClient( 7223): PnsModel {29635e30}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  969): killProcessQuiet, pid=5353
,I/ActivityManager(  969): Killing 5353:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 5353
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  969): acquireWL(378d32c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(378d32c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  969): updateBatteryInfo,
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  969): >> updateStatus
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,D/PowerUI ( 1220): closing low battery warning: level=100
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  969): acquireWL(ad181f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(ad181f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): handleMessage: E msg.what=155652
,D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  969): processMsg: StaEnabledState
D/HtcPowerSaver(  969): updateBatteryInfo
D/WifiController(  969): processMsg: DefaultState
D/PMS     (  969): runPSCheck,
D/WifiController(  969): handleMessage: X
D/HtcPowerSaver(  969): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): >> updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): << updateStatus
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  969): acquireWL(294b2b8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(294b2b8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  969): plugged=true pluggin=true
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
,D/WifiController(  969): handleMessage: E msg.what=155652
D/PMS     (  969): runPSCheck
D/WifiController(  969): processMsg: DeviceActiveState
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DefaultState
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  969): acquireWL(3301c5fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): releaseWL(3301c5fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): updateBatteryInfo
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
,D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): Checking...
,D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): processMsg: DeviceActiveState
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1543): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1543): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1543): sku_id=118
D/ContactMessageStore( 1543): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1543): start background delete task...
,D/ContactMessageStore( 1543): size: 0 , 0,
D/ContactMessageStore( 1543): Background delete complete
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PMS     (  969): acquireWL(1d35f618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,D/UsbnetService(  969): onReceive BATTERY_CHANGED
I/BatteryService(  969): n_update end
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): releaseWL(1d35f618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/NotificationService(  969): plugged=true pluggin=true
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  969): processMsg: StaEnabledState
D/HtcPowerSaver(  969): updateBatteryInfo
D/WifiController(  969): processMsg: DefaultState
D/PMS     (  969): runPSCheck
D/WifiController(  969): handleMessage: X
D/HtcPowerSaver(  969): Checking...
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  969): >> updateStatus
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  969): acquireWL(f854871): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(f854871): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  969): updateBatteryInfo
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  969): plugged=true pluggin=true
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  969): >> updateStatus
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  969): acquireWL(30387656): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(30387656): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: E msg.what=155652
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): processMsg: DeviceActiveState
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  969): acquireWL(189cc6d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  969): plugged=true pluggin=true
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/PMS     (  969): releaseWL(189cc6d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1220): closing low battery warning: level=100
,D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  969): acquireWL(20a05bc4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{208672a1: PendingIntentRecord{19b20cc6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=423690, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{385436e3: PendingIntentRecord{3b26b8e0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804896, Int=0
,V/AlarmManager(  969): sending alarm PendingIntent{6dda1e2: PendingIntentRecord{383ef65c com.android.vending startService}}, i=null, t=0, cnt=1, w=1453289081699, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{a7cf973: PendingIntentRecord{2d297030 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937481, Int=0
,D/Finsky  ( 6432): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/ActivityManager(  969): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=7283 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
V/AlarmManager(  969): sending alarm PendingIntent{25b7fa2e: PendingIntentRecord{b23b9cf com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WeatherUtility( 1220): Weather sync is On,
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,I/art     ( 1947): Explicit concurrent mark sweep GC freed 41262(2MB) AllocSpace objects, 10(604KB) LOS objects, 46% free, 4MB/8MB, paused 1.344ms total 70.639ms
,D/PMS     (  969): acquireWL(244713c7): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(20a05bc4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,D/PMS     (  969): releaseWL(244713c7): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ImageRamCache( 7283): create image Cache, size: 31457280.
,I/ImageRamCache( 7283): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 7283): create image Cache, size: 31457280.
,I/FeedSettings( 7283): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 7283): GroupBudget 0.500000 0.380000
I/FeedSettings( 7283): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 7283): changeLocale(): en_GB
,D/PMS     (  969): acquireWL(3a972563): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1947 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1947): Message class com.google.f.a.a.i
,D/PMS     (  969): releaseWL(3a972563): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1947): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1947): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1947): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1947): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Prism.AllAppsOptionsMa_( 7283): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 7283): loadGridSize() with Alternative
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6432): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/libc    ( 7283): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4,
D/libc    ( 7283): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7283): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    ( 7283): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7283): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7283): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/GLSUser ( 1947): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1947): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1947): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1947): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7283): [NET] android_getaddrinfo_proxy-, success
,I/GLSUser ( 1947): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1947): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1947): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1947): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6432): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1947): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1947): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1947): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1947): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1947): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6432): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
D/Finsky  ( 6432): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6432): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6432): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1855): client connected with version: 7571000
,D/Process (  969): killProcessQuiet, pid=6824
I/ActivityManager(  969): Killing 6824:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6824
,W/SQLiteConnectionPool( 7283): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/PMS     (  969): acquireWL(1960a297): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1002}
,I/bt-btm  ( 3530): Received oneshot timer event complete
V/AlarmManager(  969): sending alarm PendingIntent{17796c84: PendingIntentRecord{2fdb9c6d com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=946076, Int=0
I/bt-btm  ( 3530): btm_ble_timeout
I/bt-btm  ( 3530): btm_gen_resolvable_private_addr
D/PMS     (  969): releaseWL(1960a297): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1002}
D/PMS     (  969): acquireWL(337900a2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3530 1002 null
,D/bt-btm  ( 3530): btm_ble_rand_enc_complete,
I/bt-btm  ( 3530): btm_gen_resolve_paddr_low
D/bt-smp  ( 3530): smp_encrypt_data
W/bt-smp  ( 3530): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3530): Plain text(LSB ~ MSB) = bb 74 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3530): Encrypted text(LSB ~ MSB) = 36 e5 03 da c7 1f e5 f0 c2 76 12 bd 72 03 b2 26 
,I/bt-btm  ( 3530): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3530): Stopping oneshot timer
D/bt-btm  ( 3530): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  969): releaseWL(337900a2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  969): acquireWL(2562ccf0): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072},
V/AlarmManager(  969): sending alarm PendingIntent{37229269: PendingIntentRecord{288a84ee com.android.vending startService}}, i=null, t=0, cnt=1, w=1453289389178, Int=0
D/PMS     (  969): releaseWL(2562ccf0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 6432): [642] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 6432): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  969): acquireWL(358f4d8f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(358f4d8f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+,
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1220): closing low battery warning: level=100
,D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PMS     (  969): runPSCheck
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  969): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): >> updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  969): battery changed pluggedType: 2
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  969): acquireWL(33fc81c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
,V/AlarmManager(  969): sending alarm PendingIntent{208672a1: PendingIntentRecord{19b20cc6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=963690, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{32c8ec25: PendingIntentRecord{23af0f7c com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453289408963, Int=0
,W/ContextImpl( 6988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6988): MY_DEBUG = false
,D/PowerUsageService( 6988): repeat time = 1453290308988
D/PMS     (  969): releaseWL(33fc81c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,I/PowerUsageList:PowerUsageHelper( 6988): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6988): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  969): acquireWL(3fbd33ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1000},
V/AlarmManager(  969): sending alarm PendingIntent{2a8f4a08: PendingIntentRecord{11c125a1 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453289455744, Int=0
,D/SmartSyncUtils( 6988): isEpsOn(), nState = 0,
,D/PMS     (  969): releaseWL(3fbd33ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  969): acquireWL(243a43c6): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6988 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6988): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6988): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6988): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6988): SettingOnTime = 1453356000000, randomSettingOnTime = 1453355942000
D/SmartSyncScreenOnOffTimeReceiver( 6988): SettingOffTime = 1453334400000, randomSettingOffTime = 1453338422000
,D/SmartSyncScreenOnOffTimeReceiver( 6988): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6988): bNightMode = true,
D/SmartSyncScreenOnOffTimeReceiver( 6988): bNightModeTurnOffOnce = false
,D/PMS     (  969): releaseWL(243a43c6): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  969): acquireWL(1e995f87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(1e995f87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1220): closing low battery warning: level=100
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  969): acquireWL(2bd2feb4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(2bd2feb4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PMS     (  969): runPSCheck
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  969): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): >> updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  969): battery changed pluggedType: 2
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PMS     (  969): acquireWL(25a97add): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/UsbnetService(  969): onReceive BATTERY_CHANGED
I/BatteryService(  969): n_update end
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): releaseWL(25a97add): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/NotificationService(  969): plugged=true pluggin=true
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  969): processMsg: StaEnabledState
D/HtcPowerSaver(  969): updateBatteryInfo
D/WifiController(  969): processMsg: DefaultState
D/PMS     (  969): runPSCheck
D/WifiController(  969): handleMessage: X
D/HtcPowerSaver(  969): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): >> updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  969): acquireWL(1086d652): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(1086d652): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: E msg.what=155652
,D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: DefaultState
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): << updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  969): User[0] Flushing usage stats to disk
,D/PMS     (  969): acquireWL(34226d23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(34226d23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  969): updateBatteryInfo
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
,D/HeadsetStateMachine( 3530): Disconnected process message: 10, size: 0
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
