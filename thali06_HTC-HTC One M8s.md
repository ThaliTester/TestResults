#### Test 565307121a686b7_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,E/cutils-trace( 6840): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6840): ====startRecUseTime====
D/htc.customization.log.level( 6840):  is 
W/CustomizationLogLevel( 6840): Level value is invalid, use default level 2
D/CustomizationManager( 6840):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 6840): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6840): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6840): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6840): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6840): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6840): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6840): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6840): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6840): Parsing tag category name = system
I/CustomizationCIDLoader( 6840): Parsing tag category name = application
I/CustomizationCIDLoader( 6840): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6840): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6840): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6840): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6840): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6840): add string-array item, value = 42507
I/CustomizationCIDLoader( 6840): add string-array item, value = 21902
I/CustomizationCIDLoader( 6840): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6840): add string-array item, value = 23420
I/CustomizationCIDLoader( 6840): add string-array item, value = 22299
I/CustomizationCIDLoader( 6840): add string-array item, value = 24002
I/CustomizationCIDLoader( 6840): add string-array item, value = 23210
I/CustomizationCIDLoader( 6840): add string-array item, value = 23205
I/CustomizationCIDLoader( 6840): add string-array item, value = 23806
I/CustomizationCIDLoader( 6840): add string-array item, value = 23430
I/CustomizationCIDLoader( 6840): add string-array item, value = 23408
I/CustomizationCIDLoader( 6840): add string-array item, value = 27205
I/CustomizationCIDLoader( 6840): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6840): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6840):  Read CID file spent 0.098 (s)
D/CustomizationManager( 6840):  All configurations done spent 0.098 (s)
--------- beginning of system
I/ActivityManager(  941): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6840 on display 0
D/PMS     (  941): acquireHCC(18dbac1c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 941 1000 null
D/PMS     (  941): acquireHCC(3da10025): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 941 1000 null
I/ActivityManager(  941): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6858 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1327): [EventService]  onDisplayChanged: 0
V/ActivityManager(  941): Display changed displayId=0
D/DotMatrix( 1327): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1622): [trimMemory] 20
I/WebViewFactory( 6858): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6858): Time to load native libraries: 9 ms (timestamps 2981-2990),
,I/LibraryLoader( 6858): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6858): Binding Chromium to main looper Looper (main, tid 1) {30d75870},
I/LibraryLoader( 6858): Expected native library version number "",actual native library version number ""
,I/chromium( 6858): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6858): Initializing chromium process, singleProcess=true,
,W/art     ( 6858): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6858): ApplicationContext is null in ApplicationStatus
,W/chromium( 6858): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6858): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 6858): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6858): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6858): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6858): Local Branch: 
I/Adreno-EGL( 6858): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6858): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6858):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  941): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  941): java.lang.Throwable: stack dump
W/System.err(  941): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  941): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  941): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55),
W/System.err(  941): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  941): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eabda52:true
,D/BluetoothAdapter( 6858): 473009052: getState(). Returning 12
,W/art     ( 6858): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6858): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6858): CordovaWebView is running on device made by: HTC
,W/art     ( 6858): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6858): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  941): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
W/chromium( 6858): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  941): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
,D/StatusBarManagerService(  941): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
,D/FindExtension( 6858): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6858): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2ee9ed2a, mServedView=org.apache.cordova.engine.SystemWebView{1858f71b VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@330da0b8
,I/InputMethodManagerService(  941): Disable input method client, pid=1622
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/StatusBarManagerService(  941): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6858): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  941): Displayed com.test.thalitest/.MainActivity: +632ms (total +677ms)
,W/BindingManager( 6858): Cannot call determinedVisibility() - never saw a connection for the pid: 6858,
,D/JsMessageQueue( 6858): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6858): JniHelper::setJavaVM(0xab2758f8), pthread_self() = -1403362304
,I/chromium( 6858): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  941): Killing 5723:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
D/Process (  941): killProcessQuiet, pid=5723
,D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 5723
,W/jxcore-log( 6858): Initializing JXcore engine,
W/jxcore-log( 6858): JXcore engine is ready
,W/jxcore-log( 6858): Starting JXcore engine,
,D/PMS     (  941): releaseHCC(18dbac1c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  941): releaseHCC(3da10025): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6858): Platform android,
W/jxcore-log( 6858): 
W/jxcore-log( 6858): Process ARCH arm
W/jxcore-log( 6858): 
,I/jxcore-log( 6858): JXcore Cordova bridge is ready!,
I/jxcore-log( 6858): 
W/jxcore-log( 6858): JXcore engine is started
,E/jxcore  ( 6858): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6858): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6858): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/Process (  941): killProcessQuiet, pid=6366
,I/ActivityManager(  941): Killing 6366:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  941): Recipient 6366
,W/PluginManager( 6858): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 241ms. Plugin should use CordovaInterface.getThreadPool().
,D/ContactMessageStore( 1567): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1567): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  941): acquireWL(2008895a): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{10024},
V/AlarmManager(  941): sending alarm PendingIntent{1318178b: PendingIntentRecord{38f09068 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142915, Int=0
D/PMS     (  941): releaseWL(2008895a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  941): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  941): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  941): acquireWL(22dd5c81): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 941 1000 null
,D/libc    (  941): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, err=8
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  941): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  941): [NET] android_getaddrinfo_proxy+
D/libc    (  941): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024,
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  941): [NET] android_getaddrinfo_proxy-, success
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  941): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  941): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  941): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  941):  [handleDownloadXtraData]inject done.
D/PMS     (  941): acquireWL(11023fbd): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 941 1000 null
D/PMS     (  941): releaseWL(22dd5c81): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/GpsLocationProvider(  941): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  941): releaseWL(11023fbd): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/PMS     (  941): acquireWL(368ee9b2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(368ee9b2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  941): updateBatteryInfo
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): battery changed pluggedType: 2
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=97
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: X
I/HtcPowerSaver(  941): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1221): status:2 level:97 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  941): acquireWL(37b9ed03): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{1c404faf: PendingIntentRecord{30036fbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=143520, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{33b30480: PendingIntentRecord{9981ab9 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453241306686, Int=0
,D/PMS     (  941): acquireWL(11fdeefe): PARTIAL_WAKE_LOCK  *backup* 0x1 941 1000 null
,W/BackupManagerService(  941): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  941): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  941): releaseWL(11fdeefe): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  941): releaseWL(37b9ed03): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/TelephonyReceiver( 1567): switchBindHtcMsgCursor: null
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1527): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1e62e83a
I/ActivityManager(  941): Killing 6575:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  941): killProcessQuiet, pid=6575
,D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  941): Recipient 6575
,D/PMS     (  941): acquireWL(1e64565f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{1c404faf: PendingIntentRecord{30036fbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=203520, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{2f83e8ac: PendingIntentRecord{d16a975 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=214212, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{3fc5fd0a: PendingIntentRecord{3a21f97b com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=195163, Int=0
,D/PMS     (  941): acquireWL(a9ce398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): releaseWL(1e64565f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  941): acquireWL(31b567f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(a9ce398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  941): releaseWL(31b567f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(38001cf3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(38001cf3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(37d08db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(37d08db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(15182429): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(370213ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(33a8d4dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(15182429): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1872): Vacuum at: now=1453241350954 tag=VacuumService,
,D/PMS     (  941): releaseWL(370213ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  941): acquireWL(3f5fbcba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1872): Using platform SSLCertificateSocketFactory
,W/Uploader( 1872): No account for auth token provided,
D/PMS     (  941): releaseWL(3f5fbcba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(1920376b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(1920376b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1872): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1872): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1872): [NET] android_getaddrinfo_proxy+
D/libc    ( 1872): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
,D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 1872): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1872): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1872): [NET] android_getaddrinfofornet-, err=8,
,W/Uploader( 1872): No account for auth token provided
,W/Uploader( 1872):  no longer exists, so no auth token.
,W/Uploader( 1872): No account for auth token provided
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1872): Explicit concurrent mark sweep GC freed 31250(1720KB) AllocSpace objects, 9(648KB) LOS objects, 47% free, 4MB/8MB, paused 1.292ms total 72.261ms
,E/Uploader( 1872): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1872): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1872): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1872): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,W/Uploader( 1872): No account for auth token provided
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1872): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1872): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1872): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1872): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1872): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1872): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1872): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1872): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,D/PMS     (  941): releaseWL(33a8d4dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(14f4a410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(14f4a410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(2a86eb09): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(2a86eb09): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(905010e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  941): releaseWL(905010e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): updateBatteryInfo
D/WifiController(  941): handleMessage: E msg.what=155652
D/PMS     (  941): runPSCheck
D/WifiController(  941): processMsg: DeviceActiveState
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: DefaultState
D/PowerUI ( 1221): closing low battery warning: level=98
D/WifiController(  941): handleMessage: X
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  941): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1337): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1337): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1337): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1337): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  941): acquireWL(3c47e72f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
,V/AlarmManager(  941): sending alarm PendingIntent{1c404faf: PendingIntentRecord{30036fbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=263520, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{382a2ec5: PendingIntentRecord{3594201a com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453241494939, Int=0
,D/PMS     (  941): releaseWL(3c47e72f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  941): acquireWL(1ff5c74b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(1ff5c74b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  941): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: E msg.what=155652
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: StaEnabledState
,D/PowerUI ( 1221): closing low battery warning: level=98
D/WifiController(  941): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: X
I/HtcPowerSaver(  941): updateStatus (8000,98,-1,false,false,false,-1)
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/HtcPowerSaver(  941): << updateStatus
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  941): Explicit concurrent mark sweep GC freed 28511(1553KB) AllocSpace objects, 9(1224KB) LOS objects, 33% free, 16MB/25MB, paused 2.806ms total 182.238ms
,W/GLSActivity( 1872): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1872): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1872): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1872): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1872): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1872): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1872): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6122): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 6122): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6122): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6122): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6122): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6122): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6122): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40,
,W/System  ( 6122): Ignoring header User-Agent because its value was null.
D/libc    ( 6122): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6122): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6122): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6122): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6122): [NET] android_getaddrinfo_proxy+
D/libc    ( 6122): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6122): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  941): acquireWL(1fcd5335): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(1fcd5335): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): Checking...
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/HtcPowerSaver(  941): >> updateStatus
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=99
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: X
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  941): updateStatus (8000,99,-1,false,false,false,-1),
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  941): acquireWL(29c4c3ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(29c4c3ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  941): updateBatteryInfo
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=99
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  941): >> updateStatus
,D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  941): updateStatus (8000,99,-1,false,false,false,-1),
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  941): acquireWL(34ab193b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(34ab193b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderNotification, total:0
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): updateBatteryInfo
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3033): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3033): Disconnected process message: 11, size: 0
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,W/ContextImpl( 6732): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 6093): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6093): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6093): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6093): Cust_ConnectToPC   : spcsc>false
D/        ( 6093): Cust_ConnectToPC   : IPT>true
D/        ( 6093): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 6093): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 6093): Index of the first 1 = -1
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 6093): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 6093): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 6093): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 6093): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 6093): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6093): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 6093): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 6093): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1567): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1567): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1567): sku_id=118
D/ContactMessageStore( 1567): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1567): start background delete task...
,D/ContactMessageStore( 1567): size: 0 , 0
,D/ContactMessageStore( 1567): Background delete complete
,I/bt-btm  ( 3033): Received oneshot timer event complete
D/PMS     (  941): acquireWL(88cedb1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{1c404faf: PendingIntentRecord{30036fbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=383519, Int=0
I/bt-btm  ( 3033): btm_ble_timeout
V/AlarmManager(  941): sending alarm PendingIntent{1c535296: PendingIntentRecord{28a80e17 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941133, Int=0
I/bt-btm  ( 3033): btm_gen_resolvable_private_addr
D/PMS     (  941): acquireWL(a33204): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3033 1002 null
,D/bt-btm  ( 3033): btm_ble_rand_enc_complete
I/bt-btm  ( 3033): btm_gen_resolve_paddr_low
D/bt-smp  ( 3033): smp_encrypt_data
W/bt-smp  ( 3033): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3033): Plain text(LSB ~ MSB) = d1 55 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3033): Encrypted text(LSB ~ MSB) = e7 ee b5 b7 88 2e e5 cb a3 4f ae 54 97 65 c3 c2 
I/bt-btm  ( 3033): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3033): Stopping oneshot timer
D/bt-btm  ( 3033): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  941): releaseWL(88cedb1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  941): releaseWL(a33204): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  941): acquireWL(31d1b3ed): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{10024},
V/AlarmManager(  941): sending alarm PendingIntent{316a0222: PendingIntentRecord{1f1574b3 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453241628343, Int=1800000,
,V/AlarmManager(  941): sending alarm PendingIntent{3b236a70: PendingIntentRecord{3b22a1e9 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936207, Int=0
,D/PMS     (  941): acquireWL(1e4a1e6e): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  941): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6931 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  941): sending alarm PendingIntent{31e8a90f: PendingIntentRecord{342cbd9c com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453241908939, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{17db06ba: PendingIntentRecord{122ab96b android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805703, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{1b7a73a5: PendingIntentRecord{7dea1de com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453242107628, Int=0
,D/PMS     (  941): acquireWL(3b10c72b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(3b10c72b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): acquireWL(39161788): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): releaseWL(1e4a1e6e): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6732): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  941): releaseWL(31d1b3ed): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6732): MY_DEBUG = false,
,I/EventLogService( 4346): Aggregate from 1453241236363 (log), 1453239828304 (data),
,D/PowerUsageService( 6732): repeat time = 1453243007714
,D/PMS     (  941): acquireWL(314725d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(3ce4f0a3): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1872 10024 WorkSource{10024 com.google.android.gms},
,I/GCM     ( 4346): Message from null null,
E/GCM     ( 4346): Dropping message from null
,D/PMS     (  941): releaseWL(39161788): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(3ce4f0a3): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms}
,D/StatusBarManagerService(  941): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
,D/StatusBarManagerService(  941): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
,D/FindExtension( 1622): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/ThreadedRenderer( 1622): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  941): Disable input method client, pid=6858,
D/StatusBarManagerService(  941): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6858): Do restartInputUnchecked, ic=null
,I/InputMethodManager( 6858): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
D/GCM     ( 1872): Message class com.google.f.a.a.i
W/IInputConnectionWrapper( 6858): reportFullscreenMode on inactive InputConnection
,D/PMS     (  941): releaseWL(314725d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,I/PowerUsageList:PowerUsageHelper( 6732): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6732): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 6955): Error opening trace file: Permission denied (13),
I/dex2oat ( 6955): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6955): dex2oat: override thread count:4
,I/dex2oat ( 6955): dex2oat took 576.441ms (threads: 4),
,I/PushClient( 6931): ApplicationMonitor {2e2317a}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
I/PushClient( 6931): ApplicationMonitor {2e2317a}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6931): ApplicationMonitor {2e2317a}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6931): ApplicationMonitor {2e2317a}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6931): ApplicationMonitor {2e2317a}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6931): ApplicationMonitor {2e2317a}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6931): ApplicationMonitor {2e2317a}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6931): ApplicationMonitor {2e2317a}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6931): ApplicationMonitor {2e2317a}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6931): PnsModel {304a29a5}: update(): Update registration caused by: alarm,
,I/PushClient( 6931): PnsConfigModel {969bda0}: <init>(): Use dm-client for provisioning.
,W/System.err( 6931): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6931): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6931): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6931): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  941): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6963 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6963): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6963 dbg=false s=true,
,I/DeviceManagement( 6963): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6963): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6963): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6963): WorkflowService: Starting workflow service
,I/DeviceManagement( 6963): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1c318b9c] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6963): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6963): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6963): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6963): SessionStateController: Checking invariants...
,I/DeviceManagement( 6963): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6963): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6963): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6963): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1c318b9c],
,I/DeviceManagement( 6963): WorkflowService: Stopping workflow service
,I/ActivityManager(  941): Killing 6531:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  941): killProcessQuiet, pid=6531,
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6531
,I/PushClient( 6931): PnsModel {304a29a5}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  941): killProcessQuiet, pid=6602,
I/ActivityManager(  941): Killing 6602:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6602
,D/PMS     (  941): acquireWL(71663f7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{1c404faf: PendingIntentRecord{30036fbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=983520, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{1f080264: PendingIntentRecord{247baccd com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453242149477, Int=0
,D/SmartSyncUtils( 6732): isEpsOn(), nState = 0
,D/PMS     (  941): acquireWL(2add3982): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6732 1000 null
,D/PMS     (  941): releaseWL(71663f7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/SmartSyncScreenOnOffTimeReceiver( 6732): [updateNmRange] bManual = false,
,D/WeatherUtility( 1221): Weather sync is On
D/SmartSyncScreenOnOffTimeReceiver( 6732): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 6732): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6732): SettingOnTime = 1453269600000, randomSettingOnTime = 1453269092000,
D/SmartSyncScreenOnOffTimeReceiver( 6732): SettingOffTime = 1453248000000, randomSettingOffTime = 1453248394000
D/SmartSyncScreenOnOffTimeReceiver( 6732): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6732): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6732): bNightModeTurnOffOnce = false,
,D/PMS     (  941): releaseWL(2add3982): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  941): acquireWL(24434893): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(24434893): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  941): updateBatteryInfo
,D/PowerUI ( 1221): closing low battery warning: level=100
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PMS     (  941): runPSCheck
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  941): >> updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): handleMessage: E msg.what=155652
,D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  941): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
