#### Test 56672827b6f75d5_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,E/cutils-trace( 6583): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6583): ====startRecUseTime====
D/htc.customization.log.level( 6583):  is 
W/CustomizationLogLevel( 6583): Level value is invalid, use default level 2
D/CustomizationManager( 6583):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6583): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6583): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6583): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6583): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6583): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6583): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6583): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6583): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6583): Parsing tag category name = system
I/CustomizationCIDLoader( 6583): Parsing tag category name = application
I/CustomizationCIDLoader( 6583): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6583): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6583): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6583): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6583): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6583): add string-array item, value = 42507
I/CustomizationCIDLoader( 6583): add string-array item, value = 21902
I/CustomizationCIDLoader( 6583): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6583): add string-array item, value = 23420
I/CustomizationCIDLoader( 6583): add string-array item, value = 22299
I/CustomizationCIDLoader( 6583): add string-array item, value = 24002
I/CustomizationCIDLoader( 6583): add string-array item, value = 23210
I/CustomizationCIDLoader( 6583): add string-array item, value = 23205
I/CustomizationCIDLoader( 6583): add string-array item, value = 23806
I/CustomizationCIDLoader( 6583): add string-array item, value = 23430
I/CustomizationCIDLoader( 6583): add string-array item, value = 23408
I/CustomizationCIDLoader( 6583): add string-array item, value = 27205
I/CustomizationCIDLoader( 6583): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6583): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6583):  Read CID file spent 0.101 (s)
D/CustomizationManager( 6583):  All configurations done spent 0.101 (s)
--------- beginning of system
I/ActivityManager(  941): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6583 on display 0
D/PMS     (  941): acquireHCC(3a8574a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 941 1000 null
D/PMS     (  941): acquireHCC(2681e6bb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 941 1000 null
W/asset   (  941): Copying FileAsset 0x5585bb6870 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  941): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6601 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  941): Display changed displayId=0
D/DotMatrix( 1308): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1308): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6601): Copying FileAsset 0xac5c6470 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1478): [trimMemory] 20
I/WebViewFactory( 6601): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6601): Time to load native libraries: 9 ms (timestamps 920-929)
I/LibraryLoader( 6601): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6601): Binding Chromium to main looper Looper (main, tid 1) {3096f150}
I/LibraryLoader( 6601): Expected native library version number "",actual native library version number ""
I/chromium( 6601): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6601): Initializing chromium process, singleProcess=true
W/art     ( 6601): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6601): ApplicationContext is null in ApplicationStatus
W/chromium( 6601): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6601): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6601): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6601): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6601): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6601): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6601): Local Branch: 
I/Adreno-EGL( 6601): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6601): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6601):                  d74aa161a12b9c6fc6332151
W/System.err(  941): java.lang.Throwable: stack dump
D/BluetoothManagerService(  941): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  941): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@330dfe8f:true
W/System.err(  941): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  941): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  941): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  941): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6601): 973197948: getState(). Returning 12
W/art     ( 6601): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6601): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6601): CordovaWebView is running on device made by: HTC
W/art     ( 6601): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6601): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6601): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/HtcSystemUPManager(  941): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/StatusBarManagerService(  941): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
D/StatusBarManagerService(  941): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
D/FindExtension( 6601): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6601): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3c1f70a, mServedView=org.apache.cordova.engine.SystemWebView{e976b7b VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@355a6d98
I/InputMethodManagerService(  941): Disable input method client, pid=1478
D/StatusBarManagerService(  941): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
W/IInputConnectionWrapper( 6601): reportFullscreenMode on inactive InputConnection
I/ActivityManager(  941): Displayed com.test.thalitest/.MainActivity: +667ms (total +713ms)
W/BindingManager( 6601): Cannot call determinedVisibility() - never saw a connection for the pid: 6601
D/JsMessageQueue( 6601): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6601): JniHelper::setJavaVM(0xab45a8f8), pthread_self() = -1401447296
I/chromium( 6601): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6601): Initializing JXcore engine,
W/jxcore-log( 6601): JXcore engine is ready
,W/jxcore-log( 6601): Starting JXcore engine,
,D/PMS     (  941): releaseHCC(3a8574a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  941): releaseHCC(2681e6bb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6601): Platform android,
W/jxcore-log( 6601): 
W/jxcore-log( 6601): Process ARCH arm
W/jxcore-log( 6601): 
,I/jxcore-log( 6601): JXcore Cordova bridge is ready!
I/jxcore-log( 6601): 
W/jxcore-log( 6601): JXcore engine is started
,E/jxcore  ( 6601): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6601): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6601): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/Process (  941): killProcessQuiet, pid=6118
I/ActivityManager(  941): Killing 6118:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  941): Recipient 6118
,W/PluginManager( 6601): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 144ms. Plugin should use CordovaInterface.getThreadPool().
,D/PMS     (  941): acquireWL(3d8ab238): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{1a9a1e73: PendingIntentRecord{8d83130 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=123700, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{5ab2211: PendingIntentRecord{3864df76 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142834, Int=0
,D/PMS     (  941): releaseWL(3d8ab238): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1216): Weather sync is On
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  941): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  941): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  941): acquireWL(a4d4977): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 941 1000 null
,D/libc    (  941): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, err=8
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024,
D/libc    (  941): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  941): [NET] android_getaddrinfo_proxy+
D/libc    (  941): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  941): [NET] android_getaddrinfo_proxy-, success
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233392e),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS,
,D/GpsLocationProvider(  941): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  941): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  941): acquireWL(37c30613): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 941 1000 null
D/GpsLocationProvider(  941): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  941): releaseWL(a4d4977): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  941):  [handleDownloadXtraData]inject done.
D/PMS     (  941): releaseWL(37c30613): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  941): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/ContactMessageStore( 1432): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1432): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  941): acquireWL(2f959050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(2f959050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): updateBatteryInfo
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
D/PMS     (  941): runPSCheck
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,D/PowerUI ( 1216): closing low battery warning: level=100
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1432): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1569): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2b8cb94b
,I/ActivityManager(  941): Killing 6326:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  941): killProcessQuiet, pid=6326
,D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6326
,D/PMS     (  941): acquireWL(2870249): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{18cdf06f: PendingIntentRecord{33cb617c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453394751483, Int=0
D/PMS     (  941): acquireWL(3a4674e): PARTIAL_WAKE_LOCK  *backup* 0x1 941 1000 null
V/AlarmManager(  941): sending alarm PendingIntent{1a9a1e73: PendingIntentRecord{8d83130 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=183700, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{27347a05: PendingIntentRecord{1363aa5a android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=211967, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{3af3248b: PendingIntentRecord{3d2b1968 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=188630, Int=0
W/BackupManagerService(  941): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  941): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  941): releaseWL(3a4674e): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  941): acquireWL(3b87b181): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(2870249): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1216): Weather sync is On,
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/PMS     (  941): acquireWL(3ba21226): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): releaseWL(3b87b181): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  941): releaseWL(3ba21226): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(195ad80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(195ad80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(38980fb9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(f9f3ffe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(36821ac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(38980fb9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(4ab5e0a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(4ab5e0a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1866): Vacuum at: now=1453394788551 tag=VacuumService
,I/GoogleURLConnFactory( 1866): Using platform SSLCertificateSocketFactory
D/PMS     (  941): releaseWL(f9f3ffe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(395a467b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(395a467b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  941): acquireWL(2b0bac98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(2b0bac98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1866): No account for auth token provided
,D/libc    ( 1866): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1866): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1866): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1866): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1866): [NET] android_getaddrinfo_proxy+
D/libc    ( 1866): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1866): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1866): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1866): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1866): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1866): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1866): No account for auth token provided,
,W/Uploader( 1866): No account for auth token provided,
,W/Uploader( 1866): No account for auth token provided,
,W/Uploader( 1866):  no longer exists, so no auth token.
,W/Uploader( 1866): No account for auth token provided,
,W/Uploader( 1866): No account for auth token provided
,D/PMS     (  941): releaseWL(36821ac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): acquireWL(185afa44): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(185afa44): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): acquireWL(2b95772d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(2b95772d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  941): acquireWL(32c1a462): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(32c1a462): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PMS     (  941): runPSCheck
D/WifiController(  941): handleMessage: E msg.what=155652
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1216): closing low battery warning: level=100
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
D/PMS     (  941): acquireWL(225509f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
D/UsbnetService(  941): BroadcastReceiver::onReceive+
I/BatteryService(  941): n_update end
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PMS     (  941): releaseWL(225509f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  941): runPSCheck
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  941): Checking...
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: DeviceActiveState
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: DefaultState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): handleMessage: X
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1364): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 1364): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1364): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  941): acquireWL(2c2f76b0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{1a9a1e73: PendingIntentRecord{8d83130 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=243700, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{3c19a4ae: PendingIntentRecord{33ac524f com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453394918180, Int=0
,D/PMS     (  941): releaseWL(2c2f76b0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1216): Weather sync is On
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1866): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1866): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1866): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1866): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1866): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1866): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1866): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1866): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1866): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1866): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1866): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5856): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5856): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5856): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5856): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5856): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5856): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5856): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1216): reapply : com.google.android.gms 2 40
,W/System  ( 5856): Ignoring header User-Agent because its value was null.
,D/libc    ( 5856): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5856): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5856): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5856): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5856): [NET] android_getaddrinfo_proxy+
D/libc    ( 5856): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5856): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  941): acquireWL(1043de99): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(1043de99): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  941): updateBatteryInfo
D/PowerUI ( 1216): closing low battery warning: level=100
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
,D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  941): acquireWL(1e0e955e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(1e0e955e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): Checking...
,D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: X
D/PowerUI ( 1216): closing low battery warning: level=100
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1432): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1432): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1432): sku_id=118
D/ContactMessageStore( 1432): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1432): start background delete task...
,D/ContactMessageStore( 1432): size: 0 , 0,
D/ContactMessageStore( 1432): Background delete complete
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  941): acquireWL(226c6d3f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  941): n_update end
,D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  941): releaseWL(226c6d3f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  941): updateBatteryInfo
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: DefaultState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): handleMessage: X
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  941): acquireWL(2f2de60c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(2f2de60c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PMS     (  941): runPSCheck
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1216): closing low battery warning: level=100
D/WifiController(  941): handleMessage: E msg.what=155652
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: StaEnabledState
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  941): acquireWL(beacb55): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{1a9a1e73: PendingIntentRecord{8d83130 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=363700, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{b449e5b: PendingIntentRecord{9d956f8 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941924, Int=0
,I/bt-btm  ( 3161): Received oneshot timer event complete
D/PMS     (  941): acquireWL(25d9c7d1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3161 1002 null
I/bt-btm  ( 3161): btm_ble_timeout
I/bt-btm  ( 3161): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3161): btm_ble_rand_enc_complete
,D/PMS     (  941): releaseWL(beacb55): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/bt-btm  ( 3161): btm_gen_resolve_paddr_low
D/bt-smp  ( 3161): smp_encrypt_data
W/bt-smp  ( 3161): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3161): Plain text(LSB ~ MSB) = 94 4e 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3161): Encrypted text(LSB ~ MSB) = f0 02 f4 30 07 85 83 13 42 f4 9f be 19 19 dd 59 
I/bt-btm  ( 3161): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3161): Stopping oneshot timer
D/bt-btm  ( 3161): Starting oneshot timer type:103 timeout:900s
D/WeatherUtility( 1216): Weather sync is On
,W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/PMS     (  941): releaseWL(25d9c7d1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  941): acquireWL(1541f236): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{361c7674: PendingIntentRecord{7edf79d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805320, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{1a9a1e73: PendingIntentRecord{8d83130 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=963700, Int=0,
,V/AlarmManager(  941): sending alarm PendingIntent{29c8eaa4: PendingIntentRecord{20e2100d com.android.vending startService}}, i=null, t=0, cnt=1, w=1453395253160, Int=0,
,D/Finsky  ( 5856): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,V/AlarmManager(  941): sending alarm PendingIntent{1832fbc2: PendingIntentRecord{10767dd3 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937080, Int=0
,I/ActivityManager(  941): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6671 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  941): sending alarm PendingIntent{21aca009: PendingIntentRecord{3f39120e com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453395499300, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{13a1242f: PendingIntentRecord{19a3604 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453395543525, Int=0
,D/PMS     (  941): acquireWL(2025d44b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(2025d44b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 6407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  941): releaseWL(1541f236): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6407): MY_DEBUG = false
D/WeatherUtility( 1216): Weather sync is On
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
D/PowerUsageService( 6407): repeat time = 1453396443615
,I/art     ( 1866): Explicit concurrent mark sweep GC freed 34338(1865KB) AllocSpace objects, 11(880KB) LOS objects, 47% free, 4MB/8MB, paused 943us total 72.505ms,
,D/StatusBarManagerService(  941): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
,D/StatusBarManagerService(  941): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
,D/FindExtension( 1478): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1478): Defer allocateBuffers to drawing time
,I/GLSUser ( 1866): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1866): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1866): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1866): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/InputMethodManagerService(  941): Disable input method client, pid=6601,
D/StatusBarManagerService(  941): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1216): setImeWindowStatus(false,false),
,W/IInputConnectionWrapper( 6601): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6601): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6601): reportFullscreenMode on inactive InputConnection
V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 6407): PowerProfile::POWER_SCREEN_FULL = 154.8,
,W/Finsky  ( 5856): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/cutils-trace( 6694): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6694): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6694): dex2oat: override thread count:4
V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerUsageList:BatterySipperExt( 6407): gen(), null == sipper.uidObj, userId = 0
,I/GLSUser ( 1866): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1866): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1866): [GLSUser] Extracting token using key: Auth
D/PMS     (  941): acquireWL(1906c396): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
W/GLSActivity( 1866): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/GCM     ( 1866): Message class com.google.f.a.a.i
V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  941): releaseWL(1906c396): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  941): Explicit concurrent mark sweep GC freed 26330(1443KB) AllocSpace objects, 7(784KB) LOS objects, 33% free, 16MB/25MB, paused 1.652ms total 182.821ms
,I/GLSUser ( 1866): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1866): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1866): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1866): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5856): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,I/dex2oat ( 6694): dex2oat took 663.546ms (threads: 4)
,I/PushClient( 6671): ApplicationMonitor {21b2035a}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6671): ApplicationMonitor {21b2035a}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6671): ApplicationMonitor {21b2035a}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6671): ApplicationMonitor {21b2035a}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6671): ApplicationMonitor {21b2035a}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6671): ApplicationMonitor {21b2035a}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6671): ApplicationMonitor {21b2035a}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6671): ApplicationMonitor {21b2035a}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6671): ApplicationMonitor {21b2035a}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6671): PnsModel {8d09705}: update(): Update registration caused by: alarm,
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/PushClient( 6671): PnsConfigModel {2a314e80}: <init>(): Use dm-client for provisioning.,
,I/GLSUser ( 1866): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1866): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1866): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1866): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
W/System.err( 6671): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 6671): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6671): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/Finsky  ( 5856): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 5856): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,W/ContextImpl( 6671): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  941): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6702 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,D/Finsky  ( 5856): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5856): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2),
,D/DeviceConnectionService( 1810): client connected with version: 7571000
,I/DeviceManagement( 6702): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6702 dbg=false s=true,
,I/DeviceManagement( 6702): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6702): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6702): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6702): WorkflowService: Starting workflow service
,I/DeviceManagement( 6702): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@8d09705] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6702): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6702): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6702): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6702): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6702): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6702): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6702): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6702): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@8d09705],
,I/DeviceManagement( 6702): WorkflowService: Stopping workflow service
,D/Process (  941): killProcessQuiet, pid=6352
I/ActivityManager(  941): Killing 6352:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6352
,I/PushClient( 6671): PnsModel {8d09705}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  941): killProcessQuiet, pid=6282
I/ActivityManager(  941): Killing 6282:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6282
,D/PMS     (  941): acquireWL(547b593): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{10072}
V/AlarmManager(  941): sending alarm PendingIntent{1b8d49d0: PendingIntentRecord{2e85fdc9 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453395559108, Int=0
D/PMS     (  941): releaseWL(547b593): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 5856): [592] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5856): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  941): acquireWL(34d67cce): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{2eae17ef: PendingIntentRecord{1d4532fc com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453395589405, Int=0
,D/SmartSyncUtils( 6407): isEpsOn(), nState = 0
,D/PMS     (  941): releaseWL(34d67cce): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  941): acquireWL(36e7ad85): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6407 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6407): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6407): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6407): AlarmOnTime = -1,
,D/SmartSyncScreenOnOffTimeReceiver( 6407): SettingOnTime = 1453442400000, randomSettingOnTime = 1453440233000
D/SmartSyncScreenOnOffTimeReceiver( 6407): SettingOffTime = 1453420800000, randomSettingOffTime = 1453424148000
,D/SmartSyncScreenOnOffTimeReceiver( 6407): bDayMode = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6407): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6407): bNightModeTurnOffOnce = false
,D/PMS     (  941): releaseWL(36e7ad85): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  941): acquireWL(316197da): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  941): releaseWL(316197da): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1216): closing low battery warning: level=100
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  941): battery changed pluggedType: 2
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PMS     (  941): runPSCheck
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  941): acquireWL(f6e440b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(f6e440b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/NotificationService(  941): plugged=true pluggin=true,
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: E msg.what=155652
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: StaEnabledState
,D/PowerUI ( 1216): closing low battery warning: level=100
D/WifiController(  941): processMsg: DefaultState
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: X
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  941): << updateStatus
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  941): acquireWL(163082e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(163082e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PMS     (  941): runPSCheck
D/WifiController(  941): handleMessage: E msg.what=155652
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1216): closing low battery warning: level=100
,D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  941): User[0] Flushing usage stats to disk
,D/PMS     (  941): acquireWL(21fa9d01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(21fa9d01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  941): updateBatteryInfo,
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3161): Disconnected process message: 10, size: 0
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
,D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: DefaultState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): handleMessage: X
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms)
```
