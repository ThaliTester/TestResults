#### Test 50650278352fc1f_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 294391109032; DSPS: 9787704; Offset : -4321853517
,D/AndroidRuntime( 6098): 
D/AndroidRuntime( 6098): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6098): CheckJNI is OFF
D/AndroidRuntime( 6098): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1054): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1960): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1054): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1054): setTaskToReturnTo : TaskRecord{16cf66ac #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1054): setTaskToReturnTo : TaskRecord{16cf66ac #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1054): AppWindowTokenEx init.. 
E/GBMv2   (  346): DFP En is all cleared set to be enabled
I/ActivityManager( 1054): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6117 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6098): Shutting down VM
D/DSDPConnection( 1865): Display #0 changed.
V/ActivityManager( 1054): Display changed displayId=0
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{212aa45a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{14d7968b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6117): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6117): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6117): Loading: webviewchromium
I/LibraryLoader( 6117): Time to load native libraries: 5 ms (timestamps 3808-3813)
,I/LibraryLoader( 6117): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6117): Binding Chromium to main looper Looper (main, tid 1) {271f69d7}
,I/LibraryLoader( 6117): Expected native library version number "",actual native library version number ""
,I/chromium( 6117): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6117): Initializing chromium process, renderers=0
,W/art     ( 6117): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6117): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  318): registerClient() client 0xb102ab20, uid 10311
,W/chromium( 6117): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6117): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6117): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1054): Message: 20
D/BluetoothManagerService( 1054): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d8e6dd6:true
D/BluetoothAdapter( 6117): 770294468: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6117): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6117): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6117): Build Date: 12/12/14 금
I/Adreno-EGL( 6117): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6117): Remote Branch: 
I/Adreno-EGL( 6117): Local Patches: 
I/Adreno-EGL( 6117): Reconstruct Branch: 
,W/chromium( 6117): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6117): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6117): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6117): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6117): CordovaWebView is running on device made by: LGE
,W/art     ( 6117): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6117): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6117): Render dirty regions requested: true
I/OpenGLRenderer( 6117): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6117): Enabling debug mode 0
W/ActivityManager( 1054): Activity pause timeout for ActivityRecord{3c9f4f75 u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 6117): Validating map...
,D/SplitWindow( 1054): check instance of lgWin Window{15d160e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6117): LgDataFeature() Constructor: none
D/LgDataFeature( 6117): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1054): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1054): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx( 1054): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1054): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1054): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3c5b959e,  pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1467): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/SystemUI[Framework]( 1054): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1054): Displayed com.test.thalitest/.MainActivity: +649ms (total +749ms)
,I/Timeline( 1054): Timeline: Activity_windows_visible id: ActivityRecord{3c9f4f75 u0 com.test.thalitest/.MainActivity t4} time:314253
I/Timeline( 6117): Timeline: Activity_idle id: android.os.BinderProxy@3f2564f4 time:314257
I/chromium( 6117): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6117): 
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 314392529570; DSPS: 10443110; Offset : -4321836657
,D/JsMessageQueue( 6117): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6117): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6117): 
,D/jxcore_app_log( 6117): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435075840
D/JX-Cordova( 6117): jxcore cordova android initializing
,E/GBMv2   (  346): DFP En is all cleared set to be enabled
,E/GBMv2   (  346): Set value is all cleared set the max
I/GBMv2   (  346): DFP Enabled. Ignore VFP set
W/jxcore-log( 6117): Initializing JXcore engine
W/jxcore-log( 6117): JXcore engine is ready
,W/jxcore-log( 6117): Starting JXcore engine
W/.test.thalitest( 6117): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8368]" dev="sockfs" ino=8368 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6117): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6117): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[9740]" dev="sockfs" ino=9740 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6117): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6117): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29282]" dev="sockfs" ino=29282 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6117): Background sticky concurrent mark sweep GC freed 123920(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.615ms total 120.674ms
,W/jxcore-log( 6117): Platform android
W/jxcore-log( 6117): 
W/jxcore-log( 6117): Process ARCH arm
W/jxcore-log( 6117): 
I/jxcore-log( 6117): JXcore Cordova bridge is ready!
I/jxcore-log( 6117): 
W/jxcore-log( 6117): JXcore engine is started
,E/jxcore  ( 6117): Error!: missing ) after argument list
E/jxcore  ( 6117): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6117): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager( 1054): Killing 5780:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1054): failed to open /acct/uid_10008/pid_5780/cgroup.procs: No such file or directory
,W/PluginManager( 6117): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 39ms. Plugin should use CordovaInterface.getThreadPool().
,E/GBMv2   (  346): DFP En is all cleared set to be enabled
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{a2ba368 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{2ace7381 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
W/ScreenOrientationListener( 6117): Removing an inexistent observer!
I/[LGHome]EVENT( 2081): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2081): [Launcher.java:903:onResume()]onResume
,D/InputDispatcher( 1054): Window went away: Window{15d160e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/[LGHome]EVENT( 2081): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]GBoardWebView( 2081): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1916): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2713): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2081): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2081): [Launcher.java:1056:onResume()]onResume end
I/ActivityManager( 1054): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6189 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2081): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1916): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2081): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2713): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2713): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2081): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2081): , create_time: 1430558575574
I/GBoardWebViewUtils( 2081): , expire_time: 0
I/GBoardWebViewUtils( 2081): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2081): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2081): , display: false
I/GBoardWebViewUtils( 2081): , animation: false }
I/GBoardWebViewUtils( 2081): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2081): , create_time: 1430558575600
I/GBoardWebViewUtils( 2081): , expire_time: 0
I/GBoardWebViewUtils( 2081): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2081): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2081): , display: false
I/GBoardWebViewUtils( 2081): , animation: false }
I/GBoardWebViewUtils( 2081): checkExpiredAndRemoveCard() card: GBoardCard = { id: new_feature_1111111111111_1449584869051
I/GBoardWebViewUtils( 2081): , create_time: 1449584869233
I/GBoardWebViewUtils( 2081): , expire_time: 0
I/GBoardWebViewUtils( 2081): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2081): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2081): , display: false
I/GBoardWebViewUtils( 2081): , animation: false }
I/SystemUI[Framework]( 1054): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/PhoneStatusBar( 1467): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/PhoneWindowManagerEx( 1054): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1054): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1054): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1054): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3c5b959e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1054): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2081): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[LGHome]GBoardWebView( 2081): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/[LGHome]EVENT( 2081): [Launcher.java:5349:onStop()]onStop
,I/art     ( 6189): Almond Protected OAT
,D/WeatherApplication( 6189): removeAccount
,D/WeatherApplication( 6189): Account.length = 0
E/WeatherApplication( 6189): OPERATOR:OPEN
D/WeatherAncestor( 6189): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:32:22
D/Weather.Utils( 6189): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6189): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6189): 2 : This is isUpdating : false
D/Weather.Utils( 6189): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6189): 2 : All the weather widget is gone.
,D/WeatherAncestor( 6189): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:32:22
I/ActivityManager( 1054): Killing 5498:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2081): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2081): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2081): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,W/libprocessgroup( 1054): failed to open /acct/uid_10011/pid_5498/cgroup.procs: No such file or directory
,I/Timeline( 1054): Timeline: Activity_windows_visible id: ActivityRecord{37543068 u0 com.lge.launcher2/.Launcher t3} time:317067
D/[Concierge]Service( 2604): onStartCommand(). Type : 8
D/[Concierge]Service( 2604): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2081): change position of spinner
D/[Concierge]Service( 2604): Update widget ID : 11
I/[Concierge]WidgetView( 2081): initWebView(). Time : 1449588743077
D/[Concierge]Service( 2604): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2081): Return exist ConciergeWebView. Reuse : 224745687
,D/[Concierge]WidgetView( 2081): State Change : null -> AccInBeforeState
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2081): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2081): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2a1a9052
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2081): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2081): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2081): Widget kill message received. Destory myself. My : 1449588454331, New one : 1449588743077
D/[Concierge]WidgetView( 2081): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2081): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2081): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2081): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2081): Timeline: Activity_idle id: android.os.BinderProxy@26c325b4 time:317321
,I/chromium( 2081): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2081): onReloaded()
,I/GBoardWebViewClient( 2081): onPageFinished url:file:///android_asset/www/main.html
,V/BoardContentProvider( 2713): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2713): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1916): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2713): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2713): onEvent() : ACTION_BOARD_ENABLED
I/ActivityManager( 1054): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6228 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActionManagerService( 1916): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2713): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2713): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2713): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2713): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2713): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2081): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2081): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,D/GBoardUriUtils( 2081): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2081): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2081): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2081): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,V/FormManager( 6228): BoardCategory : com.lge.intent.category.gboard.MYWELLNESS, true
,I/ActivityManager( 1054): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6260 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 6228): Network not available. Please check & try again.
V/FormManager( 6228): Network unavailable.
V/FormManager( 6228): Network unavailable.
I/ActivityManager( 1054): Killing 5520:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1054): failed to open /acct/uid_10019/pid_5520/cgroup.procs: No such file or directory
E/ActivityThread( 6260): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6260): No ProfileInfo entries
I/LG Account v2.2( 6260): isEnabled: false
I/Feature ( 6260): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6260): [Lifetracker]Country: EU
I/Feature ( 6260): [Lifetracker]Operator: OPEN
I/Feature ( 6260): [Lifetracker]Ranking support: false
I/Feature ( 6260): [Lifetracker]Comfort support: false
I/Feature ( 6260): [Lifetracker]Accessory: true
I/Feature ( 6260): [Lifetracker]Health device: true
I/Feature ( 6260): [Lifetracker]Extra Pedometer: false
I/Feature ( 6260): [Lifetracker]Blood glucose device: false
I/Feature ( 6260): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 6260): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
,I/GBoardStateUtil( 6260): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6260): gboardCategory : com.lge.intent.category.gboard.MYWELLNESS, gboardState : true
I/ActivityManager( 1054): Killing 5800:com.lge.email/u0a23 (adj 15): empty #17
,I/LIA_Informant_LogCore( 2713): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2713): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
,W/libprocessgroup( 1054): failed to open /acct/uid_10023/pid_5800/cgroup.procs: No such file or directory
I/LIA_MrGDBLogger_LogCore( 2713): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2713): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
I/LIA_S4URecommender_LogCore( 2713): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2713): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
,D/CoreEventReceiver( 6260): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
,V/FormManager( 6228): BoardCategory : com.lge.intent.category.gboard.DOYOUKNOW, true
V/FormManager( 6228): Network unavailable.
,W/FormManager( 6228): Network not available. Please check & try again.
I/GBoardStateUtil( 6260): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6260): gboardCategory : com.lge.intent.category.gboard.DOYOUKNOW, gboardState : true
I/LIA_Informant_LogCore( 2713): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2713): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_Informant_BoardStateUtil( 2713): defaultHomePackage : com.lge.launcher2
D/LIA_Informant_TaskActivator( 2713): DefaultHomeCondition is satisfied
V/FormManager( 6228): Network unavailable.
I/LIA_Informant_BoardStateUtil( 2713): isEnabledConciergeBoard() : count > 0 - true
,D/LIA_Informant_TaskActivator( 2713): BoardCondition is satisfied
W/LIA_Informant_TaskActivator( 2713): setActivation() : Informant Task - ACTIVATION
D/LIA_Informant_LGIntelligentAgent( 2713): activateLIAService : Informant / true
I/LIA_Informant_LIATaskLoader( 2713): getTaskSdkClassName : com.lge.ia.LIAInformant
D/LIA_Informant_LIATaskLoader( 2713): classLoad - TargetClass : com.lge.ia.LIAInformant
I/LIA_Informant_LIATaskLoader( 2713): createLIAService - Success
I/LIA_Informant_LGIntelligentAgent( 2713): activateLIAService : startService success. (You may need to check whether its property has changed or not!)
D/LIA_Informant_LIARemoteService( 2713): onStartCommand() : LIARemoteService started! - (Id :5), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
I/LIA_Informant_InformantService( 2713): isNowInActivationCondition()
I/LIA_Informant_BoardStateUtil( 2713): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 2713): ActivationConditionHandler : LGHome condition is true
I/LIA_Informant_BoardStateUtil( 2713): isEnabledConciergeBoard() : count > 0 - true
,I/LIA_Informant_ActivationConditionHandler( 2713): ActivationConditionHandler : ConciergeBoard condition is true
,I/LIA_Informant_ActivationConditionHandler( 2713): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
I/LIA_Informant_InformantService( 2713): getTaskPropertiesAtFirstStarting()
D/LIA_Informant_LIARemoteService( 2713): --> LIA task activation intent from com.lge.ia.task.informant for Informant(activation: true)
D/LIA_Informant_LIARemoteService( 2713): updateTaskProperty() : 
I/LIA_Informant_LIARemoteService( 2713): --> LIA task activation intent from com.lge.ia.task.informant, but it's same as the current setting or couldn't chagne it so just passed !! (Informant activation : true)
I/LIA_MrGDBLogger_LogCore( 2713): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2713): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_S4URecommender_LogCore( 2713): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2713): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/GBoardtInterface( 2081): exportHTML()
,E/GBMv2   (  346): DFP En is all cleared set to be enabled
E/GBMv2   (  346): Set value is all cleared set the max
I/GBMv2   (  346): DFP Enabled. Ignore VFP set
I/GBoardtInterface( 2081): exportHTML()
,I/GBoardtInterface( 2081): exportHTML()
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2081): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2081): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 2081): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2081): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
,I/GBoardtInterface( 2081): onAnimationFinished
,I/GBoardtInterface( 2081): onAnimationFinished
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 334394185084; DSPS: 11098525; Offset : -4321859662
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=76024289, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,D/[Concierge]Service( 2604): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=76024289 [*alarm*], flags=0x0
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1054): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1412): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1412): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4898): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4898): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4898): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1467): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do add job
D/LgeQuickCoverNotificationData( 1412): add : 2
D/LgeQuickCoverNotificationData( 1412): do add job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{1e7626b5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 4898): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 354395736794; DSPS: 11753935; Offset : -4321833935
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 374397925434; DSPS: 12409367; Offset : -4321842354
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 394399104436; DSPS: 13064766; Offset : -4321853666
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 414401367658; DSPS: 13720200; Offset : -4321848927
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/WifiController( 1054): battery changed pluggedType: 2,
,D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3974): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3974): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 434402740619; DSPS: 14375605; Offset : -4321849284
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 454404238997; DSPS: 15031014; Offset : -4321845928
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 474405773625; DSPS: 15686424; Offset : -4321837361
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 494407181273; DSPS: 16341830; Offset : -4321833496
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 514408661265; DSPS: 16997239; Offset : -4321848735
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 534411567977; DSPS: 17652694; Offset : -4321841506
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 554413251719; DSPS: 18308109; Offset : -4321835970
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 574414774523; DSPS: 18963519; Offset : -4321839019
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 594416580453; DSPS: 19618938; Offset : -4321833834
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 614418257269; DSPS: 20274354; Offset : -4321865846
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 634419724344; DSPS: 20929762; Offset : -4321863537
,I/ActivityManager( 1054): Killing 5543:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1054): failed to open /acct/uid_10027/pid_5543/cgroup.procs: No such file or directory
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4898): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4898): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4898): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4898): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{1e7626b5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 654421917254; DSPS: 21585193; Offset : -4321837531
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1054): battery changed pluggedType: 2
D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3974): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3974): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 674423825267; DSPS: 22240616; Offset : -4321852022
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 694425406301; DSPS: 22896028; Offset : -4321857980
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 714426980251; DSPS: 23551439; Offset : -4321840531
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 734428390764; DSPS: 24206845; Offset : -4321833879
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 754429882007; DSPS: 24862254; Offset : -4321837762
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=76024289, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{70e99a5 type 2 when 564347 com.google.android.gms} when 564347
,D/Finsky  ( 4898): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{5b05d2b type 0 when 1449589140474 com.android.vending} when 1449589140474
,D/[Concierge]Service( 2604): onStartCommand(). Type : 9
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 4898): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=76024289 [*alarm*], flags=0x0
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1054): Explicit concurrent mark sweep GC freed 21530(1046KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 43MB/65MB, paused 1.988ms total 94.717ms
,W/Finsky  ( 4898): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 4898): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 4898): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4898): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4898): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
D/DeviceConnectionService( 1830): client connected with version: 7571000
I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 774440571479; DSPS: 25517964; Offset : -4321829625
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=76024289, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{2bd862f5 type 0 when 1449589210761 com.android.vending} when 1449589210761
,D/[Concierge]Service( 2604): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=76024289 [*alarm*], flags=0x0
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4898): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4898): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4898): [1] 5.onFinished: Scheduling replication attempt 1.
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 794442752825; DSPS: 26173396; Offset : -4321845518
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{11aa645c type 0 when 1449589232852 com.android.vending} when 1449589232852
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4898): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4898): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4898): [1] 5.onFinished: Scheduling replication attempt 2.
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 814444463703; DSPS: 26828812; Offset : -4321843442
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 834446103746; DSPS: 27484226; Offset : -4321851506
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=76024289, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{3166edbf type 0 when 1449589260008 com.android.vending} when 1449589260008
,D/[Concierge]Service( 2604): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=76024289 [*alarm*], flags=0x0
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4898): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4898): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4898): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 854447926553; DSPS: 28139645; Offset : -4321829053
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{1ab4e48e type 0 when 1449589291926 com.android.vending} when 1449589291926
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4898): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4898): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4898): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 874449483836; DSPS: 28795057; Offset : -4321858814
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{179249f9 type 0 when 1449589316785 com.android.vending} when 1449589316785
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2132): Explicit concurrent mark sweep GC freed 33211(1947KB) AllocSpace objects, 5(720KB) LOS objects, 51% free, 30MB/62MB, paused 1.144ms total 30.031ms
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4898): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4898): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4898): [1] 5.onFinished: Scheduling replication attempt 5.
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 894451777527; DSPS: 29450492; Offset : -4321854045
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 914453276165; DSPS: 30105901; Offset : -4321850562
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=76024289, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{272681f0 type 0 when 1449589338547 com.android.vending} when 1449589338547
,D/[Concierge]Service( 2604): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=76024289 [*alarm*], flags=0x0
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4898): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4898): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4898): [1] 5.onFinished: Giving up after 6 failures.
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 934455184438; DSPS: 30761323; Offset : -4321834351
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED,
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4898): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4898): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4898): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4898): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{1e7626b5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 954456733441; DSPS: 31416734; Offset : -4321842032
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 974458213486; DSPS: 32072143; Offset : -4321857218
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 994459911655; DSPS: 32727558; Offset : -4321837542
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1014462421909; DSPS: 33383000; Offset : -4321829833
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1034463831953; DSPS: 34038407; Offset : -4321853777
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1054465298299; DSPS: 34693815; Offset : -4321852456
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1074467204333; DSPS: 35349237; Offset : -4321838539
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1094468822502; DSPS: 36004650; Offset : -4321837880
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1114471140516; DSPS: 36660086; Offset : -4321839072
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1134472934988; DSPS: 37315505; Offset : -4321845214
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1154474356698; DSPS: 37970912; Offset : -4321857934
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1174475816431; DSPS: 38626319; Offset : -4321832319
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1194477652464; DSPS: 39281739; Offset : -4321827498
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/WifiController( 1054): battery changed pluggedType: 2
D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3974): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3974): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1214479451571; DSPS: 39937158; Offset : -4321828927
,I/UsageStatsService( 1054): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1234481086095; DSPS: 40592572; Offset : -4321842170
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4898): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4898): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4898): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4898): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{1e7626b5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1254486011243; DSPS: 41248093; Offset : -4321828061
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1274487647746; DSPS: 41903507; Offset : -4321841746
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1294489135239; DSPS: 42558916; Offset : -4321849667
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1314492406377; DSPS: 43214383; Offset : -4321843963
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1334493851839; DSPS: 43869790; Offset : -4321832931
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1354495424226; DSPS: 44525202; Offset : -4321847301
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1374496974583; DSPS: 45180613; Offset : -4321853600
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1394498625981; DSPS: 45836027; Offset : -4321849892
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1414500962850; DSPS: 46491463; Offset : -4321832541
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1434502830862; DSPS: 47146885; Offset : -4321856619
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1454504240751; DSPS: 47802291; Offset : -4321850538
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=76024289, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{6cc4168 type 2 when 1323388 com.google.android.gms} when 1323388
,D/[Concierge]Service( 2604): onStartCommand(). Type : 9
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=76024289 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1474509344545; DSPS: 48457818; Offset : -4321842946
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1494511857193; DSPS: 49113260; Offset : -4321832999
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1514513304685; DSPS: 49768668; Offset : -4321850247
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1534514763376; DSPS: 50424076; Offset : -4321856373
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4898): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4898): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4898): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 4898): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{1e7626b5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1554516434879; DSPS: 51079490; Offset : -4321832768
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1574517896955; DSPS: 51734898; Offset : -4321835587
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1594519375176; DSPS: 52390307; Offset : -4321852598
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1614521571003; DSPS: 53045739; Offset : -4321854322
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1634523271724; DSPS: 53701155; Offset : -4321862534
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1654524741195; DSPS: 54356563; Offset : -4321857776
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1674526290301; DSPS: 55011973; Offset : -4321834628
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1694527718315; DSPS: 55667380; Offset : -4321841019
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1714529178931; DSPS: 56322788; Offset : -4321845011
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1734531659550; DSPS: 56978229; Offset : -4321836603
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1754533439021; DSPS: 57633648; Offset : -4321857460
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1774534937452; DSPS: 58289057; Offset : -4321854365
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1794536505881; DSPS: 58944468; Offset : -4321842541
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1814538000665; DSPS: 59599877; Offset : -4321843065
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1834539760970; DSPS: 60255295; Offset : -4321852624
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1054): Prepared write state in 8ms
,I/art     ( 1054): Explicit concurrent mark sweep GC freed 29927(1312KB) AllocSpace objects, 9(592KB) LOS objects, 33% free, 44MB/66MB, paused 2.093ms total 117.910ms
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4898): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4898): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4898): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
W/System  ( 4898): Ignoring header User-Agent because its value was null.
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{1e7626b5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1854541322994; DSPS: 60910706; Offset : -4321846163
,I/ProcessStatsService( 1054): Pruning old procstats: /data/system/procstats/state-2015-12-07-15-37-07.bin
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1874542822153; DSPS: 61566115; Offset : -4321843121
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1894544310635; DSPS: 62221524; Offset : -4321850130
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1914546124690; DSPS: 62876943; Offset : -4321836821
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1934547632391; DSPS: 63532353; Offset : -4321854972
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1954549081393; DSPS: 64187760; Offset : -4321840089
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1974551269146; DSPS: 64843192; Offset : -4321849810
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1994552681587; DSPS: 65498598; Offset : -4321841151
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 2014554149704; DSPS: 66154006; Offset : -4321837618
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 2034555694904; DSPS: 66809417; Offset : -4321849075
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 2054557271303; DSPS: 67464828; Offset : -4321829019
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 2074558745462; DSPS: 68120237; Offset : -4321850145
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 2094560963945; DSPS: 68775669; Offset : -4321829030
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 2114562421489; DSPS: 69431077; Offset : -4321836383
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 2134564112366; DSPS: 70086493; Offset : -4321854203
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 2154565641630; DSPS: 70741903; Offset : -4321851027
,I/ActivityManager( 1054): Killing 5924:com.lge.eula/1000 (adj 15): empty for 2017s
,I/ActivityManager( 1054): Killing 5590:com.google.android.apps.plus/u0a97 (adj 15): empty for 2017s
,I/ActivityManager( 1054): Killing 5566:com.lge.lockscreensettings/u0a80 (adj 15): empty for 2017s
,I/ActivityManager( 1054): Killing 5862:com.google.android.apps.docs/u0a61 (adj 15): empty for 2017s
,I/ActivityManager( 1054): Killing 5833:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty for 2017s
,I/ActivityManager( 1054): Killing 5726:com.android.defcontainer/u0a4 (adj 15): empty for 2018s
,I/ActivityManager( 1054): Killing 5168:com.wsandroid.suite.lge/1000 (adj 15): empty for 2018s
,W/libprocessgroup( 1054): failed to open /acct/uid_1000/pid_5924/cgroup.procs: No such file or directory
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup( 1054): failed to open /acct/uid_10097/pid_5590/cgroup.procs: No such file or directory
W/libprocessgroup( 1054): failed to open /acct/uid_10080/pid_5566/cgroup.procs: No such file or directory
W/libprocessgroup( 1054): failed to open /acct/uid_10061/pid_5862/cgroup.procs: No such file or directory
W/libprocessgroup( 1054): failed to open /acct/uid_1000/pid_5833/cgroup.procs: No such file or directory
,W/libprocessgroup( 1054): failed to open /acct/uid_10004/pid_5726/cgroup.procs: No such file or directory
W/libprocessgroup( 1054): failed to open /acct/uid_1000/pid_5168/cgroup.procs: No such file or directory
I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
E/PlayEventLogger( 4898): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4898): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4898): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4898): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4898): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{1e7626b5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,TIME-OUT KILL (timeout was 1800000ms)
```
