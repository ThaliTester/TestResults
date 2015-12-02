#### Test 52383621d5a0cb8_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 267725774426; DSPS: 8913606; Offset : -4308022741
,D/AndroidRuntime( 6450): 
D/AndroidRuntime( 6450): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6450): CheckJNI is OFF
D/AndroidRuntime( 6450): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1952): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1036): create ActivityStackEx
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{b9d09cb #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{b9d09cb #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1d646d91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1404): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1404): mCoverWidth: 0 ,mCoverHeight: 0
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  330): DFP En is all cleared set to be enabled
I/ActivityManager( 1036): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6469 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6450): Shutting down VM
V/ActivityManager( 1036): Display changed displayId=0
D/DSDPConnection( 1855): Display #0 changed.
D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{6db0560 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{2f24ba19 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 6469): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6469): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6469): Loading: webviewchromium
I/LibraryLoader( 6469): Time to load native libraries: 4 ms (timestamps 3636-3640)
I/LibraryLoader( 6469): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6469): Binding Chromium to main looper Looper (main, tid 1) {894bdd3}
I/LibraryLoader( 6469): Expected native library version number "",actual native library version number ""
,I/chromium( 6469): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6469): Initializing chromium process, renderers=0
W/art     ( 6469): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6469): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  312): registerClient() client 0xb101ce80, uid 10311
W/chromium( 6469): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6469): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6469): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27a59ffd:true
,I/Adreno-EGL( 6469): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6469): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6469): Build Date: 12/12/14 금
I/Adreno-EGL( 6469): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6469): Remote Branch: 
I/Adreno-EGL( 6469): Local Patches: 
I/Adreno-EGL( 6469): Reconstruct Branch: 
,W/chromium( 6469): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6469): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6469): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6469): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6469): CordovaWebView is running on device made by: LGE
,W/art     ( 6469): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6469): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6469): Render dirty regions requested: true
I/OpenGLRenderer( 6469): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6469): Enabling debug mode 0
D/Atlas   ( 6469): Validating map...
,D/SplitWindow( 1036): check instance of lgWin Window{3e88038f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6469): LgDataFeature() Constructor: none
,D/LgDataFeature( 6469): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1454): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1454): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1454):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1454): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26c045ae,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1036): Displayed com.test.thalitest/.MainActivity: +607ms (total +717ms)
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{28db35a8 u0 com.test.thalitest/.MainActivity t2} time:284070
,I/Timeline( 6469): Timeline: Activity_idle id: android.os.BinderProxy@2bd8c1c3 time:284077
I/chromium( 6469): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6469): 
,D/JsMessageQueue( 6469): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6469): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435084032
D/JX-Cordova( 6469): jxcore cordova android initializing
,E/GBMv2   (  330): DFP En is all cleared set to be enabled
E/GBMv2   (  330): Set value is all cleared set the max
I/GBMv2   (  330): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6469): Initializing JXcore engine
W/jxcore-log( 6469): JXcore engine is ready
W/jxcore-log( 6469): Starting JXcore engine
W/.test.thalitest( 6469): type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[8958]" dev="sockfs" ino=8958 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6469): type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6469): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[9136]" dev="sockfs" ino=9136 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6469): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6469): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[31769]" dev="sockfs" ino=31769 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6469): Platform android
W/jxcore-log( 6469): 
W/jxcore-log( 6469): Process ARCH arm
W/jxcore-log( 6469): 
I/jxcore-log( 6469): JXcore Cordova bridge is ready!
I/jxcore-log( 6469): 
W/jxcore-log( 6469): JXcore engine is started
,E/jxcore  ( 6469): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 6469): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 6469): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager( 1036): Killing 6162:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10008/pid_6162/cgroup.procs: No such file or directory
,W/PluginManager( 6469): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 34ms. Plugin should use CordovaInterface.getThreadPool().
,E/GBMv2   (  330): DFP En is all cleared set to be enabled
,D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{bad0ade co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
,D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{37b174bf co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
W/ScreenOrientationListener( 6469): Removing an inexistent observer!
I/[LGHome]EVENT( 2071): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2071): [Launcher.java:903:onResume()]onResume
,I/[LGHome]EVENT( 2071): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2071): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]GBoardWebView( 2071): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1906): notifyUserLog: 1000003
,D/LIA_Informant_ActionManagerMessageHandler( 2695): handleMessage: what(1000) actionID(0x1000003)
,I/[LGHome]LGActivityUtil( 2071): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2071): [Launcher.java:1056:onResume()]onResume end
D/InputDispatcher( 1036): Window went away: Window{3e88038f u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1036): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6545 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SplitWindowManager( 1036): removeStackAndNeedHomeResume ActivityStack{2217d1c6 stackId=1, 0 tasks}
I/[LGHome]EVENT( 2071): [Launcher.java:1114:onPause()]onPause
I/chromium( 6469): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6469): 
D/ActionManagerService( 1906): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2071): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2695): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2695): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2071): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2071): , create_time: 1430558575574
I/GBoardWebViewUtils( 2071): , expire_time: 0
I/GBoardWebViewUtils( 2071): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2071): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2071): , display: false
I/GBoardWebViewUtils( 2071): , animation: false }
I/GBoardWebViewUtils( 2071): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2071): , create_time: 1430558575600
I/GBoardWebViewUtils( 2071): , expire_time: 0
I/GBoardWebViewUtils( 2071): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2071): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2071): , display: false
I/GBoardWebViewUtils( 2071): , animation: false }
I/GBoardWebViewUtils( 2071): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1448553258556
I/GBoardWebViewUtils( 2071): , create_time: 1448553259193
I/GBoardWebViewUtils( 2071): , expire_time: 0
I/GBoardWebViewUtils( 2071): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1448553258556&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2071): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2071): , display: false
I/GBoardWebViewUtils( 2071): , animation: false }
D/WallpaperManager( 2071): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/PhoneStatusBar( 1454): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26c045ae,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1454): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1454):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1454): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]GBoardWebView( 2071): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/art     ( 6545): Almond Protected OAT
,D/WeatherApplication( 6545): removeAccount
,D/WeatherApplication( 6545): Account.length = 0
,E/WeatherApplication( 6545): OPERATOR:OPEN
D/WeatherAncestor( 6545): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:44:34
,I/[LGHome]EVENT( 2071): [Launcher.java:5349:onStop()]onStop
D/Weather.Utils( 6545): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6545): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6545): 2 : This is isUpdating : false
D/Weather.Utils( 6545): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6545): 2 : All the weather widget is gone.
D/WeatherAncestor( 6545): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:44:34
I/ActivityManager( 1036): Killing 5638:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_5638/cgroup.procs: No such file or directory
,I/[LGHome]Launcher.Model( 2071): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{3f54b260 u0 com.lge.launcher2/.Launcher t1} time:287098
,I/[LGHome]Launcher.Model( 2071): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2071): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2071): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2071): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2071): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2603): onStartCommand(). Type : 8
D/[Concierge]Service( 2603): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2603): Update widget ID : 11
,D/[Concierge]WidgetView( 2071): change position of spinner
I/[Concierge]WidgetView( 2071): initWebView(). Time : 1449056674655
D/[Concierge]Service( 2603): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2071): Return exist ConciergeWebView. Reuse : 157011260
,D/[Concierge]WidgetView( 2071): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2071): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2071): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@359e4918
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2071): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2071): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2071): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2071): Widget kill message received. Destory myself. My : 1449056415271, New one : 1449056674655
,D/[Concierge]WidgetView( 2071): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2071): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2071): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2071): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2071): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2071): Timeline: Activity_idle id: android.os.BinderProxy@10200700 time:287332
,I/chromium( 2071): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2071): onReloaded()
,I/GBoardWebViewClient( 2071): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2695): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2695): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1906): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2695): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2695): onEvent() : ACTION_BOARD_ENABLED
I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6579 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActionManagerService( 1906): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2695): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2695): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2695): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2695): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2695): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2071): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2071): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,D/GBoardUriUtils( 2071): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2071): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2071): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1448553258556&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2071): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1448553258556&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 287726883175; DSPS: 9569003; Offset : -4308042387
,I/ActivityManager( 1036): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6604 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/FormManager( 6579): BoardCategory : com.lge.intent.category.gboard.MYWELLNESS, true
I/art     (  334): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 15.361ms
,I/art     (  334): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 256us total 13.904ms
,I/art     (  334): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 11.963ms
,W/FormManager( 6579): Network not available. Please check & try again.
V/FormManager( 6579): Network unavailable.
V/FormManager( 6579): Network unavailable.
I/ActivityManager( 1036): Killing 5660:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_5660/cgroup.procs: No such file or directory
,E/ActivityThread( 6604): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6604): No ProfileInfo entries
I/LG Account v2.2( 6604): isEnabled: false
I/Feature ( 6604): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6604): [Lifetracker]Country: EU
I/Feature ( 6604): [Lifetracker]Operator: OPEN
I/Feature ( 6604): [Lifetracker]Ranking support: false
I/Feature ( 6604): [Lifetracker]Comfort support: false
I/Feature ( 6604): [Lifetracker]Accessory: true
I/Feature ( 6604): [Lifetracker]Health device: true
I/Feature ( 6604): [Lifetracker]Extra Pedometer: false
I/Feature ( 6604): [Lifetracker]Blood glucose device: false
I/Feature ( 6604): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 6604): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
I/GBoardStateUtil( 6604): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6604): gboardCategory : com.lge.intent.category.gboard.MYWELLNESS, gboardState : true
,I/ActivityManager( 1036): Killing 6187:com.lge.email/u0a23 (adj 15): empty #17
,I/LIA_Informant_LogCore( 2695): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2695): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
,W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6187/cgroup.procs: No such file or directory
I/LIA_MrGDBLogger_LogCore( 2695): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2695): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
I/LIA_S4URecommender_LogCore( 2695): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2695): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
,D/CoreEventReceiver( 6604): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
,V/FormManager( 6579): BoardCategory : com.lge.intent.category.gboard.DOYOUKNOW, true
I/GBoardtInterface( 2071): exportHTML()
W/FormManager( 6579): Network not available. Please check & try again.
I/GBoardStateUtil( 6604): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6604): gboardCategory : com.lge.intent.category.gboard.DOYOUKNOW, gboardState : true
,I/LIA_Informant_LogCore( 2695): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2695): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_Informant_BoardStateUtil( 2695): defaultHomePackage : com.lge.launcher2
D/LIA_Informant_TaskActivator( 2695): DefaultHomeCondition is satisfied
,V/FormManager( 6579): Network unavailable.
,V/FormManager( 6579): Network unavailable.
,I/LIA_Informant_BoardStateUtil( 2695): isEnabledConciergeBoard() : count > 0 - true
D/LIA_Informant_TaskActivator( 2695): BoardCondition is satisfied
W/LIA_Informant_TaskActivator( 2695): setActivation() : Informant Task - ACTIVATION
D/LIA_Informant_LGIntelligentAgent( 2695): activateLIAService : Informant / true
I/LIA_Informant_LIATaskLoader( 2695): getTaskSdkClassName : com.lge.ia.LIAInformant
D/LIA_Informant_LIATaskLoader( 2695): classLoad - TargetClass : com.lge.ia.LIAInformant
I/LIA_Informant_LIATaskLoader( 2695): createLIAService - Success
I/LIA_Informant_LGIntelligentAgent( 2695): activateLIAService : startService success. (You may need to check whether its property has changed or not!)
,D/LIA_Informant_LIARemoteService( 2695): onStartCommand() : LIARemoteService started! - (Id :5), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
I/LIA_Informant_InformantService( 2695): isNowInActivationCondition()
I/LIA_Informant_BoardStateUtil( 2695): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 2695): ActivationConditionHandler : LGHome condition is true
I/LIA_Informant_BoardStateUtil( 2695): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 2695): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 2695): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
I/LIA_Informant_InformantService( 2695): getTaskPropertiesAtFirstStarting()
D/LIA_Informant_LIARemoteService( 2695): --> LIA task activation intent from com.lge.ia.task.informant for Informant(activation: true)
D/LIA_Informant_LIARemoteService( 2695): updateTaskProperty() : 
I/LIA_Informant_LIARemoteService( 2695): --> LIA task activation intent from com.lge.ia.task.informant, but it's same as the current setting or couldn't chagne it so just passed !! (Informant activation : true)
I/LIA_MrGDBLogger_LogCore( 2695): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2695): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_S4URecommender_LogCore( 2695): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2695): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
,I/GBoardtInterface( 2071): exportHTML()
,I/GBoardtInterface( 2071): exportHTML()
,E/GBMv2   (  330): DFP En is all cleared set to be enabled
E/GBMv2   (  330): Set value is all cleared set the max
I/GBMv2   (  330): DFP Enabled. Ignore VFP set
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2071): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2071): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 2071): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2071): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
,I/GBoardtInterface( 2071): onAnimationFinished
,I/GBoardtInterface( 2071): onAnimationFinished
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 307728505511; DSPS: 10224416; Offset : -4308038134
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 327731092223; DSPS: 10879861; Offset : -4308045677
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 347732795497; DSPS: 11535276; Offset : -4308020791
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1d646d91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2114): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2114): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2114): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2114): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 5777): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5777): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5777): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5777): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 367734415853; DSPS: 12190690; Offset : -4308048515
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 387735909751; DSPS: 12846099; Offset : -4308049717
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 407737678441; DSPS: 13501517; Offset : -4308050969
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 427739553902; DSPS: 14156938; Offset : -4308037210
,I/[SystemUI]LGPowerUI( 1454): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1454): On Skip Timer : true
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1036): battery changed pluggedType: 2
D/HeadsetStateMachine( 3708): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1454): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1454): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1952): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1952): Battery Level Remaining: 100%
D/LEDHandler( 1952): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1454): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4085): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4085): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=854739434, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{32cdb35a type 2 when 387279 com.google.android.gms} when 387279
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=854739434 [*alarm*], flags=0x0
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 447741704573; DSPS: 14812368; Offset : -4308022666
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 467743565763; DSPS: 15467790; Offset : -4308053722
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 487745279297; DSPS: 16123206; Offset : -4308049146
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 507746765799; DSPS: 16778614; Offset : -4308027488
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 527748464386; DSPS: 17434030; Offset : -4308037755
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 547749966722; DSPS: 18089439; Offset : -4308030806
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 567751533172; DSPS: 18744851; Offset : -4308051348
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 587753046238; DSPS: 19400260; Offset : -4308033644
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 607754557688; DSPS: 20055670; Offset : -4308047969
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 627756060649; DSPS: 20711079; Offset : -4308040421
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 647757772517; DSPS: 21366495; Offset : -4308037563
,I/ActivityManager( 1036): Killing 6056:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10004/pid_6056/cgroup.procs: No such file or directory
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2114): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2114): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2114): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2114): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 5777): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5777): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5777): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5777): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1d646d91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 667759383395; DSPS: 22021908; Offset : -4308044169
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 687761818231; DSPS: 22677348; Offset : -4308050686
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 707763553640; DSPS: 23332765; Offset : -4308054806
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 727765070767; DSPS: 23988174; Offset : -4308032859
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 747766799979; DSPS: 24643591; Offset : -4308043227
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 767768487992; DSPS: 25299006; Offset : -4308033785
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 787769941109; DSPS: 25954414; Offset : -4308045538
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 807772307977; DSPS: 26609851; Offset : -4308028262
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=854739434, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/Finsky  ( 5777): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{276bb75 type 0 when 1449057075207 com.android.vending} when 1449057075207
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2b29a70a type 2 when 772054 com.google.android.gms} when 772054
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=854739434 [*alarm*], flags=0x0
,W/Finsky  ( 5777): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1036): Explicit concurrent mark sweep GC freed 21337(1019KB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 2.398ms total 114.512ms
,W/Finsky  ( 5777): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 5777): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 5777): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5777): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5777): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
D/DeviceConnectionService( 1820): client connected with version: 7571000
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 827773986927; DSPS: 27265266; Offset : -4308027804
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{14248b3c type 0 when 1449057226560 com.android.vending} when 1449057226560
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2114): Explicit concurrent mark sweep GC freed 30332(1747KB) AllocSpace objects, 5(720KB) LOS objects, 51% free, 30MB/62MB, paused 1.072ms total 28.921ms
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5777): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5777): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5777): [1] 5.onFinished: Scheduling replication attempt 1.
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 847775604160; DSPS: 27920679; Offset : -4308028212
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 867777119881; DSPS: 28576089; Offset : -4308038188
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=854739434, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{16023c1f type 0 when 1449057254564 com.android.vending} when 1449057254564
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=854739434 [*alarm*], flags=0x0
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5777): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5777): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5777): [1] 5.onFinished: Scheduling replication attempt 2.
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 887778870342; DSPS: 29231506; Offset : -4308027385
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{1dd7a86e type 0 when 1449057276131 com.android.vending} when 1449057276131
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5777): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5777): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5777): [1] 5.onFinished: Scheduling replication attempt 3.
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 907781414241; DSPS: 29886950; Offset : -4308046988
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=854739434, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{1b70c959 type 0 when 1449057302684 com.android.vending} when 1449057302684
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=854739434 [*alarm*], flags=0x0
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5777): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5777): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5777): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 927783057827; DSPS: 30542364; Offset : -4308051248
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3333ea93 type 2 when 941499 com.android.bluetooth} when 941499
,W/bt-smp  ( 3708): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3708): Plain text(LSB ~ MSB) = 3f 53 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3708): Encrypted text(LSB ~ MSB) = 3f d3 fc 45 57 8b fa 42 4b be d8 92 72 6f 0b 16 
W/bt-btm  ( 3708): Stopping oneshot timer
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 947784667767; DSPS: 31197776; Offset : -4308028300
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{2649bac9 type 0 when 1449057331915 com.android.vending} when 1449057331915
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5777): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5777): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5777): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2114): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2114): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2114): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2114): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5777): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5777): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5777): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5777): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1d646d91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 967786269895; DSPS: 31853189; Offset : -4308043681
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=854739434, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{3c27e7ad type 0 when 1449057362190 com.android.vending} when 1449057362190
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=854739434 [*alarm*], flags=0x0
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5777): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5777): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5777): [1] 5.onFinished: Giving up after 6 failures.
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 987787812855; DSPS: 32508599; Offset : -4308026548
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1007789294567; DSPS: 33164008; Offset : -4308040302
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1027790850445; DSPS: 33819419; Offset : -4308040769
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1047792384761; DSPS: 34474829; Offset : -4308032044
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1067794580170; DSPS: 35130261; Offset : -4308034032
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1087796005943; DSPS: 35785668; Offset : -4308042637
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1107797507810; DSPS: 36441077; Offset : -4308036079
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1127799180979; DSPS: 37096492; Offset : -4308041429
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1147801353316; DSPS: 37751923; Offset : -4308035892
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1167803187526; DSPS: 38407343; Offset : -4308032581
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1187804635332; DSPS: 39062751; Offset : -4308049539
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1207806098606; DSPS: 39718159; Offset : -4308051266
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
I/UsageStatsService( 1036): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1227807690994; DSPS: 40373571; Offset : -4308045688
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1247809116403; DSPS: 41028977; Offset : -4308024061
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2114): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2114): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2114): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2114): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5777): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5777): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5777): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5777): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1d646d91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1267810431499; DSPS: 41684381; Offset : -4308049760
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1287811913992; DSPS: 42339789; Offset : -4308034351
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1307813437942; DSPS: 42995199; Offset : -4308036332
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1327814903716; DSPS: 43650607; Offset : -4308035115
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1347816376885; DSPS: 44306015; Offset : -4308026971
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1367817825836; DSPS: 44961423; Offset : -4308042864
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1387819372860; DSPS: 45616833; Offset : -4308021667
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1407821186186; DSPS: 46272253; Offset : -4308039266
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1427822922064; DSPS: 46927670; Offset : -4308043098
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1447824395440; DSPS: 47583078; Offset : -4308034540
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1467825960798; DSPS: 48238489; Offset : -4308025474
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1487827379488; DSPS: 48893896; Offset : -4308041162
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1507828876043; DSPS: 49549305; Offset : -4308040046
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1527830454213; DSPS: 50204717; Offset : -4308048583
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1547831922383; DSPS: 50860125; Offset : -4308045438
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2114): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2114): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2114): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2114): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5777): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5777): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5777): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5777): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1d646d91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1567833317999; DSPS: 51515530; Offset : -4308023061
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1587835157314; DSPS: 52170951; Offset : -4308045345
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1607836702047; DSPS: 52826361; Offset : -4308026438
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1627838386570; DSPS: 53481777; Offset : -4308050926
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1647840240469; DSPS: 54137197; Offset : -4308028056
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1667841958430; DSPS: 54792614; Offset : -4308049674
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1687843736288; DSPS: 55448032; Offset : -4308041732
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1707845234091; DSPS: 56103441; Offset : -4308039394
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1727846740490; DSPS: 56758850; Offset : -4308028226
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1747848173348; DSPS: 57414257; Offset : -4308029955
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1454): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1454): On Skip Timer : true
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1036): battery changed pluggedType: 2
D/HeadsetStateMachine( 3708): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1454): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1454): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1952): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1952): Battery Level Remaining: 100%
D/LEDHandler( 1952): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1454): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4085): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4085): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1767849655892; DSPS: 58069666; Offset : -4308042538
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1787851755832; DSPS: 58725095; Offset : -4308048311
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1807853659679; DSPS: 59380517; Offset : -4308036554
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1827855252275; DSPS: 60035929; Offset : -4308030767
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=854739434, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,W/bt-smp  ( 3708): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3708): Plain text(LSB ~ MSB) = 94 08 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3708): Encrypted text(LSB ~ MSB) = 84 5f 97 85 24 8d 4e 79 05 86 e7 92 5f d1 20 31 
,W/bt-btm  ( 3708): Stopping oneshot timer
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{315cb79a type 2 when 1841520 com.android.bluetooth} when 1841520
I/ProcessStatsService( 1036): Prepared write state in 11ms
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,I/ProcessStatsService( 1036): Prepared write state in 7ms
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=854739434 [*alarm*], flags=0x0
,I/ProcessStatsService( 1036): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-15-49.bin
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1847857071069; DSPS: 60691349; Offset : -4308043133
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1867867132781; DSPS: 61347039; Offset : -4308050711
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 29294(1278KB) AllocSpace objects, 10(842KB) LOS objects, 33% free, 44MB/67MB, paused 2.415ms total 146.070ms
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2114): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2114): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2114): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2114): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2114): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 5777): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5777): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5777): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5777): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5777): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1d646d91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1887868924596; DSPS: 62002457; Offset : -4308030426
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1907871211933; DSPS: 62657892; Offset : -4308031933
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1927872855362; DSPS: 63313306; Offset : -4308036480
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1947874377333; DSPS: 63968716; Offset : -4308040282
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1967876247742; DSPS: 64624137; Offset : -4308031473
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{276fecec type 2 when 1502649 com.google.android.gms} when 1502649
V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{f5ff8b5 type 0 when 1449057909218 com.google.android.gms} when 1449057909218
,I/ActivityManager( 1036): Killing 6309:com.lge.bnr/1000 (adj 15): empty for 1861s
I/ActivityManager( 1036): Killing 6290:com.lge.eula/1000 (adj 15): empty for 1861s
,I/ActivityManager( 1036): Killing 5745:com.google.android.apps.plus/u0a97 (adj 15): empty for 1861s
,I/ActivityManager( 1036): Killing 6243:com.google.android.apps.docs/u0a61 (adj 15): empty for 1861s
,I/ActivityManager( 1036): Killing 5710:com.lge.lockscreensettings/u0a80 (adj 15): empty for 1861s
,I/ActivityManager( 1036): Killing 6207:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty for 1862s
,I/ActivityManager( 1036): Killing 5690:com.android.gallery3d/u0a27 (adj 15): empty for 1863s
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6309/cgroup.procs: No such file or directory
,W/libprocessgroup( 1036): failed to open /acct/uid_10097/pid_5745/cgroup.procs: No such file or directory
W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6243/cgroup.procs: No such file or directory
W/libprocessgroup( 1036): failed to open /acct/uid_10080/pid_5710/cgroup.procs: No such file or directory
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6207/cgroup.procs: No such file or directory
W/libprocessgroup( 1036): failed to open /acct/uid_10027/pid_5690/cgroup.procs: No such file or directory
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6290/cgroup.procs: No such file or directory
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
,I/EventLogService( 2322): Aggregate from 1449056109157 (log), 1449056109157 (data)
,I/GLSUser ( 2114): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2114): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2114): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2114): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2114): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1987877945495; DSPS: 65279553; Offset : -4308042938
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2007879452518; DSPS: 65934962; Offset : -4308031276
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2027881541783; DSPS: 66590391; Offset : -4308047620
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2047883007503; DSPS: 67245799; Offset : -4308046848
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2067884791298; DSPS: 67901217; Offset : -4308032969
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2087886505613; DSPS: 68556633; Offset : -4308027664
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2107888292064; DSPS: 69212052; Offset : -4308041776
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,TIME-OUT KILL (timeout was 1800000ms)
```
