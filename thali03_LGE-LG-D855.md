#### Test 50650278cc6513d_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 271617797828; DSPS: 9040930; Offset : -4304583622
,D/AndroidRuntime( 6213): 
D/AndroidRuntime( 6213): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6213): CheckJNI is OFF
D/AndroidRuntime( 6213): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1029): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1961): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1029): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{a410913 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{a410913 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1029): AppWindowTokenEx init.. 
E/GBMv2   (  332): DFP En is all cleared set to be enabled
I/ActivityManager( 1029): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6233 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6213): Shutting down VM
V/ActivityManager( 1029): Display changed displayId=0
D/DSDPConnection( 1861): Display #0 changed.
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{357995ee co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{34878a8f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6233): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6233): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6233): Loading: webviewchromium
I/LibraryLoader( 6233): Time to load native libraries: 5 ms (timestamps 4798-4803)
,I/LibraryLoader( 6233): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6233): Binding Chromium to main looper Looper (main, tid 1) {30056b1b}
,I/LibraryLoader( 6233): Expected native library version number "",actual native library version number ""
I/chromium( 6233): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6233): Initializing chromium process, renderers=0
,W/art     ( 6233): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6233): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6233): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6233): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6233): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,V/AudioPolicyService(  316): registerClient() client 0xb146b0c0, uid 10311
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aca6505:true
I/Adreno-EGL( 6233): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6233): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6233): Build Date: 12/12/14 금
I/Adreno-EGL( 6233): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6233): Remote Branch: 
I/Adreno-EGL( 6233): Local Patches: 
I/Adreno-EGL( 6233): Reconstruct Branch: 
D/BluetoothAdapter( 6233): 181601464: getState() :  mService = null. Returning STATE_OFF
,W/chromium( 6233): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6233): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6233): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6233): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6233): CordovaWebView is running on device made by: LGE
,W/art     ( 6233): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6233): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6233): Render dirty regions requested: true
I/OpenGLRenderer( 6233): Initialized EGL, version 1.4
D/OpenGLRenderer( 6233): Enabling debug mode 0
,W/ActivityManager( 1029): Activity pause timeout for ActivityRecord{626d750 u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 6233): Validating map...
,D/SplitWindow( 1029): check instance of lgWin Window{21362257 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6233): LgDataFeature() Constructor: none
D/LgDataFeature( 6233): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3c623d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1459): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1029): Displayed com.test.thalitest/.MainActivity: +618ms (total +721ms)
I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{626d750 u0 com.test.thalitest/.MainActivity t4} time:275195
I/Timeline( 6233): Timeline: Activity_idle id: android.os.BinderProxy@386d0be8 time:275196
,D/JsMessageQueue( 6233): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6233): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6233): 
D/jxcore_app_log( 6233): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434955520
D/JX-Cordova( 6233): jxcore cordova android initializing
I/chromium( 6233): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6233): 
E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max
I/GBMv2   (  332): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6233): Initializing JXcore engine
W/jxcore-log( 6233): JXcore engine is ready
,W/jxcore-log( 6233): Starting JXcore engine
W/.test.thalitest( 6233): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10356]" dev="sockfs" ino=10356 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6233): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6233): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10567]" dev="sockfs" ino=10567 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6233): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6233): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29837]" dev="sockfs" ino=29837 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 6233): Background sticky concurrent mark sweep GC freed 123920(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.859ms total 124.731ms
W/jxcore-log( 6233): Platform android
W/jxcore-log( 6233): 
W/jxcore-log( 6233): Process ARCH arm
W/jxcore-log( 6233): 
,I/jxcore-log( 6233): JXcore Cordova bridge is ready!
I/jxcore-log( 6233): 
,W/jxcore-log( 6233): JXcore engine is started
I/Choreographer( 6233): Skipped 112 frames!  The application may be doing too much work on its main thread.
E/jxcore  ( 6233): Error!: missing ) after argument list
E/jxcore  ( 6233): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6233): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1029): Killing 5872:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10008/pid_5872/cgroup.procs: No such file or directory
,W/PluginManager( 6233): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 34ms. Plugin should use CordovaInterface.getThreadPool().
E/GBMv2   (  332): DFP En is all cleared set to be enabled
,D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{2387c11c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{354bf125 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
W/ScreenOrientationListener( 6233): Removing an inexistent observer!
I/[LGHome]EVENT( 2079): [Launcher.java:5338:onStart()]onStart
,I/[LGHome]EVENT( 2079): [Launcher.java:903:onResume()]onResume
D/InputDispatcher( 1029): Window went away: Window{21362257 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/[LGHome]EVENT( 2079): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2079): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1914): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2079): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2079): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2079): [Launcher.java:1056:onResume()]onResume end
I/ActivityManager( 1029): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6294 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2079): [Launcher.java:1114:onPause()]onPause
,D/ActionManagerService( 1914): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2079): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2079): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2079): , create_time: 1430558575574
I/GBoardWebViewUtils( 2079): , expire_time: 0
I/GBoardWebViewUtils( 2079): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2079): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2079): , display: false
I/GBoardWebViewUtils( 2079): , animation: false }
I/GBoardWebViewUtils( 2079): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2079): , create_time: 1430558575600
I/GBoardWebViewUtils( 2079): , expire_time: 0
I/GBoardWebViewUtils( 2079): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2079): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2079): , display: false
I/GBoardWebViewUtils( 2079): , animation: false }
,I/GBoardWebViewUtils( 2079): checkExpiredAndRemoveCard() card: GBoardCard = { id: new_feature_1111111111111_1449584869051
I/GBoardWebViewUtils( 2079): , create_time: 1449584869233
I/GBoardWebViewUtils( 2079): , expire_time: 0
I/GBoardWebViewUtils( 2079): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2079): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2079): , display: false
I/GBoardWebViewUtils( 2079): , animation: false }
D/WallpaperManager( 2079): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3c623d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1459): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]GBoardWebView( 2079): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/art     ( 6294): Almond Protected OAT
,D/WeatherApplication( 6294): removeAccount
D/WeatherApplication( 6294): Account.length = 0
E/WeatherApplication( 6294): OPERATOR:OPEN
,D/WeatherAncestor( 6294): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:59:47
D/Weather.Utils( 6294): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6294): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6294): 2 : This is isUpdating : false
D/Weather.Utils( 6294): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6294): 2 : All the weather widget is gone.
D/WeatherAncestor( 6294): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:59:47
I/ActivityManager( 1029): Killing 5508:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_5508/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2079): [Launcher.java:5349:onStop()]onStop
I/[LGHome]Launcher.Model( 2079): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2079): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{3e6fe1c u0 com.lge.launcher2/.Launcher t3} time:277925
,I/[LGHome]Launcher.Model( 2079): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2079): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2079): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2079): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2079): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2079): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2079): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2620): onStartCommand(). Type : 8
D/[Concierge]Service( 2620): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2620): Update widget ID : 11
,D/[Concierge]WidgetView( 2079): change position of spinner
I/[Concierge]WidgetView( 2079): initWebView(). Time : 1449586787951
D/[Concierge]Service( 2620): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2079): Return exist ConciergeWebView. Reuse : 775781631
,D/[Concierge]WidgetView( 2079): State Change : null -> AccInBeforeState
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2079): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2079): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1856e38e
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2079): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2079): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,D/[Concierge]WidgetView( 2079): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2079): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2079): Widget kill message received. Destory myself. My : 1449586538079, New one : 1449586787951
,D/[Concierge]WidgetView( 2079): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2079): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2079): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2079): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2079): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2079): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2079): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2079): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2079): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2079): Timeline: Activity_idle id: android.os.BinderProxy@3d75cf9a time:278170
,I/chromium( 2079): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2079): onReloaded()
,I/GBoardWebViewClient( 2079): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1914): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2712): onEvent() : ACTION_BOARD_ENABLED
I/ActivityManager( 1029): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6347 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActionManagerService( 1914): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2712): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2712): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2712): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2079): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2079): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2079): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
,D/GBoardWebViewUtils( 2079): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2079): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2079): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
V/FormManager( 6347): BoardCategory : com.lge.intent.category.gboard.MYWELLNESS, true
,I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6369 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 6347): Network not available. Please check & try again.
V/FormManager( 6347): Network unavailable.
,V/FormManager( 6347): Network unavailable.
I/ActivityManager( 1029): Killing 5533:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10019/pid_5533/cgroup.procs: No such file or directory
,E/ActivityThread( 6369): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6369): No ProfileInfo entries
I/LG Account v2.2( 6369): isEnabled: false
I/Feature ( 6369): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6369): [Lifetracker]Country: EU
I/Feature ( 6369): [Lifetracker]Operator: OPEN
I/Feature ( 6369): [Lifetracker]Ranking support: false
I/Feature ( 6369): [Lifetracker]Comfort support: false
I/Feature ( 6369): [Lifetracker]Accessory: true
I/Feature ( 6369): [Lifetracker]Health device: true
I/Feature ( 6369): [Lifetracker]Extra Pedometer: false
I/Feature ( 6369): [Lifetracker]Blood glucose device: false
I/Feature ( 6369): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 6369): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
,I/GBoardStateUtil( 6369): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6369): gboardCategory : com.lge.intent.category.gboard.MYWELLNESS, gboardState : true
,I/ActivityManager( 1029): Killing 5893:com.lge.email/u0a23 (adj 15): empty #17
I/GBoardtInterface( 2079): exportHTML()
,I/GBoardtInterface( 2079): exportHTML()
,I/LIA_Informant_LogCore( 2712): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2712): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_5893/cgroup.procs: No such file or directory
I/LIA_MrGDBLogger_LogCore( 2712): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2712): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
I/LIA_S4URecommender_LogCore( 2712): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2712): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
D/CoreEventReceiver( 6369): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
V/FormManager( 6347): BoardCategory : com.lge.intent.category.gboard.DOYOUKNOW, true
,I/GBoardtInterface( 2079): exportHTML()
I/GBoardStateUtil( 6369): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6369): gboardCategory : com.lge.intent.category.gboard.DOYOUKNOW, gboardState : true
W/FormManager( 6347): Network not available. Please check & try again.
,I/LIA_Informant_LogCore( 2712): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2712): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_Informant_BoardStateUtil( 2712): defaultHomePackage : com.lge.launcher2
D/LIA_Informant_TaskActivator( 2712): DefaultHomeCondition is satisfied
V/FormManager( 6347): Network unavailable.
V/FormManager( 6347): Network unavailable.
I/LIA_Informant_BoardStateUtil( 2712): isEnabledConciergeBoard() : count > 0 - true
,D/LIA_Informant_TaskActivator( 2712): BoardCondition is satisfied
W/LIA_Informant_TaskActivator( 2712): setActivation() : Informant Task - ACTIVATION
D/LIA_Informant_LGIntelligentAgent( 2712): activateLIAService : Informant / true
I/LIA_Informant_LIATaskLoader( 2712): getTaskSdkClassName : com.lge.ia.LIAInformant
D/LIA_Informant_LIATaskLoader( 2712): classLoad - TargetClass : com.lge.ia.LIAInformant
I/LIA_Informant_LIATaskLoader( 2712): createLIAService - Success
I/LIA_Informant_LGIntelligentAgent( 2712): activateLIAService : startService success. (You may need to check whether its property has changed or not!)
D/LIA_Informant_LIARemoteService( 2712): onStartCommand() : LIARemoteService started! - (Id :5), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
I/LIA_Informant_InformantService( 2712): isNowInActivationCondition()
I/LIA_Informant_BoardStateUtil( 2712): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 2712): ActivationConditionHandler : LGHome condition is true
I/LIA_Informant_BoardStateUtil( 2712): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 2712): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 2712): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
I/LIA_Informant_InformantService( 2712): getTaskPropertiesAtFirstStarting()
D/LIA_Informant_LIARemoteService( 2712): --> LIA task activation intent from com.lge.ia.task.informant for Informant(activation: true)
D/LIA_Informant_LIARemoteService( 2712): updateTaskProperty() : 
I/LIA_Informant_LIARemoteService( 2712): --> LIA task activation intent from com.lge.ia.task.informant, but it's same as the current setting or couldn't chagne it so just passed !! (Informant activation : true)
I/LIA_MrGDBLogger_LogCore( 2712): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2712): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
,I/LIA_S4URecommender_LogCore( 2712): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2712): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max
I/GBMv2   (  332): DFP Enabled. Ignore VFP set
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2079): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0,
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2079): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 2079): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 2079): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
I/GBoardtInterface( 2079): onAnimationFinished
,I/GBoardtInterface( 2079): onAnimationFinished
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 291619661454; DSPS: 9696349; Offset : -4304520481
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 311622112489; DSPS: 10351790; Offset : -4304541422
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=217447474, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{3d521a86 type 2 when 292492 com.google.android.gms} when 292492
D/[Concierge]Service( 2620): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=217447474 [*alarm*], flags=0x0
,I/VacuumService( 2123): Vacuum at: now=1449586828126 tag=VacuumService
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 331623770450; DSPS: 11007204; Offset : -4304531462
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=217447474, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,D/[Concierge]Service( 2620): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=217447474 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 351625420963; DSPS: 11662618; Offset : -4304528848
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4909): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4909): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4909): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4909): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4909): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4909): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4909): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2784ef19 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 4909): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]LGPowerUI( 1459): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1459): On Skip Timer : true
,D/WifiController( 1029): battery changed pluggedType: 2
D/LEDHandler( 1961): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1961): Battery Level Remaining: 100%
D/LEDHandler( 1961): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1459): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1459): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1459): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3148): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3148): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 371627297258; DSPS: 12318039; Offset : -4304513864
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 391628702042; DSPS: 12973446; Offset : -4304543328

```
