#### Test 50650278cc6513d_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
I/appproc ( 6759): CLASSPATH=/system/framework/am.jar
I/appproc ( 6759): Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
I/appproc ( 6759): app_process:number,5,0
I/AndroidRuntime( 6759): readDownloadBoosterConfig: 'false'
I/        ( 6759): power log dlsym ok
E/android_hardware_fm.cpp( 6759): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6759): ========64bit long size = 8
E/FM_HAL  ( 6759): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 6759): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6759): 
I/fm_hisi ( 6759): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6759): 
I/fm_hisi ( 6759): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6759): 
E/android_hardware_fm.cpp( 6759): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 2948): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2948): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2948): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2948): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwSystemManager( 3973): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3768): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3768): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3768): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 3973): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 3973): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwLauncher( 3768): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3768): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/WebViewFactory( 6779): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 6779): Loading: webviewchromium
I/LibraryLoader( 6779): Time to load native libraries: 45 ms (timestamps 1978-2023)
I/LibraryLoader( 6779): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 6779): Expected native library version number "",actual native library version number ""
I/chromium( 6779): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6779): Initializing chromium process, renderers=0
W/art     ( 6779): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6779): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6779): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6779): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 6779): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/chromium( 6779): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6779): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 6779): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 6779): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6779): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 6779): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6779): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6779): Can not find class: Landroid/app/ViewStub;
W/art     ( 6779): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6779): Attempt to remove local handle scope entry from IRT, ignoring
,I/PhoneStatusBar( 3273): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/PhoneStatusBar( 3273): shouldTranslucent:true
,I/PhoneStatusBar( 3273): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/OpenGLRenderer( 6779): Initialized EGL, version 1.4
,I/ActivityManager( 2948): Displayed com.test.thalitest/.MainActivity: +1s84ms (total +1s155ms)
,W/IInputConnectionWrapper( 6779): showStatusIcon on inactive InputConnection
,I/chromium( 6779): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6779): 
,I/art     ( 5738): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
,W/jxcore-log( 6779): Initializing JXcore engine
W/jxcore-log( 6779): JXcore engine is ready
,W/jxcore-log( 6779): Starting JXcore engine
,W/jxcore-log( 6779): Platform android
W/jxcore-log( 6779): 
W/jxcore-log( 6779): Process ARCH arm
W/jxcore-log( 6779): 
,I/art     ( 2948): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/jxcore-log( 6779): JXcore Cordova bridge is ready!
I/jxcore-log( 6779): 
W/jxcore-log( 6779): JXcore engine is started
,E/jxcore  ( 6779): Error!: missing ) after argument list
E/jxcore  ( 6779): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6779): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,W/PluginManager( 6779): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 118ms. Plugin should use CordovaInterface.getThreadPool().
,I/HwSystemManager( 3973): AppLockService:applock password not initial or function is closed
,I/HwSystemManager( 3973): AppManager:getNetAppInfoFromDB cursor lenth = 1
,I/HwSystemManager( 3973): HoldService:uid:10041 pid:5827 died
I/HwSystemManager( 3973): HoldService:oldVersionKey:10041,5827
I/HwSystemManager( 3973): BgPowerManagerService:onProcessDied uid = 10041
E/HsmCoreServiceImpl( 2948): onTransact in code is: 102
I/MediaProcessHandler( 2948): processOp opType: 1, uid: 10041, pid: 5827
W/MediaProcessHandler( 2948): remove target not exist, maybe the UI process: uid: 10041, pid: 5827
,W/ScreenOrientationListener( 6779): Removing an inexistent observer!
,E/Thermal-daemon( 2332): [ap] temp_new :29  temp_old :30
,I/ActivityManager( 2948): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,E/Thermal-daemon( 2332): [charger_ic] temp_new :29  temp_old :30
,I/HwSystemManager( 3973): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3973): BgPowerManagerService: mTimes = 60181 firstTime = 62649 firstmBatteryCapacity =2205
,I/HwLauncher( 3768): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3273): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3273): hand message 1
I/TimeManager( 3273): notify time change. size = 2
I/TimeLayout( 3273): time = 15:57
,I/TimeLayout( 3273): updateDate date = 12/8/2015
,I/TimeLayout( 3273): weekDay = Tuesday
,I/HwSystemManager( 3973): InputMethodStringPredicate:InputMethodStringPredicate :: inputMethods = [com.nuance.swype.emui, com.nuance.swype.input.HuaweiIME, com.android.inputmethod.latin]
,I/HwSystemManager( 3973): LauncherPredicate:get default launcher is null, set hwlauncher
,I/HwSystemManager( 3973): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3973): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3973): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3973): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3973): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3973): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3973): SmartMemoryCleanService:SMCSDataManager.checkAvailMemory.: availMem 1186611200 [332800000,437657600,542515200]
I/HwSystemManager( 3973): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor start
,I/HwSystemManager( 3973): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor end
,I/ClearcutLoggerApiImpl( 3593): disconnect managed GoogleApiClient
,I/ActivityManager( 2948): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,I/HwLauncher( 3768): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3273): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3273): hand message 1
I/TimeManager( 3273): notify time change. size = 2
I/TimeLayout( 3273): time = 15:58
,I/TimeLayout( 3273): updateDate date = 12/8/2015
,I/TimeLayout( 3273): weekDay = Tuesday
,E/Thermal-daemon( 2332): [ap] temp_new :28  temp_old :29
,I/art     ( 2948): Can not find class: Lcom/android/server/power/PowerManagerService$5$1;
,W/System.err( 2948): java.net.UnknownHostException: Unable to resolve host "www.google.com": No address associated with hostname
,W/System.err( 2948): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
W/System.err( 2948): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 2948): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
W/System.err( 2948): 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
W/System.err( 2948): 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
W/System.err( 2948): 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
W/System.err( 2948): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
W/System.err( 2948): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
W/System.err( 2948): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
W/System.err( 2948): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
W/System.err( 2948): 	at com.android.server.power.PowerManagerService.isGoogleConnectOK(PowerManagerService.java:3530)
W/System.err( 2948): 	at com.android.server.power.PowerManagerService.access$6500(PowerManagerService.java:107)
W/System.err( 2948): 	at com.android.server.power.PowerManagerService$5$1.run(PowerManagerService.java:3502)
W/System.err( 2948): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 2948): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 2948): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 2948): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:438)
W/System.err( 2948): 	... 12 more
,I/art     ( 2948): Can not find class: Lcom/android/server/am/ActivityManagerService$31$1;
,I/art     ( 2948): Can not find class: Lcom/android/server/am/ActivityManagerService$33$1;

```
