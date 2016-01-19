#### Test 564496607226f84_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  945): acquireWL(19f40cc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{385d92eb: PendingIntentRecord{f5d5848 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=124527, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{2054ef15: PendingIntentRecord{2440622a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143727, Int=0
D/PMS     (  945): releaseWL(19f40cc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1205): Weather sync is On
W/WeatherTimeKeeper( 1205): [refreshWeatherData] no weather data
W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
E/cutils-trace( 6817): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6817): ====startRecUseTime====
D/htc.customization.log.level( 6817):  is 
W/CustomizationLogLevel( 6817): Level value is invalid, use default level 2
D/CustomizationManager( 6817):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 6817): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6817): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6817): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6817): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6817): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6817): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6817): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6817): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6817): Parsing tag category name = system
I/CustomizationCIDLoader( 6817): Parsing tag category name = application
I/CustomizationCIDLoader( 6817): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6817): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6817): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6817): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6817): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6817): add string-array item, value = 42507
I/CustomizationCIDLoader( 6817): add string-array item, value = 21902
I/CustomizationCIDLoader( 6817): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6817): add string-array item, value = 23420
I/CustomizationCIDLoader( 6817): add string-array item, value = 22299
I/CustomizationCIDLoader( 6817): add string-array item, value = 24002
I/CustomizationCIDLoader( 6817): add string-array item, value = 23210
I/CustomizationCIDLoader( 6817): add string-array item, value = 23205
I/CustomizationCIDLoader( 6817): add string-array item, value = 23806
I/CustomizationCIDLoader( 6817): add string-array item, value = 23430
I/CustomizationCIDLoader( 6817): add string-array item, value = 23408
I/CustomizationCIDLoader( 6817): add string-array item, value = 27205
I/CustomizationCIDLoader( 6817): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6817): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6817):  Read CID file spent 0.092 (s)
D/CustomizationManager( 6817):  All configurations done spent 0.092 (s)
D/PMS     (  945): acquireHCC(23cec81b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 945 1000 null
I/ActivityManager(  945): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6817 on display 0
D/PMS     (  945): acquireHCC(1fe59db8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 945 1000 null
I/ActivityManager(  945): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6835 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1322): [EventService]  onDisplayChanged: 0
V/ActivityManager(  945): Display changed displayId=0
D/DotMatrix( 1322): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1572): [trimMemory] 20
I/WebViewFactory( 6835): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6835): Time to load native libraries: 9 ms (timestamps 4485-4494),
,I/LibraryLoader( 6835): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6835): Binding Chromium to main looper Looper (main, tid 1) {277753c6}
,I/LibraryLoader( 6835): Expected native library version number "",actual native library version number ""
,I/chromium( 6835): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6835): Initializing chromium process, singleProcess=true,
,W/art     ( 6835): Attempt to remove local handle scope entry from IRT, ignoring,
E/SysUtils( 6835): ApplicationContext is null in ApplicationStatus
,W/chromium( 6835): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6835): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6835): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6835): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6835): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6835): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6835): Local Branch: 
I/Adreno-EGL( 6835): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6835): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete,
I/Adreno-EGL( 6835):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  945): Message: MESSAGE_REGISTER_ADAPTER,
W/System.err(  945): java.lang.Throwable: stack dump
W/System.err(  945): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  945): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  945): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  945): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  945): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dda74fc:true
,D/BluetoothAdapter( 6835): 847570514: getState(). Returning 12
,W/art     ( 6835): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6835): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6835): CordovaWebView is running on device made by: HTC
,W/art     ( 6835): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6835): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  945): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/chromium( 6835): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  945): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  945): hiding MENU key
D/StatusBarManagerService(  945): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  945): hiding MENU key
,D/FindExtension( 6835): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6835): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@23301350, mServedView=org.apache.cordova.engine.SystemWebView{213ac949 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@6d2224e
,I/PhoneStatusBar( 1205): setImeWindowStatus(false,false)
I/InputMethodManagerService(  945): Disable input method client, pid=1572
D/StatusBarManagerService(  945): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6835): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  945): Displayed com.test.thalitest/.MainActivity: +619ms (total +663ms)
,W/BindingManager( 6835): Cannot call determinedVisibility() - never saw a connection for the pid: 6835,
,D/JsMessageQueue( 6835): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6835): JniHelper::setJavaVM(0xaae1a8f8), pthread_self() = -1408034632,
,I/chromium( 6835): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,W/jxcore-log( 6835): Initializing JXcore engine,
W/jxcore-log( 6835): JXcore engine is ready,
,W/jxcore-log( 6835): Starting JXcore engine,
,D/PMS     (  945): releaseHCC(23cec81b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  945): releaseHCC(1fe59db8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6835): Platform android,
W/jxcore-log( 6835): 
W/jxcore-log( 6835): Process ARCH arm
W/jxcore-log( 6835): 
,I/jxcore-log( 6835): JXcore Cordova bridge is ready!
I/jxcore-log( 6835): 
,W/jxcore-log( 6835): JXcore engine is started
,E/jxcore  ( 6835): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6835): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6835): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,I/ActivityManager(  945): Killing 6354:com.android.defcontainer/u0a15 (adj 15): empty #17,
D/Process (  945): killProcessQuiet, pid=6354
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,D/GpsLocationProvider(  945): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  945): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  945): acquireWL(3ba70271): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 945 1000 null
,D/libc    (  945): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  945): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  945): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  945): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  945): [NET] android_getaddrinfo_proxy+
D/libc    (  945): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  945): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  945): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  945): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  945): Recipient 6354
,W/PluginManager( 6835): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 242ms. Plugin should use CordovaInterface.getThreadPool().,
,D/GpsLocationProvider(  945): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  945): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  945): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  945):  [handleDownloadXtraData]inject done.,
D/PMS     (  945): acquireWL(35854ad): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 945 1000 null
,D/PMS     (  945): releaseWL(3ba70271): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null,
D/GpsLocationProvider(  945): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
D/PMS     (  945): releaseWL(35854ad): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,D/ContactMessageStore( 1491): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1491): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  945): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  945): acquireWL(136f3e2): PARTIAL_WAKE_LOCK  *alarm* 0x1 945 1000 WorkSource{1000},
V/AlarmManager(  945): sending alarm PendingIntent{580e373: PendingIntentRecord{33528ea9 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453202083901, Int=0
D/PMS     (  945): acquireWL(3b201230): PARTIAL_WAKE_LOCK  *backup* 0x1 945 1000 null
,D/PMS     (  945): releaseWL(136f3e2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,W/BackupManagerService(  945): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  945): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  945): releaseWL(3b201230): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  945): acquireWL(1546c2e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null,
,D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/BatteryService(  945): n_update end
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PMS     (  945): releaseWL(1546c2e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/PMS     (  945): runPSCheck
I/IntentController( 1205): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  945): Checking...
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): handleMessage: E msg.what=155652
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HeadsetStateMachine( 2937): Disconnected process message: 10, size: 0
,D/PowerUI ( 1205): closing low battery warning: level=98
,D/PowerUI ( 1205): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  945): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1205): status:2 level:98 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1491): switchBindHtcMsgCursor: null
,D/PMS     (  945): acquireWL(237c43cf): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{385d92eb: PendingIntentRecord{f5d5848 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=184527, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{39ac215c: PendingIntentRecord{299c6c65 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=212711, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{1bbf1d3a: PendingIntentRecord{20234deb com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=194322, Int=0
,D/PMS     (  945): acquireWL(1f87f748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): releaseWL(237c43cf): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1205): Weather sync is On
W/WeatherTimeKeeper( 1205): [refreshWeatherData] no weather data
,D/PMS     (  945): acquireWL(23ec69e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(1f87f748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  945): releaseWL(23ec69e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(3b698f63): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(3b698f63): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(3f346760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(3f346760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(350f7419): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(314a3cde): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(3468998c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(350f7419): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1848): Using platform SSLCertificateSocketFactory,
,I/VacuumService( 1848): Vacuum at: now=1453202128593 tag=VacuumService
,D/PMS     (  945): releaseWL(3468998c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(2061ad8d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(2061ad8d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): acquireWL(14860b42): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(14860b42): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(314a3cde): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(b8d1753): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(b8d1753): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(5606890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(5606890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(19489589): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(126d998e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(19489589): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1848): Using platform SSLCertificateSocketFactory
,W/Uploader( 1848): No account for auth token provided,
,D/libc    ( 1848): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1848): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1848): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1848): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1848): [NET] android_getaddrinfo_proxy+
D/libc    ( 1848): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1848): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1848): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1848): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1848): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1848): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1848): No account for auth token provided
,W/Uploader( 1848):  no longer exists, so no auth token.
,W/Uploader( 1848): No account for auth token provided
,W/Uploader( 1848): No account for auth token provided
,W/Uploader( 1848): No account for auth token provided
,D/HtcUPManager( 1205): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1205): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1466): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3546e599
,I/GLSUser ( 1848): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1848): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1848): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1848): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1848): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1848): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1848): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1848): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1848): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1848): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1322): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1322): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1205): reapply : com.google.android.gms 3 40
,I/GLSUser ( 1848): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1848): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1848): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1848): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1848): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1848): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1848): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1848): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1848): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
,E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1848): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1848): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1322): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1322): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1205): reapply : com.google.android.gms 3 40
,D/PMS     (  945): releaseWL(126d998e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  945): acquireWL(2447844a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(2447844a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  945): acquireWL(17fe0fbb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  945): releaseWL(17fe0fbb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  945): Killing 6561:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=6561
,D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6561
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1297): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1297): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1297): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 1297): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  945): acquireWL(599dcd8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{385d92eb: PendingIntentRecord{f5d5848 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=244527, Int=0
,V/AlarmManager(  945): sending alarm PendingIntent{1f819b16: PendingIntentRecord{3073ec97 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453202257376, Int=0
,D/PMS     (  945): releaseWL(599dcd8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1205): Weather sync is On,
W/WeatherTimeKeeper( 1205): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  945): acquireWL(73bee84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(73bee84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/WifiController(  945): battery changed pluggedType: 2
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): handleMessage: E msg.what=155652
I/HtcPowerSaver(  945): >> updateStatus
,D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1205): closing low battery warning: level=99
D/HeadsetStateMachine( 2937): Disconnected process message: 10, size: 0
D/PowerUI ( 1205): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
,I/IntentController( 1205): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  945): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1205): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1848): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1848): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1848): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1848): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1848): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1848): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1848): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1848): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1848): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1848): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1848): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1322): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1322): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1205): reapply : com.google.android.gms 3 40,
E/PlayEventLogger( 6097): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6097): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6097): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6097): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6097): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6097): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6097): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6097): Ignoring header User-Agent because its value was null.
,D/libc    ( 6097): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6097): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6097): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6097): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6097): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6097): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:100, mark:917604,
D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6097): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  945): acquireWL(25b4f5c6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(25b4f5c6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/WifiController(  945): battery changed pluggedType: 2
,D/WifiController(  945): handleMessage: E msg.what=155652
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): processMsg: DeviceActiveState
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: StaEnabledState
D/PowerUI ( 1205): closing low battery warning: level=99
D/WifiController(  945): processMsg: DefaultState
D/PowerUI ( 1205): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): handleMessage: X
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1205): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 2937): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  945): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1205): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  945): acquireWL(e132987): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{385d92eb: PendingIntentRecord{f5d5848 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=364527, Int=0
,I/ActivityManager(  945): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6904 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  945): sending alarm PendingIntent{3a3a00b4: PendingIntentRecord{362154dd com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453202404218, Int=0
,D/PMS     (  945): releaseWL(e132987): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1205): Weather sync is On
W/WeatherTimeKeeper( 1205): [refreshWeatherData] no weather data
,D/StatusBarManagerService(  945): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  945): hiding MENU key
,D/StatusBarManagerService(  945): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  945): hiding MENU key,
,D/FindExtension( 1572): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1572): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  945): Disable input method client, pid=6835,
D/StatusBarManagerService(  945): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6835): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6835): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6835): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1205): setImeWindowStatus(false,false)
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
,E/cutils-trace( 6926): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6926): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6926): dex2oat: override thread count:4
,I/dex2oat ( 6926): dex2oat took 811.898ms (threads: 4)
,I/PushClient( 6904): ApplicationMonitor {22cfe220}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6904): ApplicationMonitor {22cfe220}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6904): ApplicationMonitor {22cfe220}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6904): ApplicationMonitor {22cfe220}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6904): ApplicationMonitor {22cfe220}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6904): ApplicationMonitor {22cfe220}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6904): ApplicationMonitor {22cfe220}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6904): ApplicationMonitor {22cfe220}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6904): ApplicationMonitor {22cfe220}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6904): PnsModel {362f3d23}: update(): Update registration caused by: alarm
,I/PushClient( 6904): PnsConfigModel {32a23a76}: <init>(): Use dm-client for provisioning.
,W/System.err( 6904): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6904): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6904): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6904): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  945): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6933 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6933): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6933 dbg=false s=true,
,I/DeviceManagement( 6933): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6933): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6933): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6933): WorkflowService: Starting workflow service
,I/DeviceManagement( 6933): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@362f3d23] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6933): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6933): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6933): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6933): SessionStateController: Checking invariants...
,I/DeviceManagement( 6933): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 6933): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6933): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6933): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@362f3d23]
,I/DeviceManagement( 6933): WorkflowService: Stopping workflow service,
,D/Process (  945): killProcessQuiet, pid=6516
I/ActivityManager(  945): Killing 6516:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6516
,I/PushClient( 6904): PnsModel {362f3d23}: update(): The registration record has not expired yet. No need to update.
,D/Process (  945): killProcessQuiet, pid=6600
,I/ActivityManager(  945): Killing 6600:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6600
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  945): acquireWL(348c5c76): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(348c5c76): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1322): [EventService] reorderNotification, total:0
D/HeadsetStateMachine( 2937): Disconnected process message: 10, size: 0
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1205): closing low battery warning: level=100
D/HeadsetPhoneState( 2937): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2937): Disconnected process message: 11, size: 0
I/IntentController( 1205): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  945): updateBatteryInfo
D/NotificationService(  945): plugged=true pluggin=true
,D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  945): >> updateStatus
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): handleMessage: E msg.what=155652
D/PowerUI ( 1205): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
W/ContextImpl( 6735): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
D/WifiController(  945): handleMessage: X
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  945): << updateStatus
,D/TetherSettings( 6073): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 6073): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6073): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6073): Cust_ConnectToPC   : spcsc>false
D/        ( 6073): Cust_ConnectToPC   : IPT>true
D/        ( 6073): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 6073): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false,
D/SmartNS_NSReceiver( 6073): Index of the first 1 = -1
,I/BatteryController( 1205): status:5 level:100 unsupport:false plugged:true,
,W/ContextImpl( 6073): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 6073): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 6073): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 6073): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 6073): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6073): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 6073): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 6073): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1491): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1491): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1491): sku_id=118
D/ContactMessageStore( 1491): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1491): start background delete task...
,D/ContactMessageStore( 1491): size: 0 , 0,
D/ContactMessageStore( 1491): Background delete complete
,D/PMS     (  945): acquireWL(3fb8fee4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(3fb8fee4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  945): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  945): Checking...,
,D/WifiController(  945): handleMessage: E msg.what=155652
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: DeviceActiveState,
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: StaEnabledState
,D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
,D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 2937): Disconnected process message: 10, size: 0
,I/IntentController( 1205): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
D/PowerUI ( 1205): closing low battery warning: level=100
D/PowerUI ( 1205): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1205): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  945): acquireWL(7c62f4d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{385d92eb: PendingIntentRecord{f5d5848 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=544527, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{1459ca02: PendingIntentRecord{553cf13 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941549, Int=0
I/bt-btm  ( 2937): Received oneshot timer event complete
I/bt-btm  ( 2937): btm_ble_timeout
I/bt-btm  ( 2937): btm_gen_resolvable_private_addr
,D/PMS     (  945): acquireWL(9792550): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 2937 1002 null
,D/bt-btm  ( 2937): btm_ble_rand_enc_complete
I/bt-btm  ( 2937): btm_gen_resolve_paddr_low
D/bt-smp  ( 2937): smp_encrypt_data
W/bt-smp  ( 2937): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 2937): Plain text(LSB ~ MSB) = c7 62 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2937): Encrypted text(LSB ~ MSB) = 8c 73 7a 87 78 52 2d 7c 2c 22 85 e5 d9 90 80 15 
I/bt-btm  ( 2937): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 2937): Stopping oneshot timer
D/PMS     (  945): releaseWL(7c62f4d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/bt-btm  ( 2937): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1205): Weather sync is On,
,W/WeatherTimeKeeper( 1205): [refreshWeatherData] no weather data
,D/PMS     (  945): releaseWL(9792550): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  945): acquireWL(1dd37349): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{385d92eb: PendingIntentRecord{f5d5848 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=964527, Int=0
,D/SmartSyncUtils( 6735): isEpsOn(), nState = 0
V/AlarmManager(  945): sending alarm PendingIntent{139e844e: PendingIntentRecord{922496f com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453202929304, Int=0
,I/art     (  945): Explicit concurrent mark sweep GC freed 29794(1557KB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 16MB/25MB, paused 1.840ms total 191.680ms
D/PMS     (  945): acquireWL(10d3467c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6735 1000 null
,D/PMS     (  945): releaseWL(1dd37349): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/SmartSyncScreenOnOffTimeReceiver( 6735): [updateNmRange] bManual = false
D/WeatherUtility( 1205): Weather sync is On
W/WeatherTimeKeeper( 1205): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 6735): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 6735): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6735): SettingOnTime = 1453269600000, randomSettingOnTime = 1453268773000
D/SmartSyncScreenOnOffTimeReceiver( 6735): SettingOffTime = 1453248000000, randomSettingOffTime = 1453248141000
D/SmartSyncScreenOnOffTimeReceiver( 6735): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6735): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6735): bNightModeTurnOffOnce = false
D/PMS     (  945): releaseWL(10d3467c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/IntentController( 1205): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  945): acquireWL(956fb05): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  945): n_update end
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  945): releaseWL(956fb05): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1205): closing low battery warning: level=100
D/HeadsetStateMachine( 2937): Disconnected process message: 10, size: 0
D/PowerUI ( 1205): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945): onReceive BATTERY_CHANGED,
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  945): battery changed pluggedType: 2
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/PMS     (  945): runPSCheck
D/WifiController(  945): handleMessage: E msg.what=155652
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): processMsg: DeviceActiveState
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
,I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1205): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  945): acquireWL(2562975a): PARTIAL_WAKE_LOCK  *alarm* 0x1 945 1000 WorkSource{1000}
,V/AlarmManager(  945): sending alarm PendingIntent{be59fcb: PendingIntentRecord{297713a8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806168, Int=0
,V/AlarmManager(  945): sending alarm PendingIntent{385d92eb: PendingIntentRecord{f5d5848 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1024527, Int=0,
V/AlarmManager(  945): sending alarm PendingIntent{1eb40d8b: PendingIntentRecord{334c4e68 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=939532, Int=0
D/PMS     (  945): acquireWL(23d14281): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,V/AlarmManager(  945): sending alarm PendingIntent{3322cf26: PendingIntentRecord{3e53f767 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453203054591, Int=1800000
,V/AlarmManager(  945): sending alarm PendingIntent{1fcbe914: PendingIntentRecord{1c2f9bb1 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453202886965, Int=0
,D/PMS     (  945): releaseWL(23d14281): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): acquireWL(44e85bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms},
,D/WeatherUtility( 1205): Weather sync is On
,W/WeatherTimeKeeper( 1205): [refreshWeatherData] no weather data
,D/PMS     (  945): acquireWL(2f5cb7b2): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4298 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6735): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  945): releaseWL(2562975a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  945): acquireWL(2c62c0b9): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4298 10024 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 6735): MY_DEBUG = false
D/PMS     (  945): releaseWL(2f5cb7b2): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageService( 6735): repeat time = 1453203954667
,D/PMS     (  945): acquireWL(8e5af75): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10176 com.google.android.youtube},
,I/EventLogService( 4298): Aggregate from 1453202013544 (log), 1453201254556 (data)
,I/ActivityManager(  945): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6972 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/PMS     (  945): releaseWL(44e85bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  945): releaseWL(2c62c0b9): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 6735): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6735): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  945): acquireWL(17a76f7b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1848 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1848): Message class com.google.f.a.a.i,
,W/ResourcesManager( 6972): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6972): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  945): releaseWL(17a76f7b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,V/JNIHelp ( 6972): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6972): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6972): Installed default security provider GmsCore_OpenSSL
,W/art     ( 6972): Suspending all threads took: 17.199ms
,E/cutils-trace( 7003): Error opening trace file: Permission denied (13)
,I/dex2oat ( 7003): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1414292580.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads-1414292580.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7003): dex2oat: override thread count:4
,I/dex2oat ( 7003): dex2oat took 46.413ms (threads: 4),
,E/YouTube MDX( 6972): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,D/libc    ( 6972): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    ( 6972): [NET] android_getaddrinfofornet-, SUCCESS
,W/art     ( 6972): Suspending all threads took: 9.510ms,
,D/VoldConnector(  945): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 6972): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,D/VoldConnector(  945): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 6972): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  945): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 6972): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
D/VoldConnector(  945): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 6972): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 6972): Found 10024
,D/VoldConnector(  945): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 6972): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,D/PMS     (  945): acquireWL(a3c725e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  945): releaseWL(a3c725e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 6972): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6972): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6972): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6972): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6972): [NET] android_getaddrinfo_proxy+
D/libc    ( 6972): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    (  398): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6972): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 6972): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 6972): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6972): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6972): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6972): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 6972): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6972): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6972): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6972): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6972): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6972): [NET] android_getaddrinfo_proxy-, success,
D/libc    ( 6972): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 6972): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6972): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6972): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  945): releaseWL(8e5af75): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube},
,I/ActivityManager(  945): Killing 6097:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=6097
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  945): acquireWL(117a2fa4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(117a2fa4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  945): Recipient 6097
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  945): User[0] Flushing usage stats to disk
,D/PMS     (  945): acquireWL(2862710d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{385d92eb: PendingIntentRecord{f5d5848 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1144527, Int=0,
,V/AlarmManager(  945): sending alarm PendingIntent{7846d3: PendingIntentRecord{32fca210 com.htc.cs.dm startService}}, i=com.htc.cs.action.EXECUTE_WORKFLOW, t=1, cnt=1, w=1453203213170, Int=0
,I/DeviceManagement( 6933): WorkflowService: Starting workflow service
,I/DeviceManagement( 6933): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@21ccafa5] args=[Bundle[mParcelledData.dataSize=56]],
I/DeviceManagement( 6933): UpdateWorkflow: ==================================================
D/PMS     (  945): releaseWL(2862710d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
I/DeviceManagement( 6933): UpdateWorkflow: TTL update...
I/DeviceManagement( 6933): UpdateWorkflow: ==================================================
D/WeatherUtility( 1205): Weather sync is On
,W/WeatherTimeKeeper( 1205): [refreshWeatherData] no weather data
,I/DeviceManagement( 6933): SessionStateController: Checking invariants...
,I/DeviceManagement( 6933): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 6933): Perf: *** Cache update - start...,
I/DeviceManagement( 6933): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 6933): EnabledAppController: *** Updating enabled app database...
,I/DeviceManagement( 6933): Perf: *** Enabled app cache update - complete: 2 ms
I/DeviceManagement( 6933): Perf: *** Config cache update - start...
,I/DeviceManagement( 6933): ConfigCacheController: *** Updating config cache...,
I/DeviceManagement( 6933): ConfigCacheController: *** Updating stale config cache entries...
,I/art     ( 6933): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,I/art     ( 6933): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,W/System.err( 6933): Starting the internal HTTP client,
,I/DeviceManagement( 6933): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg,
,I/DeviceManagement( 6933): DeviceClientResource: Active network...
I/DeviceManagement( 6933):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BuildInfo( 6933): Created new instance: com.htc.cs.lib.hms.BuildInfo@2e660a00
,I/DeviceManagement( 6933): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
,D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 6933): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6933): [NET] android_getaddrinfo_proxy+
D/libc    ( 6933): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6933): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 6933): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6933): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6933): [NET] android_getaddrinfo_proxy+
D/libc    ( 6933): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024,
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6933): [NET] android_getaddrinfo_proxy-, success
,I/DeviceManagement( 6933): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6933): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6933): DeviceClientResourceController: handleDirectives: []
,I/System.out( 6933): isCompatible false
,I/System.out( 6933): createObjectMapper
I/System.out( 6933): isCompatible false
,I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
,I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
,I/DeviceManagement( 6933): ConfigCacheController: Getting config update from server: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.sense.socialnetwork.facebook/versions/2adae5da-a4df-4cc3-b772-ea9aaa6301b2/cid/MDowOjIwMTUtMDQtMTVUMDk6MDM6NTguMjk2Wg,
,I/DeviceManagement( 6933): DeviceClientResource: Active network...,
I/DeviceManagement( 6933):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 6933): [NET] android_getaddrinfofornet-, err=8
,I/DeviceManagement( 6933): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6933): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 6933): DeviceClientResourceController: handleDirectives: []
I/System.out( 6933): isCompatible false
I/System.out( 6933): createObjectMapper
,I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
,I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
,I/DeviceManagement( 6933): ConfigCacheController: Getting config update from server: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.identity/versions/887a7f5610a36712ed50f1fb1911e4b5da8368ea/cid/MDoyOjIwMTUtMTItMjNUMDM6MjM6MTIuMzY4Wg,
,I/DeviceManagement( 6933): DeviceClientResource: Active network...,
I/DeviceManagement( 6933):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 6933): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6933): [NET] android_getaddrinfo_proxy+
D/libc    ( 6933): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6933): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 6933): [NET] android_getaddrinfofornet-, err=8
,I/DeviceManagement( 6933): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6933): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6933): DeviceClientResourceController: handleDirectives: []
,I/System.out( 6933): isCompatible false
I/System.out( 6933): createObjectMapper,
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
,I/DeviceManagement( 6933): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pns/versions/55580870d4ecef7adc0bfac442bc01d880550489/cid/MDoxOjIwMTQtMTAtMjNUMDI6MDc6MTQuNTA0Wg,
,I/DeviceManagement( 6933): DeviceClientResource: Active network...,
I/DeviceManagement( 6933):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 6933): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    ( 6933): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6933): [NET] android_getaddrinfo_proxy+,
D/libc    ( 6933): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6933): [NET] android_getaddrinfo_proxy-, success
,I/DeviceManagement( 6933): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6933): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6933): DeviceClientResourceController: handleDirectives: [],
I/System.out( 6933): isCompatible false
I/System.out( 6933): createObjectMapper
,I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false,
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
,I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
,I/DeviceManagement( 6933): ConfigCacheController: Getting config update from server: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.csrecommend/versions/f26b54be-e9ca-4494-ba25-56712573f3ab/cid/MDoxMDoyMDE1LTA4LTI2VDEwOjE0OjI0LjczNVo,
,I/DeviceManagement( 6933): DeviceClientResource: Active network...,
I/DeviceManagement( 6933):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 6933): [NET] android_getaddrinfofornet-, err=8
,I/DeviceManagement( 6933): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6933): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6933): DeviceClientResourceController: handleDirectives: []
I/System.out( 6933): isCompatible false
I/System.out( 6933): createObjectMapper
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false,
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
,I/DeviceManagement( 6933): ConfigCacheController: Getting config update from server: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.dm/versions/b5b04a47-d585-4433-9a63-6f3f39989144/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNjA2Wg,
,I/DeviceManagement( 6933): DeviceClientResource: Active network...
I/DeviceManagement( 6933):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 6933): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 6933): [NET] android_getaddrinfofornet-, err=8
,I/DeviceManagement( 6933): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6933): ServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6933): DeviceClientResourceController: handleDirectives: []
I/System.out( 6933): isCompatible false
I/System.out( 6933): createObjectMapper
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
I/System.out( 6933): isCompatible false
,I/System.out( 6933): isCompatible false
,I/DeviceManagement( 6933): ConfigCacheController: *** Update config cache: updating 6 entries...,
I/DeviceManagement( 6933): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, statusCode=0, authCode=0>,
,I/DeviceManagement( 6933): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, statusCode=0, authCode=0>
,I/DeviceManagement( 6933): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, statusCode=0, authCode=0>
,I/DeviceManagement( 6933): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, statusCode=0, authCode=0>
,I/DeviceManagement( 6933): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, statusCode=0, authCode=0>
,I/DeviceManagement( 6933): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, statusCode=0, authCode=0>
,I/DeviceManagement( 6933): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 6933): AlarmController: Scheduling TTL alarm for: 2016.01.19 at 12:42:24.614 CET (due to: com.htc.launcher)
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=6933, uid=10099, userID:0
,I/DeviceManagement( 6933): Perf: *** Config cache update - complete: 5175 ms,
,I/DeviceManagement( 6933): Perf: *** Cache update - complete: 5180 ms
I/DeviceManagement( 6933): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@21ccafa5],
,I/DeviceManagement( 6933): WorkflowService: Stopping workflow service
,TIME-OUT KILL (timeout was 1200000ms)
```
