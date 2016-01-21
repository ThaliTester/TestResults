#### Test 56672827039a409_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6693): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6693): ====startRecUseTime====
D/htc.customization.log.level( 6693):  is 
W/CustomizationLogLevel( 6693): Level value is invalid, use default level 2
D/CustomizationManager( 6693):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 6693): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6693): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6693): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6693): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6693): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6693): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6693): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6693): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6693): Parsing tag category name = system
I/CustomizationCIDLoader( 6693): Parsing tag category name = application
I/CustomizationCIDLoader( 6693): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6693): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6693): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6693): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6693): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6693): add string-array item, value = 42507
I/CustomizationCIDLoader( 6693): add string-array item, value = 21902
I/CustomizationCIDLoader( 6693): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6693): add string-array item, value = 23420
I/CustomizationCIDLoader( 6693): add string-array item, value = 22299
I/CustomizationCIDLoader( 6693): add string-array item, value = 24002
I/CustomizationCIDLoader( 6693): add string-array item, value = 23210
I/CustomizationCIDLoader( 6693): add string-array item, value = 23205
I/CustomizationCIDLoader( 6693): add string-array item, value = 23806
I/CustomizationCIDLoader( 6693): add string-array item, value = 23430
I/CustomizationCIDLoader( 6693): add string-array item, value = 23408
I/CustomizationCIDLoader( 6693): add string-array item, value = 27205
I/CustomizationCIDLoader( 6693): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6693): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6693):  Read CID file spent 0.105 (s)
D/CustomizationManager( 6693):  All configurations done spent 0.105 (s)
--------- beginning of system
I/ActivityManager(  956): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6693 on display 0
D/PMS     (  956): acquireHCC(1be6fcd6): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 956 1000 null
D/PMS     (  956): acquireHCC(25e70b57): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 956 1000 null
I/ActivityManager(  956): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6711 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1310): [EventService]  onDisplayChanged: 0
V/ActivityManager(  956): Display changed displayId=0
D/DotMatrix( 1310): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1488): [trimMemory] 20
I/WebViewFactory( 6711): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6711): Time to load native libraries: 9 ms (timestamps 9929-9938)
,I/LibraryLoader( 6711): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6711): Binding Chromium to main looper Looper (main, tid 1) {1629e497}
,I/LibraryLoader( 6711): Expected native library version number "",actual native library version number ""
,I/chromium( 6711): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6711): Initializing chromium process, singleProcess=true
,W/art     ( 6711): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6711): ApplicationContext is null in ApplicationStatus
,W/chromium( 6711): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6711): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6711): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6711): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6711): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6711): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6711): Local Branch: 
I/Adreno-EGL( 6711): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6711): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6711):                  d74aa161a12b9c6fc6332151
,W/System.err(  956): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  956): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  956): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@375b406b:true
W/System.err(  956): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  956): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  956): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  956): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6711): 354300723: getState(). Returning 12
,W/art     ( 6711): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6711): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6711): CordovaWebView is running on device made by: HTC
,W/art     ( 6711): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6711): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6711): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/HtcSystemUPManager(  956): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  956): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  956): hiding MENU key
,D/StatusBarManagerService(  956): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  956): hiding MENU key
,D/FindExtension( 6711): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6711): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2a2799d9, mServedView=org.apache.cordova.engine.SystemWebView{1a92cf9e VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3df8ba7f
,I/InputMethodManagerService(  956): Disable input method client, pid=1488
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/StatusBarManagerService(  956): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6711): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  956): Displayed com.test.thalitest/.MainActivity: +648ms (total +693ms)
,W/BindingManager( 6711): Cannot call determinedVisibility() - never saw a connection for the pid: 6711
,D/JsMessageQueue( 6711): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6711): JniHelper::setJavaVM(0xab5628f8), pthread_self() = -1400220896
,I/chromium( 6711): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Process (  956): killProcessQuiet, pid=5594
I/ActivityManager(  956): Killing 5594:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 5594
,W/jxcore-log( 6711): Initializing JXcore engine
W/jxcore-log( 6711): JXcore engine is ready
,W/jxcore-log( 6711): Starting JXcore engine
,D/PMS     (  956): releaseHCC(1be6fcd6): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  956): releaseHCC(25e70b57): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6711): Platform android
W/jxcore-log( 6711): 
W/jxcore-log( 6711): Process ARCH arm
W/jxcore-log( 6711): 
,I/jxcore-log( 6711): JXcore Cordova bridge is ready!
I/jxcore-log( 6711): 
W/jxcore-log( 6711): JXcore engine is started
,E/jxcore  ( 6711): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6711): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6711): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/Process (  956): killProcessQuiet, pid=6228
I/ActivityManager(  956): Killing 6228:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  956): Recipient 6228
,W/PluginManager( 6711): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 130ms. Plugin should use CordovaInterface.getThreadPool().
,D/PMS     (  956): acquireWL(74276a4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000}
V/AlarmManager(  956): sending alarm PendingIntent{25d7bf6f: PendingIntentRecord{180a847c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=133261, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{3e4aac0d: PendingIntentRecord{254567c2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142940, Int=0
,D/PMS     (  956): releaseWL(74276a4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  956): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  956): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  956): acquireWL(63679d3): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 956 1000 null
,D/libc    (  956): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  956): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  956): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  956): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  956): [NET] android_getaddrinfo_proxy+,
D/libc    (  956): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  956): [NET] android_getaddrinfo_proxy-, success
D/libc    (  956): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  956): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  956): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  956): [reportHTCStatus] eventMask = 3 , status = 0
D/PMS     (  956): acquireWL(b64e02f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 956 1000 null
D/GpsLocationProvider(  956): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/PMS     (  956): releaseWL(63679d3): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  956):  [handleDownloadXtraData]inject done.
D/PMS     (  956): releaseWL(b64e02f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  956): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/ContactMessageStore( 1435): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1435): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  956): acquireWL(299bf63c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
D/UsbnetService(  956): BroadcastReceiver::onReceive+
I/BatteryService(  956): n_update end
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  956): releaseWL(299bf63c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  956): plugged=true pluggin=true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  956): runPSCheck
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): handleMessage: E msg.what=155652
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  956): Checking...
D/WifiController(  956): processMsg: DeviceActiveState
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): processMsg: StaEnabledState
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
,I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,W/ContextImpl(  956): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/TelephonyReceiver( 1435): switchBindHtcMsgCursor: null
,D/PMS     (  956): acquireWL(2ad64fc5): PARTIAL_WAKE_LOCK  *alarm* 0x1 956 1000 WorkSource{1000}
D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,V/AlarmManager(  956): sending alarm PendingIntent{ec2d1a: PendingIntentRecord{1669504b android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453396601243, Int=0
D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/PMS     (  956): acquireWL(6503a28): PARTIAL_WAKE_LOCK  *backup* 0x1 956 1000 null
D/HtcAppUPService( 1580): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@32f419ae
V/AlarmManager(  956): sending alarm PendingIntent{25d7bf6f: PendingIntentRecord{180a847c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=193261, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{4d12341: PendingIntentRecord{b1000e6 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=211168, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{2dfaa627: PendingIntentRecord{1b82d0d4 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191239, Int=0
I/ActivityManager(  956): Killing 6434:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  956): killProcessQuiet, pid=6434
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/BackupManagerService(  956): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  956): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  956): releaseWL(6503a28): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,I/ActivityManager(  956): Recipient 6434
,D/PMS     (  956): acquireWL(2a4bb27d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  956): releaseWL(2ad64fc5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  956): acquireWL(1c4b4572): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(2a4bb27d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1898): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  956): releaseWL(1c4b4572): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(3fe7666c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(3fe7666c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(1a43b435): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  956): releaseWL(1a43b435): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  956): acquireWL(25ba10ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(792e23b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  956): acquireWL(2a885eb1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  956): releaseWL(25ba10ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
I/VacuumService( 1898): Vacuum at: now=1453396638394 tag=VacuumService,
,I/GoogleURLConnFactory( 1898): Using platform SSLCertificateSocketFactory
,D/PMS     (  956): releaseWL(792e23b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  956): acquireWL(1cc36717): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1898): No account for auth token provided,
,D/PMS     (  956): releaseWL(1cc36717): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  956): acquireWL(1b661704): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(1b661704): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1898): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1898): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1898): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1898): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1898): [NET] android_getaddrinfo_proxy+,
D/libc    ( 1898): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1898): [NET] android_getaddrinfo_proxy-, success,
,D/libc    ( 1898): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1898): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1898): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1898): [NET] android_getaddrinfofornet-, err=8,
,W/Uploader( 1898): No account for auth token provided,
,W/Uploader( 1898): No account for auth token provided
,W/Uploader( 1898):  no longer exists, so no auth token.
,W/Uploader( 1898): No account for auth token provided
,I/GLSUser ( 1898): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1898): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1898): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1898): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1898): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1898): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1898): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1898): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1898): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1898): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1898): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1898): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1898): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1898): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1898): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1898): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1898): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1898): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 2 40,
,D/PMS     (  956): releaseWL(2a885eb1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  956): acquireWL(8fd5621): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(8fd5621): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(2a1ea46): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(2a1ea46): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1351): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  956): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,D/wpa_supplicant( 1351): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  956): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  956): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48
,D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  956): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  956): acquireWL(2c764407): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(2c764407): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  956): runPSCheck
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  956): Checking...
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): processMsg: DeviceActiveState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  956): processMsg: StaEnabledState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): handleMessage: X
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1898): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1898): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1898): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1898): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1898): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1898): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1898): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1898): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1898): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1898): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1898): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1898): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1898): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5943): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5943): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5943): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5943): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5943): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5943): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5943): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,W/System  ( 5943): Ignoring header User-Agent because its value was null.
,D/libc    ( 5943): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5943): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5943): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5943): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5943): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5943): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5943): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  956): acquireWL(19170991): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000}
V/AlarmManager(  956): sending alarm PendingIntent{25d7bf6f: PendingIntentRecord{180a847c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=253262, Int=0
,V/AlarmManager(  956): sending alarm PendingIntent{29d23cf7: PendingIntentRecord{3b216764 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453396767675, Int=0
,I/ActivityManager(  956): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6775 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  956): sending alarm PendingIntent{3611adcd: PendingIntentRecord{2209a682 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453396839641, Int=0
,D/PMS     (  956): releaseWL(19170991): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data,
,D/StatusBarManagerService(  956): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  956): hiding MENU key
,D/StatusBarManagerService(  956): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  956): hiding MENU key
,D/FindExtension( 1488): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1488): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  956): Disable input method client, pid=6711
,I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/StatusBarManagerService(  956): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 6711): Do restartInputUnchecked, ic=null
,I/InputMethodManager( 6711): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6711): reportFullscreenMode on inactive InputConnection
,E/cutils-trace( 6797): Error opening trace file: Permission denied (13),
I/dex2oat ( 6797): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6797): dex2oat: override thread count:4
,I/dex2oat ( 6797): dex2oat took 683.495ms (threads: 4)
,I/PushClient( 6775): ApplicationMonitor {3451c469}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6775): ApplicationMonitor {3451c469}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6775): ApplicationMonitor {3451c469}: logBasicAppInfo(): VersionName:             1.2.853019,
I/PushClient( 6775): ApplicationMonitor {3451c469}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6775): ApplicationMonitor {3451c469}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6775): ApplicationMonitor {3451c469}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6775): ApplicationMonitor {3451c469}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6775): ApplicationMonitor {3451c469}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6775): ApplicationMonitor {3451c469}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6775): PnsModel {3de786f0}: update(): Update registration caused by: alarm
,I/PushClient( 6775): PnsConfigModel {29372187}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6775): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6775): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6775): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6775): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  956): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6805 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6805): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6805 dbg=false s=true,
,I/DeviceManagement( 6805): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6805): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6805): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6805): WorkflowService: Starting workflow service
,I/DeviceManagement( 6805): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3de786f0] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6805): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6805): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6805): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6805): SessionStateController: Checking invariants...
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/DeviceManagement( 6805): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6805): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6805): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6805): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3de786f0]
,I/DeviceManagement( 6805): WorkflowService: Stopping workflow service
,D/Process (  956): killProcessQuiet, pid=6389,
I/ActivityManager(  956): Killing 6389:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6775): PnsModel {3de786f0}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  956): Recipient 6389
,D/Process (  956): killProcessQuiet, pid=6461,
I/ActivityManager(  956): Killing 6461:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 6461,
,D/PMS     (  956): acquireWL(f5651e7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(f5651e7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  956): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  956): battery changed pluggedType: 2
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/PMS     (  956): runPSCheck
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  956): Checking...
D/UsbnetService(  956): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): processMsg: DeviceActiveState
D/WifiController(  956): processMsg: StaEnabledState
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
,I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1435): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1435): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1435): sku_id=118
D/ContactMessageStore( 1435): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1435): start background delete task...
,D/ContactMessageStore( 1435): size: 0 , 0,
D/ContactMessageStore( 1435): Background delete complete
,D/PMS     (  956): acquireWL(145f7194): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000}
V/AlarmManager(  956): sending alarm PendingIntent{25d7bf6f: PendingIntentRecord{180a847c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=433262, Int=0,
V/AlarmManager(  956): sending alarm PendingIntent{2db6a43d: PendingIntentRecord{20fcb432 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941321, Int=0
,I/bt-btm  ( 3116): Received oneshot timer event complete
,I/bt-btm  ( 3116): btm_ble_timeout,
D/PMS     (  956): acquireWL(1b2c2583): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3116 1002 null
I/bt-btm  ( 3116): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3116): btm_ble_rand_enc_complete,
I/bt-btm  ( 3116): btm_gen_resolve_paddr_low
D/bt-smp  ( 3116): smp_encrypt_data
W/bt-smp  ( 3116): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3116): Plain text(LSB ~ MSB) = 7f c1 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3116): Encrypted text(LSB ~ MSB) = 29 4c e4 b7 94 fc 2b 1a dc 62 34 da 62 07 64 c0 
I/bt-btm  ( 3116): btm_gen_resolve_paddr_cmpl,
W/bt-btm  ( 3116): Stopping oneshot timer
D/bt-btm  ( 3116): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1223): Weather sync is On
D/PMS     (  956): releaseWL(145f7194): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  956): acquireWL(b8c1300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null,
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(b8c1300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  956): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/PMS     (  956): runPSCheck
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  956): Checking...
D/UsbnetService(  956): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): handleMessage: E msg.what=155652
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  956): processMsg: DeviceActiveState
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): processMsg: StaEnabledState
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
,I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  956): releaseWL(1b2c2583): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  956): acquireWL(a6e4739): PARTIAL_WAKE_LOCK  *alarm* 0x1 956 1000 WorkSource{10024}
V/AlarmManager(  956): sending alarm PendingIntent{19bde17e: PendingIntentRecord{360196df com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936706, Int=0
,V/AlarmManager(  956): sending alarm PendingIntent{1e6b4688: PendingIntentRecord{385aa821 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805014, Int=0,
V/AlarmManager(  956): sending alarm PendingIntent{a1f5f2c: PendingIntentRecord{19aea335 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453397394501, Int=0
D/PMS     (  956): acquireWL(26631df5): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(26631df5): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6515): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  956): releaseWL(a6e4739): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6515): MY_DEBUG = false
,D/PowerUsageService( 6515): repeat time = 1453398294538
,I/PowerUsageList:PowerUsageHelper( 6515): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6515): gen(), null == sipper.uidObj, userId = 0,
,I/art     (  956): Explicit concurrent mark sweep GC freed 26061(1429KB) AllocSpace objects, 8(868KB) LOS objects, 33% free, 16MB/25MB, paused 1.626ms total 160.276ms,
D/GCM     ( 1898): Message class com.google.f.a.a.i
D/PMS     (  956): acquireWL(1192c1fb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(1192c1fb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(35b94218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null,
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(35b94218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  956): updateBatteryInfo
D/PMS     (  956): runPSCheck
D/HtcPowerSaver(  956): Checking...
I/HtcPowerSaver(  956): >> updateStatus
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): << updateStatus
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  956): plugged=true pluggin=true
,D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/WifiController(  956): battery changed pluggedType: 2
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): processMsg: DeviceActiveState
D/WifiController(  956): processMsg: StaEnabledState
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  956): acquireWL(894a471): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000}
V/AlarmManager(  956): sending alarm PendingIntent{25d7bf6f: PendingIntentRecord{180a847c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=973262, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{11caa256: PendingIntentRecord{354182d7 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453397439919, Int=0
,D/SmartSyncUtils( 6515): isEpsOn(), nState = 0
,D/PMS     (  956): acquireWL(2c0c67c4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6515 1000 null
,D/PMS     (  956): releaseWL(894a471): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6515): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6515): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6515): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6515): SettingOnTime = 1453442400000, randomSettingOnTime = 1453441845000
D/SmartSyncScreenOnOffTimeReceiver( 6515): SettingOffTime = 1453420800000, randomSettingOffTime = 1453423734000,
D/SmartSyncScreenOnOffTimeReceiver( 6515): bDayMode = false
,D/WeatherUtility( 1223): Weather sync is On
D/SmartSyncScreenOnOffTimeReceiver( 6515): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6515): bNightModeTurnOffOnce = false
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  956): releaseWL(2c0c67c4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  956): User[0] Flushing usage stats to disk,
,TIME-OUT KILL (timeout was 1200000ms)
```
