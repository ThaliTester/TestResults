#### Test 5065027865f659b_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 269202467360; DSPS: 8962043; Offset : -4312722602
,D/AndroidRuntime( 6193): 
D/AndroidRuntime( 6193): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6193): CheckJNI is OFF
D/AndroidRuntime( 6193): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1035): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1951): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1035): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{2bc0ca86 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{2bc0ca86 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1035): AppWindowTokenEx init.. 
E/GBMv2   (  341): DFP En is all cleared set to be enabled
I/ActivityManager( 1035): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6214 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6193): Shutting down VM
V/ActivityManager( 1035): Display changed displayId=0
D/DSDPConnection( 1856): Display #0 changed.
D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{3f1056b2 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{140b5603 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6214): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6214): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6214): Loading: webviewchromium
,I/LibraryLoader( 6214): Time to load native libraries: 3 ms (timestamps 9409-9412)
I/LibraryLoader( 6214): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6214): Binding Chromium to main looper Looper (main, tid 1) {1ac9e6cf}
I/LibraryLoader( 6214): Expected native library version number "",actual native library version number ""
I/chromium( 6214): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6214): Initializing chromium process, renderers=0
W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6214): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  319): registerClient() client 0xb54ecda0, uid 10311
,D/BluetoothManagerService( 1035): Message: 20
D/BluetoothManagerService( 1035): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@129fa2e0:true
D/BluetoothAdapter( 6214): 1063553116: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6214): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6214): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6214): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6214): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6214): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6214): Build Date: 12/12/14 금
I/Adreno-EGL( 6214): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6214): Remote Branch: 
I/Adreno-EGL( 6214): Local Patches: 
I/Adreno-EGL( 6214): Reconstruct Branch: 
,W/chromium( 6214): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6214): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6214): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6214): CordovaWebView is running on device made by: LGE
,W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6214): Render dirty regions requested: true
I/OpenGLRenderer( 6214): Initialized EGL, version 1.4
D/OpenGLRenderer( 6214): Enabling debug mode 0
,W/ActivityManager( 1035): Activity pause timeout for ActivityRecord{86f3f47 u0 com.test.thalitest/.MainActivity t4}
,D/Atlas   ( 6214): Validating map...
D/SplitWindow( 1035): check instance of lgWin Window{248a001a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6214): LgDataFeature() Constructor: none
,D/LgDataFeature( 6214): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1458): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@24943785,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1035): Displayed com.test.thalitest/.MainActivity: +631ms (total +699ms)
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{86f3f47 u0 com.test.thalitest/.MainActivity t4} time:279903
I/Timeline( 6214): Timeline: Activity_idle id: android.os.BinderProxy@3888c08c time:279907
I/chromium( 6214): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6214): 
D/JsMessageQueue( 6214): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6214): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6214): 
D/jxcore_app_log( 6214): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434849152
D/JX-Cordova( 6214): jxcore cordova android initializing
E/GBMv2   (  341): DFP En is all cleared set to be enabled
E/GBMv2   (  341): Set value is all cleared set the max
I/GBMv2   (  341): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6214): Initializing JXcore engine
W/jxcore-log( 6214): JXcore engine is ready
,W/jxcore-log( 6214): Starting JXcore engine
,W/.test.thalitest( 6214): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[10248]" dev="sockfs" ino=10248 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6214): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6214): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8697]" dev="sockfs" ino=8697 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6214): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6214): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[30871]" dev="sockfs" ino=30871 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6214): Platform android
W/jxcore-log( 6214): 
W/jxcore-log( 6214): Process ARCH arm
W/jxcore-log( 6214): 
,I/jxcore-log( 6214): JXcore Cordova bridge is ready!
I/jxcore-log( 6214): 
,W/jxcore-log( 6214): JXcore engine is started
,E/jxcore  ( 6214): Error!: missing ) after argument list
E/jxcore  ( 6214): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6214): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 6214): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1035): Killing 5429:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_5429/cgroup.procs: No such file or directory
,W/PluginManager( 6214): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
E/GBMv2   (  341): DFP En is all cleared set to be enabled
,D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{65ab980 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{12262bb9 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
W/ScreenOrientationListener( 6214): Removing an inexistent observer!
I/[LGHome]EVENT( 2067): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2067): [Launcher.java:903:onResume()]onResume
,D/InputDispatcher( 1035): Window went away: Window{248a001a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/[LGHome]EVENT( 2067): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1916): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2067): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2779): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2067): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2067): [Launcher.java:1056:onResume()]onResume end
,I/ActivityManager( 1035): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6292 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2067): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1916): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2067): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2779): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2779): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2067): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2067): , create_time: 1430558575574
I/GBoardWebViewUtils( 2067): , expire_time: 0
I/GBoardWebViewUtils( 2067): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2067): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2067): , display: false
I/GBoardWebViewUtils( 2067): , animation: false }
I/GBoardWebViewUtils( 2067): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2067): , create_time: 1430558575600
I/GBoardWebViewUtils( 2067): , expire_time: 0
I/GBoardWebViewUtils( 2067): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2067): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2067): , display: false
I/GBoardWebViewUtils( 2067): , animation: false }
I/GBoardWebViewUtils( 2067): checkExpiredAndRemoveCard() card: GBoardCard = { id: new_feature_1111111111111_1449584869051
I/GBoardWebViewUtils( 2067): , create_time: 1449584869233
I/GBoardWebViewUtils( 2067): , expire_time: 0
I/GBoardWebViewUtils( 2067): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2067): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2067): , display: false
I/GBoardWebViewUtils( 2067): , animation: false }
,D/WallpaperManager( 2067): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@24943785,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1458): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/[LGHome]GBoardWebView( 2067): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/art     ( 6292): Almond Protected OAT
,D/WeatherApplication( 6292): removeAccount
,D/WeatherApplication( 6292): Account.length = 0
E/WeatherApplication( 6292): OPERATOR:OPEN
D/WeatherAncestor( 6292): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:15:56
D/Weather.Utils( 6292): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6292): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6292): 2 : This is isUpdating : false
I/[LGHome]EVENT( 2067): [Launcher.java:5349:onStop()]onStop
,D/Weather.Utils( 6292): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6292): 2 : All the weather widget is gone.
D/WeatherAncestor( 6292): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:15:56
I/ActivityManager( 1035): Killing 5453:com.android.contacts/u0a19 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,W/libprocessgroup( 1035): failed to open /acct/uid_10019/pid_5453/cgroup.procs: No such file or directory
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{11fe680 u0 com.lge.launcher2/.Launcher t3} time:282716
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2067): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2067): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2067): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2638): onStartCommand(). Type : 8
D/[Concierge]Service( 2638): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/[Concierge]Service( 2638): Update widget ID : 11
D/[Concierge]WidgetView( 2067): change position of spinner
I/[Concierge]WidgetView( 2067): initWebView(). Time : 1449598556903
D/[Concierge]Service( 2638): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2067): Return exist ConciergeWebView. Reuse : 1073295245
,D/[Concierge]WidgetView( 2067): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2067): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2067): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3d31549
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2067): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2067): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2067): Widget kill message received. Destory myself. My : 1449598302655, New one : 1449598556903
D/[Concierge]WidgetView( 2067): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2067): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2067): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2067): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2067): Timeline: Activity_idle id: android.os.BinderProxy@30b7d94c time:282919
,I/chromium( 2067): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2067): onReloaded()
,I/GBoardWebViewClient( 2067): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2779): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2779): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1916): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2779): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2779): onEvent() : ACTION_BOARD_ENABLED
I/ActivityManager( 1035): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6328 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActionManagerService( 1916): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2779): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2779): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2779): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2779): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2779): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2067): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2067): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,D/GBoardUriUtils( 2067): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2067): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2067): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2067): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,V/FormManager( 6328): BoardCategory : com.lge.intent.category.gboard.MYWELLNESS, true
,I/ActivityManager( 1035): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6351 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
W/FormManager( 6328): Network not available. Please check & try again.
,V/FormManager( 6328): Network unavailable.
V/FormManager( 6328): Network unavailable.
I/ActivityManager( 1035): Killing 5856:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10023/pid_5856/cgroup.procs: No such file or directory
,E/ActivityThread( 6351): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6351): No ProfileInfo entries
I/LG Account v2.2( 6351): isEnabled: false
I/Feature ( 6351): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6351): [Lifetracker]Country: EU
I/Feature ( 6351): [Lifetracker]Operator: OPEN
I/Feature ( 6351): [Lifetracker]Ranking support: false
I/Feature ( 6351): [Lifetracker]Comfort support: false
I/Feature ( 6351): [Lifetracker]Accessory: true
I/Feature ( 6351): [Lifetracker]Health device: true
I/Feature ( 6351): [Lifetracker]Extra Pedometer: false
I/Feature ( 6351): [Lifetracker]Blood glucose device: false
I/Feature ( 6351): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 6351): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
,I/GBoardStateUtil( 6351): [GBoardStateUtil] isEnableLGHealthofGBoard : true
,I/CoreEventReceiver( 6351): gboardCategory : com.lge.intent.category.gboard.MYWELLNESS, gboardState : true
I/ActivityManager( 1035): Killing 5478:com.android.gallery3d/u0a27 (adj 15): empty #17
I/LIA_Informant_LogCore( 2779): LIA Log setTagPrefix - prefix : LIA_Informant_
,I/LIA_Informant_BoardCondition( 2779): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
W/libprocessgroup( 1035): failed to open /acct/uid_10027/pid_5478/cgroup.procs: No such file or directory
I/LIA_MrGDBLogger_LogCore( 2779): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2779): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
I/LIA_S4URecommender_LogCore( 2779): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2779): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
D/CoreEventReceiver( 6351): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
,V/FormManager( 6328): BoardCategory : com.lge.intent.category.gboard.DOYOUKNOW, true
I/GBoardStateUtil( 6351): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6351): gboardCategory : com.lge.intent.category.gboard.DOYOUKNOW, gboardState : true
I/LIA_Informant_LogCore( 2779): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2779): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
,I/LIA_Informant_BoardStateUtil( 2779): defaultHomePackage : com.lge.launcher2
D/LIA_Informant_TaskActivator( 2779): DefaultHomeCondition is satisfied
W/FormManager( 6328): Network not available. Please check & try again.
,V/FormManager( 6328): Network unavailable.
V/FormManager( 6328): Network unavailable.
I/LIA_Informant_BoardStateUtil( 2779): isEnabledConciergeBoard() : count > 0 - true
D/LIA_Informant_TaskActivator( 2779): BoardCondition is satisfied
W/LIA_Informant_TaskActivator( 2779): setActivation() : Informant Task - ACTIVATION
D/LIA_Informant_LGIntelligentAgent( 2779): activateLIAService : Informant / true
I/LIA_Informant_LIATaskLoader( 2779): getTaskSdkClassName : com.lge.ia.LIAInformant
D/LIA_Informant_LIATaskLoader( 2779): classLoad - TargetClass : com.lge.ia.LIAInformant
,I/LIA_Informant_LIATaskLoader( 2779): createLIAService - Success
I/LIA_Informant_LGIntelligentAgent( 2779): activateLIAService : startService success. (You may need to check whether its property has changed or not!)
D/LIA_Informant_LIARemoteService( 2779): onStartCommand() : LIARemoteService started! - (Id :5), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
I/LIA_Informant_InformantService( 2779): isNowInActivationCondition()
I/LIA_Informant_BoardStateUtil( 2779): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 2779): ActivationConditionHandler : LGHome condition is true
,I/LIA_Informant_BoardStateUtil( 2779): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 2779): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 2779): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
I/LIA_Informant_InformantService( 2779): getTaskPropertiesAtFirstStarting()
D/LIA_Informant_LIARemoteService( 2779): --> LIA task activation intent from com.lge.ia.task.informant for Informant(activation: true)
D/LIA_Informant_LIARemoteService( 2779): updateTaskProperty() : 
I/LIA_Informant_LIARemoteService( 2779): --> LIA task activation intent from com.lge.ia.task.informant, but it's same as the current setting or couldn't chagne it so just passed !! (Informant activation : true)
I/LIA_MrGDBLogger_LogCore( 2779): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2779): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_S4URecommender_LogCore( 2779): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2779): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/GBoardtInterface( 2067): exportHTML()
,I/GBoardtInterface( 2067): exportHTML()
,I/GBoardtInterface( 2067): exportHTML()
,E/GBMv2   (  341): DFP En is all cleared set to be enabled
E/GBMv2   (  341): Set value is all cleared set the max
I/GBMv2   (  341): DFP Enabled. Ignore VFP set
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2067): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2067): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 2067): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2067): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
,I/GBoardtInterface( 2067): onAnimationFinished
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/GBoardtInterface( 2067): onAnimationFinished
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 289211413644; DSPS: 9617696; Offset : -4312717656
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 309213510199; DSPS: 10273124; Offset : -4312696505
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=341320986, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{1686b335 type 2 when 239296 android} when 239296
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{31f2a3ca type 2 when 260182 com.google.android.gms} when 260182
D/[Concierge]Service( 2638): onStartCommand(). Type : 9
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=341320986 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 329215419723; DSPS: 10928547; Offset : -4312709406
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=341320986, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,D/[Concierge]Service( 2638): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=341320986 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 349217053204; DSPS: 11583960; Offset : -4312693564
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1035): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1458): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 5569): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5569): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5569): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1400): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1400): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1400): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1400): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1400): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1400): handleNotificationPosted(true)
D/QuickCircle( 1400): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1400): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post do add job
D/LgeQuickCoverNotificationData( 1400): add : 2
D/LgeQuickCoverNotificationData( 1400): do add job
D/LgeQuickCoverNotificationData( 1400): showAll3
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1400): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1400): updateNotificationData: count=3
D/QuickStatusbarLayout( 1400): Notification difference=198
D/QuickStatusbarLayout( 1400): child = android.widget.LinearLayout{2e4d716d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 5569): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 369218922832; DSPS: 12239382; Offset : -4312715948
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 389220713867; DSPS: 12894800; Offset : -4312694985
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 409222619692; DSPS: 13550223; Offset : -4312711793
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/WifiController( 1035): battery changed pluggedType: 2
,D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3225): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3225): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 429224234737; DSPS: 14205636; Offset : -4312714102
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 449225736083; DSPS: 14861045; Offset : -4312708326
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 469227292273; DSPS: 15516456; Offset : -4312708481
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 489228767266; DSPS: 16171864; Offset : -4312698252
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 509230925956; DSPS: 16827295; Offset : -4312706336
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
,I/[SystemUI]Clock( 1458): called onTimeUpdated()
I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 529232501469; DSPS: 17482707; Offset : -4312717711
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 549234075056; DSPS: 18138118; Offset : -4312700651
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 569235534683; DSPS: 18793526; Offset : -4312705713
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 589237300665; DSPS: 19448944; Offset : -4312709723
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 609238772636; DSPS: 20104352; Offset : -4312702831
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 629241006483; DSPS: 20759785; Offset : -4312696662
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 649242600695; DSPS: 21415198; Offset : -4312719856
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5569): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5569): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5569): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 5569): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/art     ( 1035): Explicit concurrent mark sweep GC freed 22632(1083KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 43MB/65MB, paused 2.762ms total 122.222ms
,D/LgeQuickCoverNLService( 1400): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1400): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1400): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1400): handleNotificationPosted(true)
D/QuickCircle( 1400): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1400): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post do just update job
D/LgeQuickCoverNotificationData( 1400): showAll3
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1400): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1400): updateNotificationData: count=3
D/QuickStatusbarLayout( 1400): Notification difference=198
D/QuickStatusbarLayout( 1400): child = android.widget.LinearLayout{2e4d716d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 669244209228; DSPS: 22070610; Offset : -4312698159
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 689245695158; DSPS: 22726019; Offset : -4312707538
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 709250940047; DSPS: 23381551; Offset : -4312711778
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 729252542330; DSPS: 24036963; Offset : -4312696199
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 749254028104; DSPS: 24692372; Offset : -4312706022
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 769259414711; DSPS: 25347909; Offset : -4312720869
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/WifiController( 1035): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3225): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3225): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 789260698922; DSPS: 26003311; Offset : -4312718501
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 809262354332; DSPS: 26658725; Offset : -4312711093
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 829264047136; DSPS: 27314140; Offset : -4312696807
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 849266023274; DSPS: 27969565; Offset : -4312704103
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 869267724673; DSPS: 28624981; Offset : -4312711871
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 889275472686; DSPS: 29280595; Offset : -4312715192
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 909276912990; DSPS: 29936002; Offset : -4312709345
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 929278378452; DSPS: 30591410; Offset : -4312708622
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 949279935944; DSPS: 31246821; Offset : -4312707684
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1400): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1400): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1400): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1400): handleNotificationPosted(true)
D/QuickCircle( 1400): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1400): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post do just update job
D/LgeQuickCoverNotificationData( 1400): showAll3
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1400): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1400): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5569): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5569): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5569): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5569): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1400): Notification difference=198
D/QuickStatusbarLayout( 1400): child = android.widget.LinearLayout{2e4d716d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 969286192290; DSPS: 31902386; Offset : -4312707389
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 989287948585; DSPS: 32557804; Offset : -4312721061
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=341320986, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{3d0706a6 type 2 when 546547 com.google.android.gms} when 546547
,D/Finsky  ( 5569): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{16c9ac94 type 0 when 1449598907067 com.android.vending} when 1449598907067
D/[Concierge]Service( 2638): onStartCommand(). Type : 9
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=341320986 [*alarm*], flags=0x0
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 5569): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 5569): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 5569): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 5569): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5569): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5569): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
D/DeviceConnectionService( 1821): client connected with version: 7571000
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{303146b6 type 0 when 1449599278723 com.android.vending} when 1449599278723
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 32179(1878KB) AllocSpace objects, 7(1008KB) LOS objects, 51% free, 30MB/62MB, paused 1.162ms total 33.791ms
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5569): [1] 5.onFinished: Scheduling replication attempt 1.
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1009289141754; DSPS: 33213203; Offset : -4312715682
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=341320986, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{e6bbdc1 type 0 when 1449599299424 com.android.vending} when 1449599299424
,D/[Concierge]Service( 2638): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=341320986 [*alarm*], flags=0x0
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1029290681748; DSPS: 33868613; Offset : -4312702322
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5569): [1] 5.onFinished: Scheduling replication attempt 2.
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1049292479708; DSPS: 34524032; Offset : -4312706462
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{93311d8 type 0 when 1449599323543 com.android.vending} when 1449599323543
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5569): [1] 5.onFinished: Scheduling replication attempt 3.
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1069293544023; DSPS: 35179427; Offset : -4312709090
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1089295019537; DSPS: 35834835; Offset : -4312699669
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=341320986, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{22f386ab type 0 when 1449599358400 com.android.vending} when 1449599358400
,D/[Concierge]Service( 2638): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=341320986 [*alarm*], flags=0x0
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5569): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1109296562289; DSPS: 36490246; Offset : -4312713340
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{6885caa type 0 when 1449599387756 com.android.vending} when 1449599387756
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5569): [1] 5.onFinished: Scheduling replication attempt 5.
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1129297902906; DSPS: 37145650; Offset : -4312713648
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=341320986, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{19a83c05 type 0 when 1449599417326 com.android.vending} when 1449599417326
,D/[Concierge]Service( 2638): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=341320986 [*alarm*], flags=0x0
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5569): [1] 5.onFinished: Giving up after 6 failures.
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1149299547274; DSPS: 37801063; Offset : -4312688534
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1169301682267; DSPS: 38456494; Offset : -4312720264
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1189302797989; DSPS: 39111890; Offset : -4312700752
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1209304427199; DSPS: 39767303; Offset : -4312691448
,I/UsageStatsService( 1035): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1229305997139; DSPS: 40422715; Offset : -4312708501
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1249307065153; DSPS: 41078110; Offset : -4312706283
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 25321(1055KB) AllocSpace objects, 5(208KB) LOS objects, 33% free, 44MB/66MB, paused 2.225ms total 135.198ms
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1400): onNotificationPosted
D/SmartCoverUpdateMonitor( 1400): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1400): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1400): handleNotificationPosted(true)
D/QuickCircle( 1400): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1400): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post do just update job
D/LgeQuickCoverNotificationData( 1400): showAll3
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1400): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1400): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 5569): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5569): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5569): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5569): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1400): Notification difference=198
D/QuickStatusbarLayout( 1400): child = android.widget.LinearLayout{2e4d716d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1269308670457; DSPS: 41733523; Offset : -4312720599
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1289310846648; DSPS: 42388954; Offset : -4312711131
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1309312971745; DSPS: 43044383; Offset : -4312691745
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1329314469237; DSPS: 43699793; Offset : -4312720210
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1349315965844; DSPS: 44355202; Offset : -4312718836
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1369317058336; DSPS: 45010598; Offset : -4312722683
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1389318736349; DSPS: 45666013; Offset : -4312725586
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1409320818530; DSPS: 46321441; Offset : -4312718392
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1429322408366; DSPS: 46976853; Offset : -4312715392
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1449323830337; DSPS: 47632259; Offset : -4312697437
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1469325357673; DSPS: 48287669; Offset : -4312696007
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1489326924071; DSPS: 48943081; Offset : -4312716574
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1509328353281; DSPS: 49598488; Offset : -4312721638
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1529329806608; DSPS: 50253895; Offset : -4312702691
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1549332243736; DSPS: 50909335; Offset : -4312706734
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1400): onNotificationPosted
D/SmartCoverUpdateMonitor( 1400): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1400): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1400): handleNotificationPosted(true)
D/QuickCircle( 1400): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1400): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post do just update job
D/LgeQuickCoverNotificationData( 1400): showAll3
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1400): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1400): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 5569): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5569): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5569): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5569): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1400): Notification difference=198
D/QuickStatusbarLayout( 1400): child = android.widget.LinearLayout{2e4d716d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1569333951281; DSPS: 51564751; Offset : -4312708173
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/WifiController( 1035): battery changed pluggedType: 2
,D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
D/LEDHandler( 1951): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3225): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3225): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1589335454502; DSPS: 52220160; Offset : -4312700548
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=341320986, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{3a02879d type 2 when 1435331 com.google.android.gms} when 1435331
,D/[Concierge]Service( 2638): onStartCommand(). Type : 9
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=341320986 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1609337085327; DSPS: 52875574; Offset : -4312717621
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1629338538810; DSPS: 53530981; Offset : -4312698437
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1649340635834; DSPS: 54186410; Offset : -4312707309
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1669341631138; DSPS: 54841803; Offset : -4312718903
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1689343480871; DSPS: 55497223; Offset : -4312700172
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1709345021644; DSPS: 56152634; Offset : -4312715821
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1729346571793; DSPS: 56808044; Offset : -4312691604
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1749347990535; DSPS: 57463451; Offset : -4312707214
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1769349441516; DSPS: 58118859; Offset : -4312721025
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1789351342708; DSPS: 58774281; Offset : -4312711740
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1809352939262; DSPS: 59429693; Offset : -4312702361
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1829354576650; DSPS: 60085107; Offset : -4312712896
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1849356130341; DSPS: 60740518; Offset : -4312715627
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1035): Prepared write state in 9ms
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1400): onNotificationPosted
D/SmartCoverUpdateMonitor( 1400): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1400): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1400): handleNotificationPosted(true)
D/QuickCircle( 1400): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1400): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): post do just update job
D/LgeQuickCoverNotificationData( 1400): showAll3
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1400): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1400): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1400): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1400): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1400): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 5569): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5569): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5569): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5569): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5569): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1400): Notification difference=198
D/QuickStatusbarLayout( 1400): child = android.widget.LinearLayout{2e4d716d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ProcessStatsService( 1035): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-18-01.bin
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1869357769187; DSPS: 61395931; Offset : -4312694161
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1889359273502; DSPS: 62051341; Offset : -4312715620
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1909361995630; DSPS: 62706790; Offset : -4312709348
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1929363443539; DSPS: 63362198; Offset : -4312726569
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1949364908376; DSPS: 64017605; Offset : -4312696085
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1969366612326; DSPS: 64673021; Offset : -4312701067
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1989368291537; DSPS: 65328436; Offset : -4312700427
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2009370659603; DSPS: 65983874; Offset : -4312712628
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2029371649803; DSPS: 66639266; Offset : -4312698834
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2049373081670; DSPS: 67294673; Offset : -4312701476
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2069374539319; DSPS: 67950081; Offset : -4312708749
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2089376098999; DSPS: 68605492; Offset : -4312705465
,TIME-OUT KILL (timeout was 1800000ms)
```
