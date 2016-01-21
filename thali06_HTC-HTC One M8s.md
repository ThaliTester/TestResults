#### Test 56449660311ec66_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6949): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6949): ====startRecUseTime====
D/htc.customization.log.level( 6949):  is 
W/CustomizationLogLevel( 6949): Level value is invalid, use default level 2
D/CustomizationManager( 6949):  Read ACC file spent 0.031 (s)
D/CIDMapFileReader( 6949): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6949): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6949): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6949): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6949): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6949): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6949): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6949): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6949): Parsing tag category name = system
I/CustomizationCIDLoader( 6949): Parsing tag category name = application
I/CustomizationCIDLoader( 6949): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6949): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6949): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6949): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6949): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6949): add string-array item, value = 42507
I/CustomizationCIDLoader( 6949): add string-array item, value = 21902
I/CustomizationCIDLoader( 6949): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6949): add string-array item, value = 23420
I/CustomizationCIDLoader( 6949): add string-array item, value = 22299
I/CustomizationCIDLoader( 6949): add string-array item, value = 24002
I/CustomizationCIDLoader( 6949): add string-array item, value = 23210
I/CustomizationCIDLoader( 6949): add string-array item, value = 23205
I/CustomizationCIDLoader( 6949): add string-array item, value = 23806
I/CustomizationCIDLoader( 6949): add string-array item, value = 23430
I/CustomizationCIDLoader( 6949): add string-array item, value = 23408
I/CustomizationCIDLoader( 6949): add string-array item, value = 27205
I/CustomizationCIDLoader( 6949): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6949): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6949):  Read CID file spent 0.066 (s)
D/CustomizationManager( 6949):  All configurations done spent 0.067 (s)
--------- beginning of system
I/ActivityManager(  971): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6949 on display 0
D/PMS     (  971): acquireHCC(c8ace22): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 971 1000 null
D/PMS     (  971): acquireHCC(323450b3): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 971 1000 null
W/asset   (  971): Copying FileAsset 0x55b84cd380 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  971): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6967 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  971): Display changed displayId=0
D/DotMatrix( 1338): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1338): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6967): Copying FileAsset 0xac72e598 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1587): [trimMemory] 20
I/WebViewFactory( 6967): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/Process (  971): killProcessQuiet, pid=5752
I/ActivityManager(  971): Killing 5752:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/LibraryLoader( 6967): Time to load native libraries: 9 ms (timestamps 969-978),
,I/LibraryLoader( 6967): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6967): Binding Chromium to main looper Looper (main, tid 1) {144f5366}
,I/LibraryLoader( 6967): Expected native library version number "",actual native library version number ""
,I/chromium( 6967): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6967): Initializing chromium process, singleProcess=true
,I/ActivityManager(  971): Recipient 5752
,W/art     ( 6967): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6967): ApplicationContext is null in ApplicationStatus
,W/chromium( 6967): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6967): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6967): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6967): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6967): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6967): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6967): Local Branch: 
I/Adreno-EGL( 6967): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6967): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6967):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  971): java.lang.Throwable: stack dump
W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@188b4388:true
,D/BluetoothAdapter( 6967): 1025967869: getState(). Returning 12
,W/art     ( 6967): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6967): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6967): CordovaWebView is running on device made by: HTC
,W/art     ( 6967): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6967): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  971): Activity pause timeout for ActivityRecord{2e4f1670 u0 com.test.thalitest/.MainActivity t8}
,W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6967): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  971): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
,D/StatusBarManagerService(  971): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
,D/FindExtension( 6967): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6967): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@143cfdf0, mServedView=org.apache.cordova.engine.SystemWebView{af76f69 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@23829dee
,I/InputMethodManagerService(  971): Disable input method client, pid=1587
,I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6967): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  971): Displayed com.test.thalitest/.MainActivity: +650ms (total +695ms)
,W/BindingManager( 6967): Cannot call determinedVisibility() - never saw a connection for the pid: 6967
,D/JsMessageQueue( 6967): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6967): JniHelper::setJavaVM(0xab5c28f8), pthread_self() = -1399806352
,I/chromium( 6967): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6967): Initializing JXcore engine
W/jxcore-log( 6967): JXcore engine is ready
,D/PMS     (  971): releaseHCC(c8ace22): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  971): releaseHCC(323450b3): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6967): Starting JXcore engine
,W/jxcore-log( 6967): Platform android
W/jxcore-log( 6967): 
W/jxcore-log( 6967): Process ARCH arm
W/jxcore-log( 6967): 
,I/jxcore-log( 6967): JXcore Cordova bridge is ready!
I/jxcore-log( 6967): 
W/jxcore-log( 6967): JXcore engine is started
,E/jxcore  ( 6967): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6967): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6967): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/Process (  971): killProcessQuiet, pid=6465,
I/ActivityManager(  971): Killing 6465:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  971): Recipient 6465
,W/PluginManager( 6967): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 127ms. Plugin should use CordovaInterface.getThreadPool().
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/PMS     (  971): acquireWL(3fe68cd0): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10024},
,V/AlarmManager(  971): sending alarm PendingIntent{2cf184c9: PendingIntentRecord{35c0f7ce com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=145492, Int=0
,D/PMS     (  971): releaseWL(3fe68cd0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/GpsLocationProvider(  971): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  971): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
D/PMS     (  971): acquireWL(25fe76ef): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 971 1000 null
,D/libc    (  971): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  971): [NET] android_getaddrinfofornet-, err=8
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  971): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  971): [NET] android_getaddrinfo_proxy+
,D/libc    (  971): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  971): [NET] android_getaddrinfo_proxy-, success
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  971): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  971): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  971): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  971): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  971):  [handleDownloadXtraData]inject done.
D/PMS     (  971): acquireWL(14e5930b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 971 1000 null
D/GpsLocationProvider(  971): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  971): releaseWL(25fe76ef): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/PMS     (  971): releaseWL(14e5930b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1535): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1535): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  971): acquireWL(1e0f25e8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000},
V/AlarmManager(  971): sending alarm PendingIntent{2d68371b: PendingIntentRecord{100be0b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149966, Int=0
,V/AlarmManager(  971): sending alarm PendingIntent{23700401: PendingIntentRecord{11b032a6 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453367959456, Int=0
D/PMS     (  971): acquireWL(9d854e7): PARTIAL_WAKE_LOCK  *backup* 0x1 971 1000 null
,W/BackupManagerService(  971): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  971): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  971): releaseWL(9d854e7): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  971): releaseWL(1e0f25e8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1216): Weather sync is On,
,W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data,
,D/PMS     (  971): acquireWL(2ca4b894): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
,I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(2ca4b894): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  971): updateBatteryInfo
D/PMS     (  971): runPSCheck
D/HtcPowerSaver(  971): Checking...
I/HtcPowerSaver(  971): >> updateStatus
,D/PowerUI ( 1216): closing low battery warning: level=100
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1338): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1),
D/UsbnetService(  971): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  971): << updateStatus
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: DeviceActiveState
,D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1535): switchBindHtcMsgCursor: null
,D/PMS     (  971): acquireWL(8d7df3d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{2d68371b: PendingIntentRecord{100be0b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209966, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{301cd332: PendingIntentRecord{f4b5883 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=211593, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{305eca00: PendingIntentRecord{35e83239 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192035, Int=0
,D/WeatherUtility( 1216): Weather sync is On
,D/PMS     (  971): acquireWL(440f07e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/PMS     (  971): releaseWL(8d7df3d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024},
,D/PMS     (  971): acquireWL(1860f9df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): releaseWL(440f07e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  971): releaseWL(1860f9df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(3600ef71): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(3600ef71): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): acquireWL(29c09156): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(29c09156): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(31ca45d7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(2fb16ec4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(4c6ce2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(31ca45d7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1823): Vacuum at: now=1453368001956 tag=VacuumService
,I/GoogleURLConnFactory( 1823): Using platform SSLCertificateSocketFactory
D/PMS     (  971): releaseWL(2fb16ec4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(17b8b330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(17b8b330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(275d1ba9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(275d1ba9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1823): No account for auth token provided
,D/libc    ( 1823): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1823): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1823): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1823): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1823): [NET] android_getaddrinfo_proxy+
D/libc    ( 1823): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1823): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1823): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1823): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1823): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1823): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1823): No account for auth token provided
,D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1646): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3c9ae3b9
I/ActivityManager(  971): Killing 6689:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=6689
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 6689
,W/Uploader( 1823): No account for auth token provided
,W/Uploader( 1823):  no longer exists, so no auth token.
,W/Uploader( 1823): No account for auth token provided
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1823): Explicit concurrent mark sweep GC freed 31924(1754KB) AllocSpace objects, 9(648KB) LOS objects, 47% free, 4MB/8MB, paused 1.276ms total 111.944ms,
,E/Uploader( 1823): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1823): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1823): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1823): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1823): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1823): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1338): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1338): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1216): reapply : com.google.android.gms 2 40
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1823): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1823): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1823): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1823): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1823): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1823): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1338): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1338): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1216): reapply : com.google.android.gms 3 40
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1823): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1823): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1823): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1823): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1823): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1823): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1823): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1338): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1338): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1216): reapply : com.google.android.gms 4 40
,D/PMS     (  971): releaseWL(4c6ce2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(90372b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(90372b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): acquireWL(122f7bb7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(122f7bb7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  971): acquireWL(1c739f24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(1c739f24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PMS     (  971): runPSCheck
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  971): Checking...
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  971): >> updateStatus
D/DotMatrix( 1338): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): handleMessage: E msg.what=155652
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1332): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1332): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): acquireWL(118fea8d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
I/BatteryService(  971): n_update end
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): releaseWL(118fea8d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1338): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/PMS     (  971): runPSCheck
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  971): >> updateStatus
D/PowerUI ( 1216): closing low battery warning: level=100
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: DeviceActiveState
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1338): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1338): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/GLSActivity( 1823): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1823): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1823): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1823): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1823): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1823): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1823): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1216): reapply : com.google.android.gms 4 40
,E/PlayEventLogger( 6130): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6130): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6130): 	,at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6130): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6130): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6130): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6130): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6130): Ignoring header User-Agent because its value was null.
,D/libc    ( 6130): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6130): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6130): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6130): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6130): [NET] android_getaddrinfo_proxy+
D/libc    ( 6130): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6130): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  971): acquireWL(17e0c0a7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000},
V/AlarmManager(  971): sending alarm PendingIntent{2d68371b: PendingIntentRecord{100be0b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=269966, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{a9d90fd: PendingIntentRecord{27f201f2 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453368133788, Int=0
,I/ActivityManager(  971): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7033 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  971): sending alarm PendingIntent{31cec043: PendingIntentRecord{2a6e76c0 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453368175149, Int=0
,D/WeatherUtility( 1216): Weather sync is On,
D/PMS     (  971): releaseWL(17e0c0a7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,I/art     (  971): Explicit concurrent mark sweep GC freed 28055(1530KB) AllocSpace objects, 10(1320KB) LOS objects, 33% free, 16MB/25MB, paused 1.819ms total 233.182ms
,D/StatusBarManagerService(  971): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
,D/StatusBarManagerService(  971): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
,D/FindExtension( 1587): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1587): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  971): Disable input method client, pid=6967
D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6967): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6967): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6967): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1216): setImeWindowStatus(false,false),
,E/cutils-trace( 7055): Error opening trace file: Permission denied (13),
I/dex2oat ( 7055): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7055): dex2oat: override thread count:4
,I/dex2oat ( 7055): dex2oat took 731.504ms (threads: 4)
,I/PushClient( 7033): ApplicationMonitor {3646e4c0}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 7033): ApplicationMonitor {3646e4c0}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 7033): ApplicationMonitor {3646e4c0}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7033): ApplicationMonitor {3646e4c0}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7033): ApplicationMonitor {3646e4c0}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7033): ApplicationMonitor {3646e4c0}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7033): ApplicationMonitor {3646e4c0}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 7033): ApplicationMonitor {3646e4c0}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7033): ApplicationMonitor {3646e4c0}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7033): PnsModel {92c2643}: update(): Update registration caused by: alarm
,I/PushClient( 7033): PnsConfigModel {39c96216}: <init>(): Use dm-client for provisioning.
,W/System.err( 7033): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 7033): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7033): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7033): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  971): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7062 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7062): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7062 dbg=false s=true,
,I/DeviceManagement( 7062): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 7062): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7062): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 7062): WorkflowService: Starting workflow service
,I/DeviceManagement( 7062): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@92c2643] args=[Bundle[mParcelledData.dataSize=88]]
I/DeviceManagement( 7062): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7062): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7062): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7062): SessionStateController: Checking invariants...
,I/DeviceManagement( 7062): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7062): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7062): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7062): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@92c2643],
,I/DeviceManagement( 7062): WorkflowService: Stopping workflow service
,D/Process (  971): killProcessQuiet, pid=6644
I/ActivityManager(  971): Killing 6644:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 6644
,I/PushClient( 7033): PnsModel {92c2643}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  971): Killing 6104:com.android.settings/1000 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=6104
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 6104,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  971): acquireWL(3059b36d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(3059b36d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1216): closing low battery warning: level=98
D/DotMatrix( 1338): [EventService] reorderNotification, total:1
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/NotificationService(  971): plugged=true pluggin=true
D/DotMatrix( 1338): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/WifiController(  971): battery changed pluggedType: 2
D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  971): >> updateStatus
D/HeadsetPhoneState( 3252): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,I/HtcPowerSaver(  971): updateStatus (8000,98,-1,false,false,false,-1)
D/UsbnetService(  971): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  971): << updateStatus
D/HeadsetStateMachine( 3252): Disconnected process message: 11, size: 0
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
,D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,W/ContextImpl( 6864): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,I/BatteryController( 1216): status:2 level:98 unsupport:false plugged:true
,I/ActivityManager(  971): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=7091 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7091): -onCreate(),
,V/Settings:HtcSettingsApplication( 7091): [7091/7091] onCreate()
,D/TetherSettings( 7091): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 7091): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 7091): Cust_ConnectToPC   : Modem_Link>false
D/        ( 7091): Cust_ConnectToPC   : spcsc>false
D/        ( 7091): Cust_ConnectToPC   : IPT>true
D/        ( 7091): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 7091): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 7091): Index of the first 1 = -1
,W/ContextImpl( 7091): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 7091): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 7091): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 7091): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 7091): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false,
D/SmartNS_NSReceiver( 7091): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 7091): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 7091): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/Process (  971): killProcessQuiet, pid=6130
I/ActivityManager(  971): Killing 6130:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  971): Recipient 6130
,D/PMS     (  971): acquireWL(3904033): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(3904033): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  971): Checking...
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: StaEnabledState
D/PowerUI ( 1216): closing low battery warning: level=98
D/WifiController(  971): processMsg: DefaultState
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): handleMessage: X
I/HtcPowerSaver(  971): updateStatus (8000,98,-1,false,false,false,-1)
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  971): << updateStatus
D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1338): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/BatteryController( 1216): status:2 level:98 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  971): acquireWL(126d0ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
I/BatteryService(  971): n_update end
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PMS     (  971): releaseWL(126d0ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1216): closing low battery warning: level=99
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/NotificationService(  971): plugged=true pluggin=true
D/WifiController(  971): handleMessage: E msg.what=155652
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  971): runPSCheck
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): processMsg: DefaultState
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): handleMessage: X
D/WifiController(  971): battery changed pluggedType: 2
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1338): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  971): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1216): status:2 level:99 unsupport:false plugged:true
,D/ContactMessageStore( 1535): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1535): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1535): sku_id=118
D/ContactMessageStore( 1535): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1535): start background delete task...,
,D/ContactMessageStore( 1535): size: 0 , 0
D/ContactMessageStore( 1535): Background delete complete
,D/PMS     (  971): acquireWL(16eb1969): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(16eb1969): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1338): [EventService] reorderNotification, total:0
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1338): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  971): updateBatteryInfo
D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
D/NotificationService(  971): plugged=true pluggin=true
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1216): closing low battery warning: level=100
D/HeadsetPhoneState( 3252): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/PMS     (  971): runPSCheck
D/HeadsetStateMachine( 3252): Disconnected process message: 11, size: 0
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971): onReceive BATTERY_CHANGED
,D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
W/ContextImpl( 6864): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): handleMessage: E msg.what=155652
,D/WifiController(  971): processMsg: DeviceActiveState,
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: StaEnabledState
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  971): processMsg: DefaultState
I/HtcPowerSaver(  971): << updateStatus
D/WifiController(  971): handleMessage: X
,D/TetherSettings( 7091): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 7091): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 7091): Cust_ConnectToPC   : Modem_Link>false
D/        ( 7091): Cust_ConnectToPC   : spcsc>false
D/        ( 7091): Cust_ConnectToPC   : IPT>true
D/        ( 7091): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 7091): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 7091): Index of the first 1 = -1
W/ContextImpl( 7091): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 7091): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 7091): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 7091): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 7091): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 7091): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  971): acquireWL(e04ac8f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{2d68371b: PendingIntentRecord{100be0b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=389966, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{2a2b3b1c: PendingIntentRecord{3412e325 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=943708, Int=0
,I/bt-btm  ( 3252): Received oneshot timer event complete
D/PMS     (  971): acquireWL(de2cfa): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3252 1002 null
I/bt-btm  ( 3252): btm_ble_timeout
I/bt-btm  ( 3252): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3252): btm_ble_rand_enc_complete
I/bt-btm  ( 3252): btm_gen_resolve_paddr_low
D/bt-smp  ( 3252): smp_encrypt_data
W/bt-smp  ( 3252): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3252): Plain text(LSB ~ MSB) = 53 3c 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3252): Encrypted text(LSB ~ MSB) = 2d 7c 76 45 a5 01 c7 82 69 55 f1 cb 71 4a 63 42 
I/bt-btm  ( 3252): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3252): Stopping oneshot timer
D/bt-btm  ( 3252): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  971): releaseWL(e04ac8f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1216): Weather sync is On
,W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/PMS     (  971): releaseWL(de2cfa): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/ActivityManager(  971): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7118 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/PMS     (  971): acquireWL(13a982ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10072}
,V/AlarmManager(  971): sending alarm PendingIntent{3eed08: PendingIntentRecord{3fd89715 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453368443172, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{23338ca1: PendingIntentRecord{17521ec6 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453368615966, Int=1800000
V/AlarmManager(  971): sending alarm PendingIntent{67b9e87: PendingIntentRecord{1059d1b4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937017, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{ef50af4: PendingIntentRecord{3464321d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806212, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{395b51dd: PendingIntentRecord{5b2499 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453368758570, Int=0
,D/PMS     (  971): acquireWL(2cc16152): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(3d9c5520): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1823 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): releaseWL(3d9c5520): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6864): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  971): acquireWL(270409e): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4568 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(2cc16152): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(13a982ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6864): MY_DEBUG = false
,D/PowerUsageService( 6864): repeat time = 1453369658642,
,I/EventLogService( 4568): Aggregate from 1453367889178 (log), 1453366815921 (data)
,D/PMS     (  971): acquireWL(21f46c9b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(90ba838): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1823 10024 WorkSource{10024 com.google.android.gms},
,I/GCM     ( 4568): Message from null null
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7118, uid=10072, userID:0
E/GCM     ( 4568): Dropping message from null,
,W/global  ( 7118): [apache-http] Connection GC has been deprecated!,
D/PMS     (  971): releaseWL(90ba838): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1823): Message class com.google.f.a.a.i
,D/PMS     (  971): releaseWL(21f46c9b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/Finsky  ( 7118): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,D/PMS     (  971): releaseWL(270409e): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/global  ( 7118): [apache-http] Connection GC has been deprecated!,
,I/PowerUsageList:PowerUsageHelper( 6864): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6864): gen(), null == sipper.uidObj, userId = 0
,W/global  ( 7118): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7118): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  971): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7157 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7118): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
W/Settings( 7118): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7118, uid=10072, userID:0
,D/Finsky  ( 7118): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/ResourcesManager( 7157): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7157): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7118): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7118): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7118): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7118): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,I/MultiDex( 7157): VM with version 2.1.0 has multidex support,
I/MultiDex( 7157): install
,I/MultiDex( 7157): VM has multidex support, MultiDex support library is disabled.
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/JNIHelp ( 7157): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7118): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 7157): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 7157): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bde3450: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7157): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1823): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1823): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4568): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4568, uid=10024, userID:0,
,D/WearableService( 5841): callingUid 10024, callindPid: 5841
,E/MDM     ( 1847): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4568): Restart initialization of location
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7118): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/Finsky  ( 7118): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/AndroidHttpClient( 7118): Leak found,
E/AndroidHttpClient( 7118): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 7118): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 7118): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 7118): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 7118): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 7118): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 7118): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 7118): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 7118): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 7118): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 7118): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 7118): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 7118): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 7118): 	at java.lang.reflect.Method.invoke(Native Method),
E/AndroidHttpClient( 7118): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 7118): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 7118): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  971): acquireWL(38a940a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10072}
V/AlarmManager(  971): sending alarm PendingIntent{149aae0d: PendingIntentRecord{3fd89715 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453368759835, Int=0
D/PMS     (  971): releaseWL(38a940a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 7118): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
W/Finsky  ( 7118): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7118): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7118): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 7118): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/DeviceConnectionService( 1847): client connected with version: 7571000,
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7118): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  971): Explicit concurrent mark sweep GC freed 19966(961KB) AllocSpace objects, 3(628KB) LOS objects, 33% free, 16MB/25MB, paused 2.032ms total 193.173ms
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7118): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 7118): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 7118): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7118): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 7118): [1] DailyHygiene.reschedule: Scheduling new run in 91 minutes (failures=3),
,D/DeviceConnectionService( 1847): client connected with version: 7571000
,D/Process (  971): killProcessQuiet, pid=6198
,I/ActivityManager(  971): Killing 6198:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 6198
,I/ActivityManager(  971): Killing 6040:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
D/Process (  971): killProcessQuiet, pid=6040
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 6040
,D/PMS     (  971): acquireWL(cc37607): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10072}
,V/AlarmManager(  971): sending alarm PendingIntent{d999334: PendingIntentRecord{2375b55d com.android.vending startService}}, i=null, t=0, cnt=1, w=1453368775325, Int=0,
D/PMS     (  971): releaseWL(cc37607): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 7118): [722] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 7118): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  971): acquireWL(194ebed2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000},
V/AlarmManager(  971): sending alarm PendingIntent{2d68371b: PendingIntentRecord{100be0b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=989965, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{2d176ba3: PendingIntentRecord{38d6aea0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453368805622, Int=0
,D/SmartSyncUtils( 6864): isEpsOn(), nState = 0,
D/PMS     (  971): acquireWL(c5d4a59): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6864 1000 null
,D/PMS     (  971): releaseWL(194ebed2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6864): [updateNmRange] bManual = false,
D/WeatherUtility( 1216): Weather sync is On
,W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 6864): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6864): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6864): SettingOnTime = 1453442400000, randomSettingOnTime = 1453441279000
,D/SmartSyncScreenOnOffTimeReceiver( 6864): SettingOffTime = 1453420800000, randomSettingOffTime = 1453425283000
D/SmartSyncScreenOnOffTimeReceiver( 6864): bDayMode = false,
D/SmartSyncScreenOnOffTimeReceiver( 6864): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6864): bNightModeTurnOffOnce = false
,D/PMS     (  971): releaseWL(c5d4a59): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  971): User[0] Flushing usage stats to disk
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1823): Explicit concurrent mark sweep GC freed 32432(1896KB) AllocSpace objects, 10(840KB) LOS objects, 47% free, 4MB/8MB, paused 1.019ms total 67.762ms
,I/GLSUser ( 1823): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1823): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1823): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1823): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1823): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1823): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1823): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1823): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1823): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1823): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1823): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1216): reapply : com.google.android.gms 3 40
,E/PlayEventLogger( 7118): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7118): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7118): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7118): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7118): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7118): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7118): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1338): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1338): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/System  ( 7118): Ignoring header User-Agent because its value was null.,
D/libc    ( 7118): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 7118): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7118): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 7118): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7118): [NET] android_getaddrinfo_proxy+
D/libc    ( 7118): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7118): [NET] android_getaddrinfo_proxy-, success
,D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): acquireWL(3f8a8393): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
D/DotMatrix( 1338): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  971): n_update end
D/DotMatrix( 1338): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  971): releaseWL(3f8a8393): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  971): updateBatteryInfo
D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  971): runPSCheck,
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): handleMessage: E msg.what=155652
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: StaEnabledState
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  971): processMsg: DefaultState
I/HtcPowerSaver(  971): << updateStatus
D/WifiController(  971): handleMessage: X
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
