#### Test 50650278eab32a5_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/Finsky  ( 4906): [1] 5.onFinished: Scheduling replication attempt 2.
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 157254048903; DSPS: 5293910; Offset : -4318653054
,D/AndroidRuntime( 6126): 
D/AndroidRuntime( 6126): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6126): CheckJNI is OFF
D/AndroidRuntime( 6126): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1032): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1973): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1032): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{13131cc6 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{13131cc6 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1032): AppWindowTokenEx init.. 
E/GBMv2   (  339): DFP En is all cleared set to be enabled
I/ActivityManager( 1032): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6145 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6126): Shutting down VM
V/ActivityManager( 1032): Display changed displayId=0
D/DSDPConnection( 1869): Display #0 changed.
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{3361805f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{3e1acaac co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6145): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6145): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6145): Loading: webviewchromium
I/LibraryLoader( 6145): Time to load native libraries: 3 ms (timestamps 7921-7924)
I/LibraryLoader( 6145): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6145): Binding Chromium to main looper Looper (main, tid 1) {194bb48}
I/LibraryLoader( 6145): Expected native library version number "",actual native library version number ""
I/chromium( 6145): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6145): Initializing chromium process, renderers=0
W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6145): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  316): registerClient() client 0xb558a480, uid 10311
W/chromium( 6145): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6145): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6145): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3aa56320:true
I/Adreno-EGL( 6145): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6145): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6145): Build Date: 12/12/14 금
I/Adreno-EGL( 6145): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6145): Remote Branch: 
I/Adreno-EGL( 6145): Local Patches: 
I/Adreno-EGL( 6145): Reconstruct Branch: 
D/BluetoothAdapter( 6145): 521395681: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6145): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6145): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6145): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6145): CordovaWebView is running on device made by: LGE
W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6145): Render dirty regions requested: true
I/OpenGLRenderer( 6145): Initialized EGL, version 1.4
D/OpenGLRenderer( 6145): Enabling debug mode 0
D/Atlas   ( 6145): Validating map...
D/SplitWindow( 1032): check instance of lgWin Window{2883ce5a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1eebd7a0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1449): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1449): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1449):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1449): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6145): LgDataFeature() Constructor: none
D/LgDataFeature( 6145): LgDataFeature() Constructor Done, null
I/Timeline( 6145): Timeline: Activity_idle id: android.os.BinderProxy@28bf0151 time:158332
I/ActivityManager( 1032): Displayed com.test.thalitest/.MainActivity: +557ms (total +652ms)
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{390bc487 u0 com.test.thalitest/.MainActivity t4} time:158357
I/chromium( 6145): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6145): 
D/JsMessageQueue( 6145): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6145): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435107072
D/JX-Cordova( 6145): jxcore cordova android initializing
E/GBMv2   (  339): DFP En is all cleared set to be enabled
E/GBMv2   (  339): Set value is all cleared set the max
I/GBMv2   (  339): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6145): Initializing JXcore engine
W/jxcore-log( 6145): JXcore engine is ready
,W/jxcore-log( 6145): Starting JXcore engine
W/.test.thalitest( 6145): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[10417]" dev="sockfs" ino=10417 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6145): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 6145): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9769]" dev="sockfs" ino=9769 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6145): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6145): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[30436]" dev="sockfs" ino=30436 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6145): Background sticky concurrent mark sweep GC freed 123906(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.617ms total 115.929ms
,W/jxcore-log( 6145): Platform android
W/jxcore-log( 6145): 
W/jxcore-log( 6145): Process ARCH arm
W/jxcore-log( 6145): 
,I/jxcore-log( 6145): JXcore Cordova bridge is ready!
I/jxcore-log( 6145): 
W/jxcore-log( 6145): JXcore engine is started
,I/chromium( 6145): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6145): 
,E/jxcore  ( 6145): Error!: missing ) after argument list
E/jxcore  ( 6145): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6145): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 6145): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager( 1032): Killing 5819:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10008/pid_5819/cgroup.procs: No such file or directory
,W/PluginManager( 6145): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
E/GBMv2   (  339): DFP En is all cleared set to be enabled
,D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{830e375 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{39caf0a co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
W/ScreenOrientationListener( 6145): Removing an inexistent observer!
I/[LGHome]EVENT( 2082): [Launcher.java:5338:onStart()]onStart
,I/[LGHome]EVENT( 2082): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2082): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1938): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2682): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2082): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2082): [Launcher.java:1056:onResume()]onResume end
D/InputDispatcher( 1032): Window went away: Window{2883ce5a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1032): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6223 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2082): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1938): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2682): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2682): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2082): , create_time: 1430558575574
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2082): , create_time: 1430558575600
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: new_feature_1111111111111_1449660465987
I/GBoardWebViewUtils( 2082): , create_time: 1449660466862
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature.html?id=new_feature_1111111111111_1449660465987&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
,D/WallpaperManager( 2082): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/PhoneStatusBar( 1449): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1eebd7a0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1449): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1449):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1449): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/art     ( 6223): Almond Protected OAT
,D/WeatherApplication( 6223): removeAccount
,D/WeatherApplication( 6223): Account.length = 0
E/WeatherApplication( 6223): OPERATOR:OPEN
D/WeatherAncestor( 6223): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:46:20
D/Weather.Utils( 6223): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6223): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 6223): 2 : This is isUpdating : false
D/Weather.Utils( 6223): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6223): 2 : All the weather widget is gone.
D/WeatherAncestor( 6223): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:46:20
I/ActivityManager( 1032): Killing 5490:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_5490/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2082): [Launcher.java:5349:onStop()]onStop
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{2c509c75 u0 com.lge.launcher2/.Launcher t3} time:161292
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2082): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2588): onStartCommand(). Type : 8
D/[Concierge]Service( 2588): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/[Concierge]Service( 2588): Update widget ID : 11
D/[Concierge]WidgetView( 2082): change position of spinner
I/[Concierge]WidgetView( 2082): initWebView(). Time : 1449668780499
D/[Concierge]Service( 2588): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2082): Return exist ConciergeWebView. Reuse : 1065993972
D/[Concierge]WidgetView( 2082): State Change : null -> AccInBeforeState
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2082): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1035dc50
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2082): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2082): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2082): Widget kill message received. Destory myself. My : 1449668646965, New one : 1449668780499
D/[Concierge]WidgetView( 2082): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2082): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2082): Timeline: Activity_idle id: android.os.BinderProxy@2f7ee711 time:161602
,I/chromium( 2082): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2082): onReloaded()
,I/GBoardWebViewClient( 2082): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2682): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/BoardContentProvider( 2682): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1938): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2682): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2682): onEvent() : ACTION_BOARD_ENABLED
,I/ActivityManager( 1032): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6262 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActionManagerService( 1938): notifyUserLog: 1000001
V/BoardContentProvider( 2682): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2682): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2682): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2682): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2682): onSettingEvent() : GBoard On - add scheduler - 0
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449660465987&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449660465987&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,V/FormManager( 6262): BoardCategory : com.lge.intent.category.gboard.MYWELLNESS, true
,I/ActivityManager( 1032): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6286 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
W/FormManager( 6262): Network not available. Please check & try again.
,V/FormManager( 6262): Network unavailable.
,V/FormManager( 6262): Network unavailable.
I/ActivityManager( 1032): Killing 5511:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10019/pid_5511/cgroup.procs: No such file or directory
,E/ActivityThread( 6286): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6286): No ProfileInfo entries
I/LG Account v2.2( 6286): isEnabled: false
I/Feature ( 6286): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6286): [Lifetracker]Country: EU
I/Feature ( 6286): [Lifetracker]Operator: OPEN
I/Feature ( 6286): [Lifetracker]Ranking support: false
I/Feature ( 6286): [Lifetracker]Comfort support: false
I/Feature ( 6286): [Lifetracker]Accessory: true
I/Feature ( 6286): [Lifetracker]Health device: true
I/Feature ( 6286): [Lifetracker]Extra Pedometer: false
I/Feature ( 6286): [Lifetracker]Blood glucose device: false
I/Feature ( 6286): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 6286): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
I/GBoardStateUtil( 6286): [GBoardStateUtil] isEnableLGHealthofGBoard : true
,I/CoreEventReceiver( 6286): gboardCategory : com.lge.intent.category.gboard.MYWELLNESS, gboardState : true
I/ActivityManager( 1032): Killing 5844:com.lge.email/u0a23 (adj 15): empty #17
I/LIA_Informant_LogCore( 2682): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2682): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
,W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_5844/cgroup.procs: No such file or directory
,I/LIA_MrGDBLogger_LogCore( 2682): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2682): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
I/LIA_S4URecommender_LogCore( 2682): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2682): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
D/CoreEventReceiver( 6286): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
,V/FormManager( 6262): BoardCategory : com.lge.intent.category.gboard.DOYOUKNOW, true
I/GBoardStateUtil( 6286): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6286): gboardCategory : com.lge.intent.category.gboard.DOYOUKNOW, gboardState : true
I/LIA_Informant_LogCore( 2682): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2682): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_Informant_BoardStateUtil( 2682): defaultHomePackage : com.lge.launcher2
D/LIA_Informant_TaskActivator( 2682): DefaultHomeCondition is satisfied
V/FormManager( 6262): Network unavailable.
,W/FormManager( 6262): Network not available. Please check & try again.
V/FormManager( 6262): Network unavailable.
I/LIA_Informant_BoardStateUtil( 2682): isEnabledConciergeBoard() : count > 0 - true
D/LIA_Informant_TaskActivator( 2682): BoardCondition is satisfied
W/LIA_Informant_TaskActivator( 2682): setActivation() : Informant Task - ACTIVATION
D/LIA_Informant_LGIntelligentAgent( 2682): activateLIAService : Informant / true
I/LIA_Informant_LIATaskLoader( 2682): getTaskSdkClassName : com.lge.ia.LIAInformant
D/LIA_Informant_LIATaskLoader( 2682): classLoad - TargetClass : com.lge.ia.LIAInformant
I/LIA_Informant_LIATaskLoader( 2682): createLIAService - Success
I/LIA_Informant_LGIntelligentAgent( 2682): activateLIAService : startService success. (You may need to check whether its property has changed or not!)
D/LIA_Informant_LIARemoteService( 2682): onStartCommand() : LIARemoteService started! - (Id :5), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
I/LIA_Informant_InformantService( 2682): isNowInActivationCondition()
,I/LIA_Informant_BoardStateUtil( 2682): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 2682): ActivationConditionHandler : LGHome condition is true
I/GBoardtInterface( 2082): exportHTML()
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 23678(1118KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 3.147ms total 89.601ms
,I/LIA_Informant_BoardStateUtil( 2682): isEnabledConciergeBoard() : count > 0 - true
,I/LIA_Informant_ActivationConditionHandler( 2682): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 2682): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
I/LIA_Informant_InformantService( 2682): getTaskPropertiesAtFirstStarting()
D/LIA_Informant_LIARemoteService( 2682): --> LIA task activation intent from com.lge.ia.task.informant for Informant(activation: true)
D/LIA_Informant_LIARemoteService( 2682): updateTaskProperty() : 
I/LIA_Informant_LIARemoteService( 2682): --> LIA task activation intent from com.lge.ia.task.informant, but it's same as the current setting or couldn't chagne it so just passed !! (Informant activation : true)
I/LIA_MrGDBLogger_LogCore( 2682): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2682): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_S4URecommender_LogCore( 2682): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2682): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/GBoardtInterface( 2082): exportHTML()
I/GBoardtInterface( 2082): exportHTML()
,E/GBMv2   (  339): DFP En is all cleared set to be enabled
E/GBMv2   (  339): Set value is all cleared set the max
I/GBMv2   (  339): DFP Enabled. Ignore VFP set
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 2082): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 2082): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
I/GBoardtInterface( 2082): onAnimationFinished
,I/GBoardtInterface( 2082): onAnimationFinished
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 177255655769; DSPS: 5949323; Offset : -4318663515
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{41c820a type 0 when 1449668787158 com.android.vending} when 1449668787158
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4906): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4906): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4906): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 197257282584; DSPS: 6604736; Offset : -4318653950
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=34134441, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{3eef92e5 type 0 when 1449668821432 com.android.vending} when 1449668821432
,D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=34134441 [*alarm*], flags=0x0
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2139): Explicit concurrent mark sweep GC freed 22319(1259KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.408ms total 56.780ms
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4906): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4906): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4906): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 217259168462; DSPS: 7260158; Offset : -4318660396
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{384d813f type 2 when 179610 com.google.android.gms} when 179610
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 237261655330; DSPS: 7915600; Offset : -4318675892
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{1343ff55 type 0 when 1449668849462 com.android.vending} when 1449668849462
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{3c7dcd6a type 2 when 237776 android} when 237776
V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{2022f25b type 2 when 244515 com.google.android.gms} when 244515
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4906): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4906): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4906): [1] 5.onFinished: Scheduling replication attempt 5.
,I/[SystemUI]LGPowerUI( 1449): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1449): On Skip Timer : true
,D/WifiController( 1032): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1449): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,D/LEDHandler( 1973): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1973): Battery Level Remaining: 100%
D/LEDHandler( 1973): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1449): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3988): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3988): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 257263651989; DSPS: 8571025; Offset : -4318662901
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
,I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=34134441, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{d5c651a type 0 when 1449668884279 com.android.vending} when 1449668884279
,D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=34134441 [*alarm*], flags=0x0
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4906): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4906): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4906): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 277265274324; DSPS: 9226438; Offset : -4318658049
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 297266894734; DSPS: 9881851; Offset : -4318654941
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 317268624621; DSPS: 10537268; Offset : -4318664478
I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 337270866907; DSPS: 11192702; Offset : -4318680596
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{b78daee V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 357272541638; DSPS: 11848116; Offset : -4318653867
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 377274269963; DSPS: 12503533; Offset : -4318664888
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 397275733550; DSPS: 13158941; Offset : -4318666274
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 417277327240; DSPS: 13814353; Offset : -4318659498
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 437278992386; DSPS: 14469768; Offset : -4318672897
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 457281243944; DSPS: 15125202; Offset : -4318679432
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 477282858155; DSPS: 15780614; Offset : -4318652135
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 497284326637; DSPS: 16436023; Offset : -4318679067
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=34134441, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{35a0a82b type 2 when 492919 com.google.android.gms} when 492919
,D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=34134441 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 517285810639; DSPS: 17091431; Offset : -4318659908
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 537287272402; DSPS: 17746839; Offset : -4318662937
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 557289022134; DSPS: 18402256; Offset : -4318652837
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 577291383950; DSPS: 19057694; Offset : -4318671418
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 597292927327; DSPS: 19713104; Offset : -4318653765
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 617294385497; DSPS: 20368512; Offset : -4318660594
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 637296082155; DSPS: 21023928; Offset : -4318672920
,I/ActivityManager( 1032): Killing 5536:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_5536/cgroup.procs: No such file or directory
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{b78daee V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 657298174596; DSPS: 21679356; Offset : -4318655597
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 677299690943; DSPS: 22334766; Offset : -4318665024
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 697302370519; DSPS: 22990214; Offset : -4318670995
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 717304216553; DSPS: 23645634; Offset : -4318656120
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 737305726180; DSPS: 24301044; Offset : -4318672346
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 757307193620; DSPS: 24956452; Offset : -4318669749
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 777308676061; DSPS: 25611861; Offset : -4318682800
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 797310745845; DSPS: 26267288; Offset : -4318657511
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 817312259690; DSPS: 26922698; Offset : -4318669467
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 837313709059; DSPS: 27578105; Offset : -4318654659
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 857315187645; DSPS: 28233514; Offset : -4318671383
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 877316939721; DSPS: 28888931; Offset : -4318658782
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 897318713463; DSPS: 29544349; Offset : -4318655086
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 917320830278; DSPS: 30199779; Offset : -4318674319
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 937322641261; DSPS: 30855198; Offset : -4318664108
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{b78daee V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 957324477919; DSPS: 31510618; Offset : -4318658374
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 977326030620; DSPS: 32166029; Offset : -4318662148
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=34134441, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{348460ce type 0 when 1449669238046 com.google.android.gms} when 1449669238046
V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{1f302bef type 2 when 996841 com.google.android.gms} when 996841
,D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=34134441 [*alarm*], flags=0x0
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/EventLogService( 2328): Aggregate from 1449667437978 (log), 1449667437978 (data)
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 997327387644; DSPS: 32821434; Offset : -4318677659
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1017329127167; DSPS: 33476851; Offset : -4318678368
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1037331199921; DSPS: 34132278; Offset : -4318650291
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
,I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1057332699548; DSPS: 34787688; Offset : -4318676518
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1077334158030; DSPS: 35443095; Offset : -4318652465
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1097335902710; DSPS: 36098513; Offset : -4318677701
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1449): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1449): On Skip Timer : true
,D/WifiController( 1032): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1449): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1973): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1973): Battery Level Remaining: 100%
D/LEDHandler( 1973): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3988): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3988): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1117337646035; DSPS: 36753930; Offset : -4318673877
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1137339105298; DSPS: 37409338; Offset : -4318679458
,I/[SystemUI]LGPowerUI( 1449): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1449): On Skip Timer : true
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1157341087792; DSPS: 38064762; Offset : -4318650037
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1177342611950; DSPS: 38720173; Offset : -4318682172
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1197344420016; DSPS: 39375592; Offset : -4318674747
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1217345875736; DSPS: 40030999; Offset : -4318653354
,I/UsageStatsService( 1032): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1237347379374; DSPS: 40686409; Offset : -4318675543
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 27726(1295KB) AllocSpace objects, 8(512KB) LOS objects, 33% free, 44MB/66MB, paused 1.948ms total 104.346ms
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{b78daee V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1257348947909; DSPS: 41341820; Offset : -4318663663
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1277351240402; DSPS: 41997255; Offset : -4318659885
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1297352739248; DSPS: 42652664; Offset : -4318656296
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1317354208303; DSPS: 43308072; Offset : -4318652241
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1337355919285; DSPS: 43963489; Offset : -4318680683
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1357357411567; DSPS: 44618897; Offset : -4318653140
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1377358874842; DSPS: 45274305; Offset : -4318654892
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1397360961085; DSPS: 45929734; Offset : -4318674232
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1417362489880; DSPS: 46585144; Offset : -4318671341
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1437364316382; DSPS: 47240564; Offset : -4318675686
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1457366311062; DSPS: 47895989; Offset : -4318664830
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1477368069440; DSPS: 48551407; Offset : -4318676446
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1497369527661; DSPS: 49206814; Offset : -4318652578
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1517371304476; DSPS: 49862233; Offset : -4318676325
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1537372809469; DSPS: 50517642; Offset : -4318666668
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{b78daee V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1557374377742; DSPS: 51173053; Offset : -4318654791
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1577375891902; DSPS: 51828463; Offset : -4318666589
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
,I/[SystemUI]Clock( 1449): called onTimeUpdated()
I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1597377636113; DSPS: 52483880; Offset : -4318661827
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1617379288552; DSPS: 53139294; Offset : -4318657363
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1637381721671; DSPS: 53794734; Offset : -4318665521
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1657383202965; DSPS: 54450143; Offset : -4318679639
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1677384651499; DSPS: 55105550; Offset : -4318665485
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1697386608991; DSPS: 55760974; Offset : -4318661170
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1717388086744; DSPS: 56416383; Offset : -4318678830
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1737389544809; DSPS: 57071790; Offset : -4318655038
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1757391076885; DSPS: 57727201; Offset : -4318679334
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1777393101252; DSPS: 58382627; Offset : -4318669101
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1797394284005; DSPS: 59038026; Offset : -4318676585
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1817395808268; DSPS: 59693436; Offset : -4318678174
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1449): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1449): On Skip Timer : true
,D/WifiController( 1032): battery changed pluggedType: 2
,D/LEDHandler( 1973): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1973): Battery Level Remaining: 100%
D/LEDHandler( 1973): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1449): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1449): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3988): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3988): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1837397427218; DSPS: 60348849; Offset : -4318676605
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1032): Prepared write state in 11ms
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4906): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4906): Ignoring header User-Agent because its value was null.
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{b78daee V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ProcessStatsService( 1032): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-11-25.bin
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1857399006013; DSPS: 61004260; Offset : -4318654283
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1877401372569; DSPS: 61659698; Offset : -4318667968
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1897403129331; DSPS: 62315116; Offset : -4318681253
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1917404871876; DSPS: 62970533; Offset : -4318678313
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1937406332649; DSPS: 63625940; Offset : -4318651815
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1957407822278; DSPS: 64281349; Offset : -4318657598
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1977409314457; DSPS: 64936758; Offset : -4318660756
,TIME-OUT KILL (timeout was 1800000ms),D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1997411141481; DSPS: 65592178; Offset : -4318664733
D/AndroidRuntime( 6715): 
D/AndroidRuntime( 6715): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6715): CheckJNI is OFF
D/AndroidRuntime( 6715): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1032): Killing 6145:com.test.thalitest/u0a311 (adj 15): stop com.test.thalitest
W/PackageSettings( 1032): Skipping PackageSetting{3bac443e com.example.hello/10318} due to missing metadata
I/ActivityManager( 1032): Killing 5585:com.google.android.apps.plus/u0a97 (adj 15): empty for 1881s
I/ActivityManager( 1032): Killing 5892:com.google.android.apps.docs/u0a61 (adj 15): empty for 1881s
I/ActivityManager( 1032): Killing 5556:com.lge.lockscreensettings/u0a80 (adj 15): empty for 1881s
I/ActivityManager( 1032): Killing 5873:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty for 1881s
I/ActivityManager( 1032): Killing 5166:com.wsandroid.suite.lge/1000 (adj 15): empty for 1882s
I/ActivityManager( 1032): Killing 5740:com.android.defcontainer/u0a4 (adj 15): empty for 1882s
W/ActivityManager( 1032): Spurious death for ProcessRecord{aef0960 6145:com.test.thalitest/u0a311}, curProc for 6145: null
I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/art     ( 2082): Explicit concurrent mark sweep GC freed 11244(798KB) AllocSpace objects, 12(5MB) LOS objects, 35% free, 57MB/89MB, paused 1.022ms total 43.678ms
I/art     ( 4272): Explicit concurrent mark sweep GC freed 15081(881KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 443us total 53.463ms
W/libprocessgroup( 1032): failed to open /acct/uid_10097/pid_5585/cgroup.procs: No such file or directory
W/libprocessgroup( 1032): failed to open /acct/uid_10061/pid_5892/cgroup.procs: No such file or directory
W/libprocessgroup( 1032): failed to open /acct/uid_10080/pid_5556/cgroup.procs: No such file or directory
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5873/cgroup.procs: No such file or directory
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5166/cgroup.procs: No such file or directory
W/libprocessgroup( 1032): failed to open /acct/uid_10004/pid_5740/cgroup.procs: No such file or directory
D/KeyguardModel( 1449): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1816): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2044): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2682): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/BroadcastQueue( 1032): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/BroadcastQueue( 1032): android.os.RemoteException: app.thread must not be null
W/BroadcastQueue( 1032): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:454)
W/BroadcastQueue( 1032): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:540)
W/BroadcastQueue( 1032): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:588)
W/BroadcastQueue( 1032): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:156)
W/BroadcastQueue( 1032): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 1032): 	at android.os.Looper.loop(Looper.java:135)
W/BroadcastQueue( 1032): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 1032): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
W/System.err( 4219): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4219): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4219): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4219): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4219): 	at android.os.Handler.handleCallback(Handler.java:739)
I/ActivityManager( 1032): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6746 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/System.err( 4219): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4219): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4219): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4219): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4219): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/SplitUIManager( 1886): split_name #11 / not available #0
D/SplitUIService( 1886): removed split : 
I/ActivityManager( 1032): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6765 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/SplitUIManager( 1886): split_name #11 / not available #0
I/SplitUIService( 1886): split app #11
I/[SystemUI]QSlideListController( 1449): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     ( 1032): Explicit concurrent mark sweep GC freed 19684(1317KB) AllocSpace objects, 8(618KB) LOS objects, 33% free, 44MB/66MB, paused 1.537ms total 139.042ms
I/art     ( 1032): WaitForGcToComplete blocked for 126.408ms for cause Explicit
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1449): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1449): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 6746): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
D/administrator( 1032): Handling package changes for user 0
I/LockScreenSettings( 6765): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1449): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1449): createShortcutInfo...
D/KeyguardModel( 1449): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1449): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1449): createShortcutInfo...
D/PluginManager( 6746): init()
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1449): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1449): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1449): createShortcutInfo...
I/ActivityManager( 1032): Killing 5943:com.lge.eula/1000 (adj 15): empty for 1881s
I/NotificationService( 1032): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1032): Receieved: android.intent.action.PACKAGE_REMOVED
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
I/art     ( 1032): Explicit concurrent mark sweep GC freed 4325(234KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.643ms total 168.839ms
D/KeyguardModel( 1449): handleShortcutListChanged...
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5943/cgroup.procs: No such file or directory
D/TaskPersister( 1032): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1449): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1449): createShortcutInfo...
D/KeyguardModel( 1449): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1449): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1449): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1449): createShortcutInfo...
W/ResourceType( 1449): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1449): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1449): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1449): createShortcutInfo...
D/KeyguardModel( 1449): handleShortcutListChanged...
D/AndroidRuntime( 6715): Shutting down VM
W/ExternalStrings( 6746): load override strings
W/ExternalStrings( 6746): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6746): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6746): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6746): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6746): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6746): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6746): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6746): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6746): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6746): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6746): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6746): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6746): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6746): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 6746): onCreate
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/Signer  ( 6746): override build config not found
D/Signer  ( 6746): value of property debug is false
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6746): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6746): Create singleton instance
D/LGMDMWrapper( 6746): LG MDM library v4.0.0 is available on this device.
D/PostponalbeReceiver( 6746): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 6746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6794 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 5968:com.lge.bnr/1000 (adj 15): empty for 1881s
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5968/cgroup.procs: No such file or directory

```
