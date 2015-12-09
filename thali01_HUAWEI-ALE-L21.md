#### Test 5065027873d6a28_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
I/appproc ( 6772): CLASSPATH=/system/framework/am.jar
I/appproc ( 6772): Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
I/appproc ( 6772): app_process:number,5,0
I/AndroidRuntime( 6772): readDownloadBoosterConfig: 'false'
I/        ( 6772): power log dlsym ok
E/android_hardware_fm.cpp( 6772): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6772): ========64bit long size = 8
E/FM_HAL  ( 6772): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 6772): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6772): 
I/fm_hisi ( 6772): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6772): 
I/fm_hisi ( 6772): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6772): 
E/android_hardware_fm.cpp( 6772): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 3018): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 3018): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 3018): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 3018): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwSystemManager( 4066): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 4066): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3835): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3835): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3835): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 4066): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwLauncher( 3835): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3835): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/WebViewFactory( 6791): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/LibraryLoader( 6791): Loading: webviewchromium
I/LibraryLoader( 6791): Time to load native libraries: 59 ms (timestamps 2587-2646)
I/LibraryLoader( 6791): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 6791): Expected native library version number "",actual native library version number ""
I/chromium( 6791): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6791): Initializing chromium process, renderers=0
W/art     ( 6791): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6791): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6791): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6791): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 6791): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/chromium( 6791): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6791): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 6791): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 6791): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6791): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 6791): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6791): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6791): Can not find class: Landroid/app/ViewStub;
W/art     ( 6791): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6791): Attempt to remove local handle scope entry from IRT, ignoring
,I/PhoneStatusBar( 3392): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/PhoneStatusBar( 3392): shouldTranslucent:true
,I/PhoneStatusBar( 3392): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/OpenGLRenderer( 6791): Initialized EGL, version 1.4
,I/ActivityManager( 3018): Displayed com.test.thalitest/.MainActivity: +1s124ms (total +1s204ms)
,W/IInputConnectionWrapper( 6791): showStatusIcon on inactive InputConnection
,I/art     ( 5714): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
,W/jxcore-log( 6791): Initializing JXcore engine
W/jxcore-log( 6791): JXcore engine is ready
,W/jxcore-log( 6791): Starting JXcore engine
,W/jxcore-log( 6791): Platform android
W/jxcore-log( 6791): 
W/jxcore-log( 6791): Process ARCH arm
W/jxcore-log( 6791): 
,I/art     ( 3018): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/jxcore-log( 6791): JXcore Cordova bridge is ready!
I/jxcore-log( 6791): 
,W/jxcore-log( 6791): JXcore engine is started
I/chromium( 6791): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6791): 
,E/jxcore  ( 6791): Error!: missing ) after argument list
E/jxcore  ( 6791): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6791): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 6791): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,W/PluginManager( 6791): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 118ms. Plugin should use CordovaInterface.getThreadPool().
,I/HwSystemManager( 4066): AppLockService:applock password not initial or function is closed
,I/HwSystemManager( 4066): AppLockService:applock password not initial or function is closed
,I/HwSystemManager( 4066): AppManager:getNetAppInfoFromDB cursor lenth = 1
,E/HsmCoreServiceImpl( 3018): onTransact in code is: 102
I/MediaProcessHandler( 3018): processOp opType: 1, uid: 10041, pid: 5857
,W/MediaProcessHandler( 3018): remove target not exist, maybe the UI process: uid: 10041, pid: 5857
,I/HwSystemManager( 4066): HoldService:uid:10041 pid:5857 died
I/HwSystemManager( 4066): HoldService:oldVersionKey:10041,5857
I/HwSystemManager( 4066): BgPowerManagerService:onProcessDied uid = 10041
,W/ScreenOrientationListener( 6791): Removing an inexistent observer!
,I/ActivityManager( 3018): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,E/Thermal-daemon( 2330): [ap] temp_new :29  temp_old :30
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 60179 firstTime = 62654 firstmBatteryCapacity =2205
,E/Thermal-daemon( 2330): [charger_ic] temp_new :29  temp_old :30
,I/HwSystemManager( 4066): InputMethodStringPredicate:InputMethodStringPredicate :: inputMethods = [com.nuance.swype.emui, com.nuance.swype.input.HuaweiIME, com.android.inputmethod.latin]
,I/HwSystemManager( 4066): LauncherPredicate:get default launcher is null, set hwlauncher
,I/HwSystemManager( 4066): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 4066): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 4066): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 4066): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 4066): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 4066): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 4066): SmartMemoryCleanService:SMCSDataManager.checkAvailMemory.: availMem 1190572032 [332800000,437657600,542515200]
I/HwSystemManager( 4066): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor start
,I/HwSystemManager( 4066): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor end
,I/ClearcutLoggerApiImpl( 3698): disconnect managed GoogleApiClient
,I/HwLauncher( 3835): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3392): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3392): hand message 1
I/TimeManager( 3392): notify time change. size = 2
,I/TimeLayout( 3392): time = 03:04
,I/TimeLayout( 3392): updateDate date = 12/9/2015
,I/TimeLayout( 3392): weekDay = Wednesday
,I/ActivityManager( 3018): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 124128 firstTime = 62654 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 150415 firstTime = 62654 firstmBatteryCapacity =2205
,E/Thermal-daemon( 2330): [ap] temp_new :28  temp_old :29
,I/HwLauncher( 3835): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3392): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3392): hand message 1
I/TimeManager( 3392): notify time change. size = 2
,I/TimeLayout( 3392): time = 03:05
,I/TimeLayout( 3392): updateDate date = 12/9/2015
,I/TimeLayout( 3392): weekDay = Wednesday
,I/art     ( 3018): Can not find class: Lcom/android/server/power/PowerManagerService$5$1;
,W/System.err( 3018): java.net.UnknownHostException: Unable to resolve host "www.google.com": No address associated with hostname
,W/System.err( 3018): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
W/System.err( 3018): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 3018): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
W/System.err( 3018): 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
W/System.err( 3018): 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
W/System.err( 3018): 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
W/System.err( 3018): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
W/System.err( 3018): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
W/System.err( 3018): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
W/System.err( 3018): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
W/System.err( 3018): 	at com.android.server.power.PowerManagerService.isGoogleConnectOK(PowerManagerService.java:3530)
W/System.err( 3018): 	at com.android.server.power.PowerManagerService.access$6500(PowerManagerService.java:107)
W/System.err( 3018): 	at com.android.server.power.PowerManagerService$5$1.run(PowerManagerService.java:3502)
W/System.err( 3018): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 3018): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 3018): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 3018): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:438)
W/System.err( 3018): 	... 12 more
,I/art     ( 3018): Can not find class: Lcom/android/server/am/ActivityManagerService$31$1;
,I/art     ( 3018): Can not find class: Lcom/android/server/am/ActivityManagerService$33$1;
,E/Thermal-daemon( 2330): [charger_ic] temp_new :28  temp_old :29
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 421135 firstTime = 62654 firstmBatteryCapacity =2205
,E/HwSystemManager( 4066): BgPowerManagerService: conusmPower = 0 result = 0 flag1 =false flag2 = false
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 0 firstTime = 513862 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 30088 firstTime = 513862 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 120325 firstTime = 513862 firstmBatteryCapacity =2205
,E/Thermal-daemon( 2330): [charger_ic] temp_new :29  temp_old :28
,E/Thermal-daemon( 2330): [charger_ic] temp_new :28  temp_old :29
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 150405 firstTime = 513862 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 180486 firstTime = 513862 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 210566 firstTime = 513862 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 272917 firstTime = 513862 firstmBatteryCapacity =2205
,I/HwLauncher( 3835): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3392): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3392): hand message 1
I/TimeManager( 3392): notify time change. size = 2
,I/TimeLayout( 3392): time = 03:15
,I/TimeLayout( 3392): updateDate date = 12/9/2015
,I/TimeLayout( 3392): weekDay = Wednesday
,I/PG Utils( 5714): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/EventLogService( 5714): Aggregate from 1449625406085 (log), 1449625406085 (data)
,I/PG Utils( 5714): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/Finsky  ( 6022): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/art     ( 3018): Explicit concurrent mark sweep GC freed 27590(1298KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/42MB, paused 1.995ms total 179.108ms
,I/PG Utils( 5714): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5714): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/Finsky  ( 6022): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/Finsky  ( 6022): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 332920 firstTime = 513862 firstmBatteryCapacity =2205
E/HwSystemManager( 4066): BgPowerManagerService: conusmPower = 0 result = 0 flag1 =false flag2 = false
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 0 firstTime = 874829 firstmBatteryCapacity =2205
,I/HwLauncher( 3835): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3392): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3392): hand message 1
I/TimeManager( 3392): notify time change. size = 2
I/TimeLayout( 3392): time = 03:16
,I/TimeLayout( 3392): updateDate date = 12/9/2015
,I/TimeLayout( 3392): weekDay = Wednesday
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 30086 firstTime = 874829 firstmBatteryCapacity =2205
,I/AGNSSCONTROL( 2639): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2639): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2639): void kill_timer(timer_t) -- 102: Timer: kill a timer 2876821376
,I/AGNSSCONTROL( 2639): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2876850664
I/AGNSSCONTROL( 2639): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2639): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2639): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
,E/Lss-gw  ( 2639): AllowSendingCellIdsToServer could not remove file. Error 2
,I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
,I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1449627406630, wifi_time:1449594816763
,W/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 624: the wifi info saved time is old for now
I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:0
W/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 678: WIFI MAC ADDRESS COUNT LESS THAN 2
,I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:0
I/AGNSSCONTROL( 2639): int MyLssGwCommunicator::sendRequestWithGeranCellId(EPH_TYPE, int, int, int, int, bool) -- 53: sendRequestWithGeranCellId called, mcc:-1, mnc:-1, lac:0, ci:0
,W/Lss     ( 7586): Ephemeris estimate for SV 3 is too old. It was generated at 1130601600 (sec)
W/Lss     ( 7586): Recalculating ephemeris estimate
,W/Lss     ( 7586): No ephemeris, cannot initialize predictor for SV 3
,W/Lss     ( 7586): Unable to open file /data/gnss/pgps/ephem09 for reading
E/Lss     ( 7586): No ephemeris estimate available for SV 9
,W/Lss     ( 7586): Ephemeris estimate for SV 25 is too old. It was generated at 1131458400 (sec)
W/Lss     ( 7586): Recalculating ephemeris estimate
,E/GpsOrbitPredictor( 7586): initialize: ephemeris toe is within outage, gnss=1, svId=26, toe=[TOC](1,850,237600)/1133632800.000000
,E/Lss     ( 7586): Initializing predictor with ephemeris failed (13)
,E/Lss     ( 7586): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 7586): No reference location.
,W/Lss     ( 7586): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3093 bytes of data
,I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 122
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:850, gpsTime.gpsTOW23b:3342788, nTOWassist:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:2, iode2:68, iode3:68, m0:-1003507211.000000, delta_n:14651.000000, ecc:129334890.000000, ek:0.000000, sqrt_a:2702007865.000000, omega_0:550713357.000000, i0:643835727.000000, omega:-1507415173.000000, omega_dot:-23140.000000, i_dot:1018.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:750.000000, cus:3091.000000, crc:8254.000000, crs:793.000000, cic:227.000000, cis:37.000000, group_delay:-44.000000, af0:1283192.000000, af1:6.000000, af2:0.000000, aodc:68, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:92, iode3:92, m0:14020706.000000, delta_n:13444.000000, ecc:1929824.000000, ek:0.000000, sqrt_a:2701963120.000000, omega_0:573529460.000000, i0:658276324.000000, omega:-2137998424.000000, omega_dot:-22813.000000, i_dot:934.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:550.000000, cus:3224.000000, crc:8540.000000, crs:649.000000, cic:19.000000, cis:9.000000, group_delay:9.000000, af0:234053.000000, af1:57.000000, af2:0.000000, aodc:92, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:1, iode2:108, iode3:108, m0:1027870030.000000, delta_n:11567.000000, ecc:13871390.000000, ek:0.000000, sqrt_a:2701982753.000000, omega_0:-144191325.000000, i0:657460121.000000, omega:-1098547361.000000, omega_dot:-21597.000000, i_dot:372.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1654.000000, cus:5843.000000, crc:5454.000000, crs:-1799.000000, cic:60.000000, cis:-58.000000, group_delay:10.000000, af0:-33266.000000, af1:-13.000000, af2:0.000000, aodc:108, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:2, iode2:104, iode3:104, m0:-2121147715.000000, delta_n:11136.000000, ecc:48045690.000000, ek:0.000000, sqrt_a:2701952407.000000, omega_0:-822419954.000000, i0:676768768.000000, omega:437729641.000000, omega_dot:-22091.000000, i_dot:-993.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3130.000000, cus:2657.000000, crc:9490.000000, crs:-3591.000000, cic:-20.000000, cis:-54.000000, group_delay:-27.000000, af0:755553.000000, af1:26.000000, af2:0.000000, aodc:104, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:2, iode2:148, iode3:148, m0:62279117.000000, delta_n:11720.000000, ecc:71560649.000000, ek:0.000000, sqrt_a:2702024460.000000, omega_0:2058881671.000000, i0:660010733.000000, omega:-1330307320.000000, omega_dot:-22180.000000, i_dot:-37.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2219.000000, cus:6020.000000, crc:5380.000000, crs:2598.000000, cic:-65.000000, cis:40.000000, group_delay:-20.000000, af0:35734.000000, af1:-21.000000, af2:0.000000, aodc:148, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:2, iode2:91, iode3:91, m0:772890552.000000, delta_n:11305.000000, ecc:70845183.000000, ek:0.000000, sqrt_a:2702007293.000000, omega_0:-809606435.000000, i0:677134810.000000, omega:214986415.000000, omega_dot:-22431.000000, i_dot:-1169.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2693.000000, cus:2417.000000, crc:9874.000000, crs:-3229.000000, cic:3.000000, cis:39.000000, group_delay:-22.000000, af0:-126895.000000, af1:31.000000, af2:0.000000, aodc:91, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:1, iode2:74, iode3:74, m0:1159325272.000000, delta_n:15447.000000, ecc:140914269.000000, ek:0.000000, sqrt_a:2701993025.000000, omega_0:1272670247.000000, i0:631984060.000000, omega:-1316144393.000000, omega_dot:-23797.000000, i_dot:-1163.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1224.000000, cus:3675.000000, crc:7331.000000, crs:-1287.000000, cic:-84.000000, cis:-225.000000, group_delay:-24.000000, af0:989687.000000, af1:33.000000, af2:0.000000, aodc:74, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:2, iode2:56, iode3:56, m0:-388097799.000000, delta_n:15377.000000, ecc:43237020.000000, ek:0.000000, sqrt_a:2702004647.000000, omega_0:1237071980.000000, i0:632808057.000000, omega:880468093.000000, omega_dot:-23935.000000, i_dot:-1043.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-829.000000, cus:3579.000000, crc:7439.000000, crs:-1023.000000, cic:0.000000, cis:42.000000, group_delay:-18.000000, af0:809548.000000, af1:25.000000, af2:0.000000, aodc:56, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:3, iode2:107, iode3:107, m0:827847061.000000, delta_n:15872.000000, ecc:68803575.000000, ek:0.000000, sqrt_a:2702003264.000000, omega_0:1273226228.000000, i0:630505195.000000, omega:-1400032214.000000, omega_dot:-24262.000000, i_dot:-1378.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1096.000000, cus:3596.000000, crc:7421.000000, crs:-1265.000000, cic:-77.000000, cis:-18.000000, group_delay:-38.000000, af0:897395.000000, af1:29.000000, af2:0.000000, aodc:107, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:3, iode2:94, iode3:94, m0:-1166928845.000000, delta_n:14034.000000, ecc:33315009.000000, ek:0.000000, sqrt_a:2701992950.000000, omega_0:-1586204565.000000, i0:650391926.000000, omega:208921127.000000, omega_dot:-23792.000000, i_dot:962.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2404.000000, cus:1402.000000, crc:10400.000000, crs:2852.000000, cic:-6.000000, cis:-42.000000, group_delay:6.000000, af0:-19386.000000, af1:-5.000000, af2:0.000000, aodc:94, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:2, iode2:45, iode3:45, m0:624108735.000000, delta_n:11578.000000, ecc:171931097.000000, ek:0.000000, sqrt_a:2702023575.000000, omega_0:-806088945.000000, i0:676222178.000000, omega:-1122946154.000000, omega_dot:-23141.000000, i_dot:-1037.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2841.000000, cus:3119.000000, crc:9299.000000, crs:-3101.000000, cic:-183.000000, cis:-73.000000, group_delay:-24.000000, af0:1045786.000000, af1:23.000000, af2:0.000000, aodc:45, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:79, iode3:79, m0:-1874264941.000000, delta_n:13946.000000, ecc:14135826.000000, ek:0.000000, sqrt_a:2702003799.000000, omega_0:-1524126302.000000, i0:652157397.000000, omega:2142836494.000000, omega_dot:-23727.000000, i_dot:676.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1916.000000, cus:1125.000000, crc:10858.000000, crs:2161.000000, cic:10.000000, cis:-18.000000, group_delay:7.000000, af0:146835.000000, af1:47.000000, af2:0.000000, aodc:79, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:3, iode2:135, iode3:135, m0:-1564049872.000000, delta_n:13707.000000, ecc:97737736.000000, ek:0.000000, sqrt_a:2701994173.000000, omega_0:1345411520.000000, i0:646953909.000000, omega:130690113.000000, omega_dot:-22756.000000, i_dot:-996.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1064.000000, cus:4231.000000, crc:7033.000000, crs:-1205.000000, cic:-39.000000, cis:-100.000000, group_delay:-7.000000, af0:90339.000000, af1:106.000000, af2:0.000000, aodc:135, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 82
W/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 106656
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:4, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:4, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:4, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:4, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:4, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:5, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:6, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:18, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:4, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:4, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:3, usIod:21, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
W/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 90244 firstTime = 874829 firstmBatteryCapacity =2205
,I/ClearcutLoggerApiImpl( 3885): disconnect managed GoogleApiClient
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 150402 firstTime = 874829 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 211950 firstTime = 874829 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 271950 firstTime = 874829 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 451953 firstTime = 874829 firstmBatteryCapacity =2205
E/HwSystemManager( 4066): BgPowerManagerService: conusmPower = -1 result = -7 flag1 =false flag2 = false
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 0 firstTime = 1386188 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 120315 firstTime = 1386188 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 180468 firstTime = 1386188 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 180595 firstTime = 1386188 firstmBatteryCapacity =2205
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 330888 firstTime = 1386188 firstmBatteryCapacity =2205
E/HwSystemManager( 4066): BgPowerManagerService: conusmPower = -1 result = -10 flag1 =false flag2 = false
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 0 firstTime = 1746779 firstmBatteryCapacity =2206
,I/HwSystemManager( 4066): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4066): BgPowerManagerService: mTimes = 60002 firstTime = 1746779 firstmBatteryCapacity =2206
,I/AGNSSCONTROL( 2639): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2639): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2639): void kill_timer(timer_t) -- 102: Timer: kill a timer 2876850664
I/AGNSSCONTROL( 2639): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2876854960
I/AGNSSCONTROL( 2639): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2639): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2639): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
E/Lss-gw  ( 2639): AllowSendingCellIdsToServer could not remove file. Error 2
I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
,I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1449628306628, wifi_time:1449594816763
W/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 624: the wifi info saved time is old for now
I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:0
W/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 678: WIFI MAC ADDRESS COUNT LESS THAN 2
I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:0
I/AGNSSCONTROL( 2639): int MyLssGwCommunicator::sendRequestWithGeranCellId(EPH_TYPE, int, int, int, int, bool) -- 53: sendRequestWithGeranCellId called, mcc:-1, mnc:-1, lac:0, ci:0
,W/Lss     ( 8370): Ephemeris estimate for SV 3 is too old. It was generated at 1130601600 (sec)
W/Lss     ( 8370): Recalculating ephemeris estimate
,W/Lss     ( 8370): No ephemeris, cannot initialize predictor for SV 3
,W/Lss     ( 8370): Unable to open file /data/gnss/pgps/ephem09 for reading
E/Lss     ( 8370): No ephemeris estimate available for SV 9
,W/Lss     ( 8370): Ephemeris estimate for SV 25 is too old. It was generated at 1131458400 (sec)
W/Lss     ( 8370): Recalculating ephemeris estimate
,E/GpsOrbitPredictor( 8370): initialize: ephemeris toe is within outage, gnss=1, svId=26, toe=[TOC](1,850,237600)/1133632800.000000
,E/Lss     ( 8370): Initializing predictor with ephemeris failed (13)
,E/Lss     ( 8370): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 8370): No reference location.
W/Lss     ( 8370): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3093 bytes of data
I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 122
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:850, gpsTime.gpsTOW23b:3354038, nTOWassist:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:2, iode2:68, iode3:68, m0:-1003507211.000000, delta_n:14651.000000, ecc:129334890.000000, ek:0.000000, sqrt_a:2702007865.000000, omega_0:550713357.000000, i0:643835727.000000, omega:-1507415173.000000, omega_dot:-23140.000000, i_dot:1018.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:750.000000, cus:3091.000000, crc:8254.000000, crs:793.000000, cic:227.000000, cis:37.000000, group_delay:-44.000000, af0:1283192.000000, af1:6.000000, af2:0.000000, aodc:68, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:92, iode3:92, m0:14020706.000000, delta_n:13444.000000, ecc:1929824.000000, ek:0.000000, sqrt_a:2701963120.000000, omega_0:573529460.000000, i0:658276324.000000, omega:-2137998424.000000, omega_dot:-22813.000000, i_dot:934.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:550.000000, cus:3224.000000, crc:8540.000000, crs:649.000000, cic:19.000000, cis:9.000000, group_delay:9.000000, af0:234053.000000, af1:57.000000, af2:0.000000, aodc:92, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:1, iode2:108, iode3:108, m0:1027870030.000000, delta_n:11567.000000, ecc:13871390.000000, ek:0.000000, sqrt_a:2701982753.000000, omega_0:-144191325.000000, i0:657460121.000000, omega:-1098547361.000000, omega_dot:-21597.000000, i_dot:372.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1654.000000, cus:5843.000000, crc:5454.000000, crs:-1799.000000, cic:60.000000, cis:-58.000000, group_delay:10.000000, af0:-33266.000000, af1:-13.000000, af2:0.000000, aodc:108, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:2, iode2:104, iode3:104, m0:-2121147715.000000, delta_n:11136.000000, ecc:48045690.000000, ek:0.000000, sqrt_a:2701952407.000000, omega_0:-822419954.000000, i0:676768768.000000, omega:437729641.000000, omega_dot:-22091.000000, i_dot:-993.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3130.000000, cus:2657.000000, crc:9490.000000, crs:-3591.000000, cic:-20.000000, cis:-54.000000, group_delay:-27.000000, af0:755553.000000, af1:26.000000, af2:0.000000, aodc:104, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:2, iode2:148, iode3:148, m0:62279117.000000, delta_n:11720.000000, ecc:71560649.000000, ek:0.000000, sqrt_a:2702024460.000000, omega_0:2058881671.000000, i0:660010733.000000, omega:-1330307320.000000, omega_dot:-22180.000000, i_dot:-37.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2219.000000, cus:6020.000000, crc:5380.000000, crs:2598.000000, cic:-65.000000, cis:40.000000, group_delay:-20.000000, af0:35734.000000, af1:-21.000000, af2:0.000000, aodc:148, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:2, iode2:91, iode3:91, m0:772890552.000000, delta_n:11305.000000, ecc:70845183.000000, ek:0.000000, sqrt_a:2702007293.000000, omega_0:-809606435.000000, i0:677134810.000000, omega:214986415.000000, omega_dot:-22431.000000, i_dot:-1169.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2693.000000, cus:2417.000000, crc:9874.000000, crs:-3229.000000, cic:3.000000, cis:39.000000, group_delay:-22.000000, af0:-126895.000000, af1:31.000000, af2:0.000000, aodc:91, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:1, iode2:74, iode3:74, m0:1159325272.000000, delta_n:15447.000000, ecc:140914269.000000, ek:0.000000, sqrt_a:2701993025.000000, omega_0:1272670247.000000, i0:631984060.000000, omega:-1316144393.000000, omega_dot:-23797.000000, i_dot:-1163.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1224.000000, cus:3675.000000, crc:7331.000000, crs:-1287.000000, cic:-84.000000, cis:-225.000000, group_delay:-24.000000, af0:989687.000000, af1:33.000000, af2:0.000000, aodc:74, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:2, iode2:56, iode3:56, m0:-388097799.000000, delta_n:15377.000000, ecc:43237020.000000, ek:0.000000, sqrt_a:2702004647.000000, omega_0:1237071980.000000, i0:632808057.000000, omega:880468093.000000, omega_dot:-23935.000000, i_dot:-1043.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-829.000000, cus:3579.000000, crc:7439.000000, crs:-1023.000000, cic:0.000000, cis:42.000000, group_delay:-18.000000, af0:809548.000000, af1:25.000000, af2:0.000000, aodc:56, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:3, iode2:107, iode3:107, m0:827847061.000000, delta_n:15872.000000, ecc:68803575.000000, ek:0.000000, sqrt_a:2702003264.000000, omega_0:1273226228.000000, i0:630505195.000000, omega:-1400032214.000000, omega_dot:-24262.000000, i_dot:-1378.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1096.000000, cus:3596.000000, crc:7421.000000, crs:-1265.000000, cic:-77.000000, cis:-18.000000, group_delay:-38.000000, af0:897395.000000, af1:29.000000, af2:0.000000, aodc:107, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:3, iode2:94, iode3:94, m0:-1166928845.000000, delta_n:14034.000000, ecc:33315009.000000, ek:0.000000, sqrt_a:2701992950.000000, omega_0:-1586204565.000000, i0:650391926.000000, omega:208921127.000000, omega_dot:-23792.000000, i_dot:962.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2404.000000, cus:1402.000000, crc:10400.000000, crs:2852.000000, cic:-6.000000, cis:-42.000000, group_delay:6.000000, af0:-19386.000000, af1:-5.000000, af2:0.000000, aodc:94, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:2, iode2:45, iode3:45, m0:624108735.000000, delta_n:11578.000000, ecc:171931097.000000, ek:0.000000, sqrt_a:2702023575.000000, omega_0:-806088945.000000, i0:676222178.000000, omega:-1122946154.000000, omega_dot:-23141.000000, i_dot:-1037.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2841.000000, cus:3119.000000, crc:9299.000000, crs:-3101.000000, cic:-183.000000, cis:-73.000000, group_delay:-24.000000, af0:1045786.000000, af1:23.000000, af2:0.000000, aodc:45, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:79, iode3:79, m0:-1874264941.000000, delta_n:13946.000000, ecc:14135826.000000, ek:0.000000, sqrt_a:2702003799.000000, omega_0:-1524126302.000000, i0:652157397.000000, omega:2142836494.000000, omega_dot:-23727.000000, i_dot:676.000000
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1916.000000, cus:1125.000000, crc:10858.000000, crs:2161.000000, cic:10.000000, cis:-18.000000, group_delay:7.000000, af0:146835.000000, af1:47.000000, af2:0.000000, aodc:79, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:3, iode2:135, iode3:135, m0:-1564049872.000000, delta_n:13707.000000, ecc:97737736.000000, ek:0.000000, sqrt_a:2701994173.000000, omega_0:1345411520.000000, i0:646953909.000000, omega:130690113.000000, omega_dot:-22756.000000, i_dot:-996.000000
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1064.000000, cus:4231.000000, crc:7033.000000, crs:-1205.000000, cic:-39.000000, cis:-100.000000, group_delay:-7.000000, af0:90339.000000, af1:106.000000, af2:0.000000, aodc:135, health:0, toc:17100, toe:17100, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 82
W/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2639): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 106656
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:5, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:6, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:18, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:4, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:3, usIod:23, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
W/AGNSSCONTROL( 2639): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2639): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2639): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/art     ( 3018): Can not find class: Lcom/android/server/AppOpsService$1$1;
,I/art     ( 3018): Can not find class: Lcom/android/server/am/ActivityManagerService$24;
,I/art     ( 3018): Can not find class: Lcom/android/server/pm/PackageManagerService$PackageUsage$1;
,I/art     ( 3018): Can not find class: Lcom/android/server/am/ProcessStatsService$2;
,I/ActivityManager( 3018): filter receiver for action = com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS
,I/HwLauncher( 3835): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3392): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3392): hand message 1
I/TimeManager( 3392): notify time change. size = 2
I/TimeLayout( 3392): time = 03:32
I/TimeLayout( 3392): updateDate date = 12/9/2015
I/TimeLayout( 3392): weekDay = Wednesday
,I/HwSystemManager( 4066): aor:Network Stats Updated
I/HwSystemManager( 4066): aoi:onNetworkStatsUpdated
I/HwSystemManager( 4066): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4066): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4066): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4066): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4066): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4066): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 4066): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/PG Utils( 5714): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/HwSystemManager( 4066): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4066): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4066): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4066): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4066): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 4066): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4066): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4066): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4066): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4066): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4066): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/PG Utils( 5714): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3018): Explicit concurrent mark sweep GC freed 33333(1682KB) AllocSpace objects, 8(244KB) LOS objects, 33% free, 28MB/42MB, paused 1.788ms total 177.780ms
,I/HwSystemManager( 4066): HoldService:uid:10084 pid:6315 died
I/HwSystemManager( 4066): HoldService:oldVersionKey:10084,6315
E/HsmCoreServiceImpl( 3018): onTransact in code is: 102
I/HwSystemManager( 4066): BgPowerManagerService:onProcessDied uid = 10084
I/MediaProcessHandler( 3018): processOp opType: 1, uid: 10084, pid: 6315
W/MediaProcessHandler( 3018): remove target not exist, maybe the UI process: uid: 10084, pid: 6315
,I/HwSystemManager( 4066): HoldService:uid:10050 pid:6424 died
I/HwSystemManager( 4066): BgPowerManagerService:onProcessDied uid = 10050
I/HwSystemManager( 4066): HoldService:oldVersionKey:10050,6424
E/HsmCoreServiceImpl( 3018): onTransact in code is: 102
I/MediaProcessHandler( 3018): processOp opType: 1, uid: 10050, pid: 6424
W/MediaProcessHandler( 3018): remove target not exist, maybe the UI process: uid: 10050, pid: 6424
,W/Lss     ( 8463): No ephemeris, cannot initialize predictor for SV 3
,W/Lss     ( 8463): No ephemeris, cannot initialize predictor for SV 9
,E/GpsOrbitPredictor( 8463): initialize: ephemeris toe is within outage, gnss=1, svId=26, toe=[TOC](1,850,237600)/1133632800.000000
,E/Lss     ( 8463): Initializing predictor with ephemeris failed (13)
,W/Lss     ( 8463): No ephemeris, cannot initialize predictor for SV 16
,W/Lss     ( 8463): Ephemeris estimate for SV 3 is too old. It was generated at 1130601600 (sec)
W/Lss     ( 8463): Recalculating ephemeris estimate
,W/Lss     ( 8463): No ephemeris, cannot initialize predictor for SV 3
,W/Lss     ( 8463): Unable to open file /data/gnss/pgps/ephem09 for reading
E/Lss     ( 8463): No ephemeris estimate available for SV 9
,W/Lss     ( 8463): Ephemeris estimate for SV 25 is too old. It was generated at 1131458400 (sec)
W/Lss     ( 8463): Recalculating ephemeris estimate
,E/GpsOrbitPredictor( 8463): initialize: ephemeris toe is within outage, gnss=1, svId=26, toe=[TOC](1,850,237600)/1133632800.000000
,E/Lss     ( 8463): Initializing predictor with ephemeris failed (13)
,E/Lss     ( 8463): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 8463): No reference location.
W/Lss     ( 8463): Cannot calculate visible satellites. Returning all odd satellite ids
,TIME-OUT KILL (timeout was 1800000ms)
```
